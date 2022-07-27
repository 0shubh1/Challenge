We can use ARM template to deploy our resouces for Tier 3 architecture:
1. Virtual entwork will be having four subnets.
2. Each subnet will have network security group, so total 4 NSGs.
3. We have used external and interal load balancers.
4. External LB to balanance HTTP and HTTPS traffic to web servers.
5. Internal LB will be used for traffic to app VMs.
6. We have used parameters to increase the readability of the whole JSON template.
7. Virtual Machine Availability sets for Web, App and DB tier to provide logical grouping of VMs that allows Azure to understand 
how our application is built to provide for redundancy and availability.
