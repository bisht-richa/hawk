### Group

Resource groups contain a set of resources that need to be located
together, be started sequentially and stopped in the reverse order.

To create a group, define an ID and select the resources that will be
members of the group.

An example for use of a group is a Web server that requires an IP
address and a file system. Configure IP address and file system as
separate resources and combine them into a cluster resource group. In
case of a software or hardware malfunction, the group will fail over
to another cluster node, similar to an individual cluster resource.
