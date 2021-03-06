---
title: Upgrading from Previous Versions

menu:
  chronograf_1_0:
    name: Upgrading from Previous Versions
    weight: 10
    parent: Administration
---

Users looking to upgrade from versions prior to 0.10 to version 1.0 need to
take a few additional steps.

### For users who wish to maintain their dashboards and visualizations

1. [Install](https://influxdata.com/downloads/) Chronograf 0.10 to upgrade the `chronograf.db` directory
2. [Install](https://influxdata.com/downloads/) Chronograf 1.0

### For users with no attachment to their dashboards and visualizations

1. Remove the `chronograf.db` directory
2. [Install](https://influxdata.com/downloads/) Chronograf 1.0

> **Note:** Chronograf 0.11 made several changes to take into account the [breaking API changes](https://github.com/influxdata/influxdb/blob/master/CHANGELOG.md) released with InfluxDB 0.11.
As a result, we do not recommend using Chronograf 1.0 with InfluxDB versions prior to 0.11.
In general, we recommend maintaining version parity across the TICK stack.
