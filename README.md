## Workflows & Dashboard Setup in Dynatrace

We provide a Dynatrace **workflow** and **dashboard** to help visualize and investigate feature flag data.

- **Workflow**: Automatically creates a feature flag update event for services sending spans (no need to manually map services to flags).
- **Dashboard**: Displays flag state changes over time, including response rates, throughput, and error rates in regards to a specific feature flag for a service.

You will have to import the Workflow and Dashboard into your Dynatrace instance through the following steps.

### Import Workflow

1. Download the workflow JSON: [Workflows Feature Flag.json](https://github.com/DevCycleHQ-Labs/dynatrace-integration/blob/main/Workflows%20Feature%20Flag.json)
2. In Dynatrace, go to **Workflows** → **Upload**, and import the file.

### Import Dashboard

1. Download the dashboard JSON: [Feature Flag Observability.json](https://github.com/DevCycleHQ-Labs/dynatrace-integration/blob/main/Feature%20Flag%20Observability.json)
2. In Dynatrace, go to **Dashboards** → **Upload**, and import the file.
