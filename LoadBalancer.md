## Load Balancer
---

[Visuals](https://www.slideshare.net/raja.s.75/load-balancer)

* Load balancing is a technique to spread work between many servers , processes, disks or other resources in order to get optimal resource (virtual or physical) utilization and decrease computing time. 
* A load balancer can be used to increase the capacity of a server farm beyond that of a single server. 
* It can also allow the service to continue even in the face of server down time due to server failure or server maintenance. 
* A load balancer consists of a virtual server (also referred to as vserver or VIP) which, in turn, consists of an IP address and port. 
* Virtual server is bound to a number of physical services running on the physical servers in a server farm. 
* A client sends a request to the virtual server, which in turn selects a physical server in the server farm and directs this request to the selected physical server.
* Different virtual servers can be configured for different sets of physical services, such as TCP and UDP services in general. 
* Application specific virtual server may exist to support HTTP, FTP, SSL, DNS, etc. 
* The load balancing methods manage the selection of an appropriate physical server in a server farm. 

### Sticky Sessions or Persistence

* Persistence can be configured on a virtual server; once a server is selected, subsequent requests from the client are directed to the same server. 
* Persistence is sometimes necessary in applications where client state is maintained on the server, but the use of persistence can cause problems in failure and other situations.
* A more common method of managing persistence is to store state information in a shared database, which can be accessed by all real servers, and to link this information to a client with a small token such as a cookie, which is sent in every client request.

### Load Balancing between REST Services

* Load balancers also perform server monitoring of services in a web server farm
* In case of failure of a service, the load balancer continues to perform load balancing across the remaining services that are UP.
* In case of failure of all the servers bound to a virtual server, requests may be sent to a backup virtual server (if configured) or optionally redirected to a configured URL. 
* In Global Server Load Balancing (GSLB) the load balancer distributes load to a geographically distributed set of server farms based on health, server load or proximity.


[Visuals](https://www.slideshare.net/raja.s.75/load-balancer)
