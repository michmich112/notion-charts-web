---
title: "Adding the Integration"
description: "How to add the Notion Charts integration to your workspace"
lead: "How to add the Notion Charts integration to your workspace"
date: 2022-11-26T17:23:47-08:00
lastmod: 2022-11-29T18:40:57-08:00
draft: false
images: []
menu:
  docs:
    parent: "get-started"
    identifier: "adding-the-integration-1889cb3017099bca00a50e7afa28c114"
weight: 801
toc: true
---

## Authorize the extension with Notion

{{< alert icon="🚧" text="You will need to authorize the extension for exevery workspace you want to use." />}}

## Save the token

Once you've authorized the exention with Notion, you'll be presented with a token for the workspace.
Copy and keep this token safe as you will need to put it in each url you request to have embedded.

{{< alert icon="👉" text="The token should only be used with the workspace that authorized it." />}}

## Test the connection

1. Go to the Notion workspace you've just authorized and create a new `embed` block.
2. Enter the following url (making sure to replace `<your-token>` with the token you saved previously):

```url
  https://api.notion-charts.app/workspace?token=<your-token>
```

3. After a few seconds, the `embed` block should display information about your workspace
