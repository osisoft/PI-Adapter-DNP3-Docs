---
uid: DNP3Configuration
---

# Configuration

PI Adapter for DNP3 provides configuration of data source and data selection.

The examples in the configuration topics use `curl`, a commonly available tool on both Windows and Linux. You can configure the adapter with any programming language or tool that supports making REST calls or with the EdgeCmd utility. For more information, see the [EdgeCmd utility documentation (https://osisoft.github.io/Edgecmd-Docs/v1.1/edgecmd-utility.html)](https://osisoft.github.io/Edgecmd-Docs/v1.1/edgecmd-utility.html). To validate successful configurations, you can perform data retrieval (GET commands) with a browser, if available, on your device.

For more information on PI Adapter configuration tools, see [Configuration tools](xref:ConfigurationTools).

## Quick start

This Quick Start guides you through setup of each configuration file available for PI Adapter for DNP3. As you complete each step, perform each required configuration to establish a data flow from a data source to one or more endpoints. Some configurations are optional.

**Important:** If you want to complete the optional configurations, complete those tasks before the required tasks.

1. Configure one or several DNP3 system components.<br>See [System components configuration](xref:SystemComponentsConfiguration#configure-system-components).

2. Configure a DNP3 data source for each DNP3 device.<br>See [PI Adapter for DNP3 data source configuration](xref:PIAdapterForDNP3DataSourceConfiguration#configure-dnp3-data-source).

3. **Optional**: Configure schedules.<br>See [Schedules configuration](xref:SchedulesConfiguration#configure-schedules).

4. Configure a DNP3 data selection for each DNP3 data source.<br>See [PI Adapter for DNP3 data selection configuration](xref:PIAdapterForDNP3DataSelectionConfiguration#configure-dnp3-data-selection).

5. **Optional**: Configure data filters.<br>See [Data filters configuration](xref:DataFiltersConfiguration#configure-data-filters).

6. Configure one or several egress endpoints.<br>See [Egress endpoints configuration](xref:EgressEndpointsConfiguration).

7. **Optional**: Configure health endpoints, general (diagnostics and metadata), buffering, and logging. See the following topics:

    - [Health endpoint configuration](xref:HealthEndpointConfiguration#configure-health-endpoint)
    - [General configuration](xref:GeneralConfiguration#configure-general)
    - [Buffering configuration](xref:BufferingConfiguration#configure-buffering)
    - [Logging configuration](xref:LoggingConfiguration#configure-logging)
 