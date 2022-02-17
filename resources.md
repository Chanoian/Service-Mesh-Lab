#VirtualService
Defines rules that control how requests for service are routed within service mesh

#DestinationRule
Configures set of policies to be applied to request after VirtualService routing occurs

#ServiceEntry
Enables requests to services outside service mesh
Gateway	Configures load balancer operating at edge of mesh for:
• HTTP/TCP ingress traffic to mesh application
• Egress traffic to external services

#Sidecar
Configures sidecar proxies attached to application workloads running inside mesh