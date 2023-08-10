---
title: Known Issues
weight: 1000
description: "List of known issues in the latest release of NGINX Amplify"
toc: true
tags: ["docs"]
---

{{<rn-styles>}}

---

### {{% icon-resolved %}} Adding new Slack integration not supported in Beta user interface. {#907}

{{<bootstrap-table "table table-striped table-bordered">}}
| Issue ID | Status |
|----------|--------|
| 907      | Resolved   |
{{</bootstrap-table>}}

#### Description

Adding a new Slack channel in the Notifications Settings page does not work in the Beta user interface.

#### Workaround

Add any new Slack channel integrations in the Classic user interface.

---

### {{% icon-bug %}} Custom Time Ranges are Not Supported in Beta user interface {#507}

{{<bootstrap-table "table table-striped table-bordered">}}
| Issue ID | Status |
|----------|--------|
| 507      | Open   |
{{</bootstrap-table>}}

#### Description

Graphs and custom dashboards only support selecting a time range from a predefined set and do not yet support selecting a custom time range.

---

### {{% icon-bug %}} Unable to Copy Existing Dashboard Widgets in Beta user interface {#859}

{{<bootstrap-table "table table-striped table-bordered">}}
| Issue ID | Status |
|----------|--------|
| 859      | Open   |
{{</bootstrap-table>}}

#### Description

Custom dashboards do not yet support copying individual dashboard widgets to another dashboard.

#### Workaround

Default graphs can be added to dashboards, and entire dashboards can be cloned. To replicate an existing widget, it needs to be recreated directly.

---

### {{% icon-bug %}} Unable to add some NGINX HTTP requests metrics to custom graph {#631}

{{<bootstrap-table "table table-striped table-bordered">}}
| Issue ID | Status |
|----------|--------|
| 631      | Open   |
{{</bootstrap-table>}}

#### Description

When trying to create a custom dashboard for the metrics nginx.http.request.reading and nginx.http.request.writing, the option to add them to the dashboard is disabled.

---