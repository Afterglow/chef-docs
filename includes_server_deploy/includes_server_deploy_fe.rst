.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

A scaled front end deployment is ideal for organizations that know they will need to plan for high availability, but also have internal requirements for back end high availability that are different from the scaled back end scenario. This is fine, of course. |chef server oec| can be configured for back end high availability in many different ways. This scenario recognizes that the back end high availability decisions are your own, but that deploying for front end high availability is also a requirement.

.. image:: ../../images/oec_server_deploy_fe.png

where:

* The front end servers handle requests from the |chef client| (where the requests are made by the |chef client| as it configures a node), from workstations (where the request is typically in the form of a |knife| command), and by users who log on to the |chef server| web user interface. Load balancing is typically configured for the front end servers by using a combination of hardware (such as |f5| or |netscalar|), |ssl| off-loading, and a round-robin load balancing algorithm.
* The back end server is shown as a single machine. In some organizations, a single back end machine is fine, but more commonly, this scenario represents an organization that has different requirements from the "asynchronous block level replication of logical volume managers (|drbd|), a shared virtual IP address, and access to the primary server (via the shared virtual IP address) maintained by |keepalived|" approach that is the default scenario described in the documentation for |chef server oec|. If a different approach is needed, please consult with |opscode| support to help ensure that all of the critical configuration requirements are understood.

