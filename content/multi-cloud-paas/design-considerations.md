# PaaS Design Considerations

* In the case of a web application, the port and the IP is moving target, provided by the platform
* Application deployments are ephemeral, similar to containers on Kubernetes
* When an application crashes it can be reprovisioned or restarted
* When application scales out/in new instances are deployed and destroyed
* State is better to be externalized whether in-memory or persistent
* Configuration and secrets should not be embedded in the application code
* It is rather difficult to debug a PaaS application in production, robust logging is required



