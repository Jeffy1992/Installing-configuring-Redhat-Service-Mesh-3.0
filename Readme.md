By using Redhat offical Documentation i have perform this installation
https://docs.redhat.com/en/documentation/red_hat_openshift_service_mesh/3.1/html/installing/index

First install Service mesh operator
https://docs.redhat.com/en/documentation/red_hat_openshift_service_mesh/3.1/html/installing/ossm-installing-service-mesh#ossm-installing-operator_ossm-installing-openshift-service-mesh

Then install istio
https://docs.redhat.com/en/documentation/red_hat_openshift_service_mesh/3.1/html/installing/ossm-installing-service-mesh#ossm-creating-istio-project_ossm-installing-openshift-service-mesh

create istio cni
https://docs.redhat.com/en/documentation/red_hat_openshift_service_mesh/3.1/html/installing/ossm-installing-service-mesh#ossm-creating-istio-cni-project_ossm-installing-openshift-service-mesh

Enable side car injection on namespaces
https://docs.redhat.com/en/documentation/red_hat_openshift_service_mesh/3.1/html/installing/ossm-sidecar-injection#ossm-enabling-sidecar-injection-namespace-labels_ossm-sidecar-injection

https://docs.redhat.com/en/documentation/red_hat_openshift_service_mesh/3.1/html/installing/ossm-multi-cluster-topologies#ossm-installing-kiali-multi-cluster-mesh_ossm-multi-cluster-topologies
CR is in yaml


Install cert-manager Operator for Red Hat OpenShift 
Install Tempo Operator and create tempostack


Install Red Hat build of OpenTelemetry operator
Red Hat build of OpenTelemetry is a collection of tools, APIs, and SDKs. You use it to instrument, generate, collect, and export telemetry data (metrics, logs, and traces) for analysis in order to understand your software's performance and behavior. This operator was previously called Red Hat OpenShift distributed tracing data collection.
Operator features
Sidecar injection - annotate your pods and let the operator inject a sidecar.
Managed upgrades - updating the operator will automatically update your OpenTelemetry collectors.
Deployment modes - your collector can be deployed as sidecar, daemon set, or regular deployment.
Service port management - the operator detects which ports need to be exposed based on the provided configuration.

