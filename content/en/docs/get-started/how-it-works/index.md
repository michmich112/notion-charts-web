---
title: "How It Works"
description: "Find out how the Notion Charts integration functions"
lead: "Find out how the Notion Charts integration functions"
date: 2022-12-16T11:57:13-08:00
lastmod: 2022-12-16T11:57:13-08:00
draft: false
images: []
menu:
  docs:
    parent: "get-started"
    identifier: "how-it-works-8f43c96d9b7449445c5cd3cf8d38b842"
weight: 802
toc: false
---

## Embeding a chart
When you embed a chart the following will happen:

1. We validate your token
2. We query the notion API for your data query block, and your database data. 
3. We run your data query with a PostgreSQL interpreter on the database data.
4. We return all the chart configuration and data needed to display your chart.

{{< figure src="How-it-works.drawio.png" alt="High level diagram" caption="<em>High level overview of how Notion Charts Works.</em>" class="mx-auto w-75" >}}

