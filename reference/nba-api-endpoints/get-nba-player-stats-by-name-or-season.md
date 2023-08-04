---
description: Great way to explore data about your favorite players!
cover: >-
  https://images.unsplash.com/photo-1608245449230-4ac19066d2d0?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw1fHxiYXNrZXRiYWxsfGVufDB8fHx8MTY5MTE2ODQxOXww&ixlib=rb-4.0.3&q=85
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: false
  pagination:
    visible: true
---

# 📊 Get NBA Player Stats by Name or Season

## Get all NBA Players by Season.

{% swagger src="../../.gitbook/assets/open.yaml" path="/api/playerdata/season/2023" method="get" expanded="true" fullWidth="false" %}
[open.yaml](../../.gitbook/assets/open.yaml)
{% endswagger %}

### Obtain Individual Player Stats by Name

{% swagger src="../../.gitbook/assets/open.yaml" path="/api/playerdata/name/{player_name}" method="get" expanded="true" fullWidth="false" %}
[open.yaml](../../.gitbook/assets/open.yaml)
{% endswagger %}

##
