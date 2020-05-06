# n8n-prodpad2youtrack
This is a little workflow for n8n / Nodemation (https://n8n.io/).

It copies an Idea from ProdPad (https://www.prodpad.com/) to your YouTrack (https://www.jetbrains.com/youtrack/) instance.

## Handling

The workflow has three nodes.

1. The first node (webhook) is quite straight forward. Nothing special here.
2. The second node does all the transformation. You might change some details here, like **customFields** amongst others.
3. The third node sends all the data to your YouTrack instance. Don't forget to **add authentication and your YouTrack URL** here.

## Changes

### 0.1.0
- Can handle a webhook request from ProdPad and create a representation of the idea in YouTrack


