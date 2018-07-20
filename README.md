# Welcome, Knative

Knative (pronounced kay-nay-tiv) extends Kubernetes to provide a set of middleware 
components that are essential to build modern, source-centric, and container-based 
applications that can run anywhere: on premises, in the cloud, or even in a third-party 
data center. 

Each of the components under the Knative project attempt to identify common patterns and 
codify the best practices that are shared by successful real-world Kubernetes-based frameworks and 
applications. Knative components focus on solving many mundane but difficult tasks such as:

* [Deploying a container](./install/getting-started-knative-app.md)
* [Orchestrating source-to-URL workflows on Kubernetes](./serving/samples/source-to-url-go/)
* [Routing and managing traffic with blue/green deployment](./serving/samples/blue-green-deployment.md)
* [Automatic scaling and sizing workloads based on demand](./serving/samples/autoscale-go)
* [Binding running services to eventing ecosystems](./eventing/samples/event-flow/README.md)

Developers on Knative can use familiar idioms, languages, and frameworks to deploy any workload: 
functions, applications, or containers.

## Components

The following Knative components are currently available:

* [Build](https://github.com/knative/build) - Source-to-container build orchestration
* [Eventing](https://github.com/knative/eventing) - Management and delivery of events
* [Serving](https://github.com/knative/serving) - Request-driven compute that can scale to zero

## Audience

Knative is designed with different personas in mind:

![Diagram that displays different Audiences for Knative](./images/knative-audience.png)

### Developers

Knative components offer developers Kubernetes-native APIs for deploying
serverless-style functions, applications, and containers to an auto-scaling
runtime.

To join the conversation, head over to the
[Knative users](https://groups.google.com/d/forum/knative-users) Google group.

### Operators

Knative components are intended to be integrated into more polished
products that cloud service providers or in-house teams in large
enterprises can then operate.

Any enterprise or cloud provider can adopt Knative components into
their own systems and pass the benefits along to their customers.

### Contributors

With a clear project scope, lightweight governance model, and clean
lines of separation between pluggable components, the Knative project
establishes an efficient contributor workflow.

Knative is a diverse, open, and inclusive community. To get involved, see
[CONTRIBUTING.md](./community/CONTRIBUTING.md)
and join the [Knative community](./community/README.md).

Your own path to becoming a Knative contributor can
[begin anywhere](https://github.com/knative/serving/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22).
[Bug reports](https://github.com/knative/serving/issues/new) and
friction logs from new developers are especially welcome.

## Documentation

Follow the links in this section to learn more about Knative.

### Getting started

* [Installing Knative](./install/README.md)
* [Getting started with app deployment](./install/getting-started-knative-app.md)
* [Samples](./serving/samples/)
* [Getting started with serving](./serving)
* [Getting started with builds](./build)
* [Getting started with eventing](./eventing)

### More samples and demos

* [Autoscaling](./serving/samples/autoscale-go/README.md)
* [Source-to-URL deployment](./serving/samples/source-to-url-go/README.md)
* [Binding running services to eventing ecosystems](./eventing/samples/event-flow/README.md)
* [Telemetry](./serving/samples/telemetry-go/README.md)
* [REST API sample](./serving/samples/rest-api-go/README.md)

### Setting up logging and metrics 

* [Installing logging, metrics and traces](./serving/installing-logging-metrics-traces.md)
* [Accessing logs](./serving/accessing-logs.md)
* [Accessing metrics](./serving/accessing-metrics.md)
* [Accessing traces](./serving/accessing-traces.md)
* [Setting up a logging plugin](./serving/setting-up-a-logging-plugin.md)

### Debugging Knative serving issues 

* [Debugging application issues](./serving/debugging-application-issues.md)
* [Debugging performance issues](./serving/debugging-performance-issues.md)

### Configuration and networking

* [Configuring outbound network access](./serving/outbound-network-access.md)
* [Using a custom domain](./serving/using-a-custom-domain.md)
* [Assigning a static IP address for Knative on Google Kubernetes Engine](./serving/gke-assigning-static-ip-address.md)
