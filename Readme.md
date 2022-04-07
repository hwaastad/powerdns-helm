# PowerDNS
This project contains complete DNS Project:
* Authoritive Server
* Recursor
* DNSDist
* PowerDNS Admin

I is kind of opiniated, but will work as a Kubernetes deployment for external services.
## Setup
### kube-apiserver
* kube-apiserver needs alpha feature gate:
  ```
  MixedProtocolLBService=true
  ```