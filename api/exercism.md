---
layout: default
title: Exercism Widgets 
---

# Info

**NOTE:** Your account must be Public (Have at least 10rep) to use this API.

This api can be used to embed Exercism widget on sites and Github Profiles.

Base URL: https://api.janpalma.cz/exercism/

# Endpoints
## GET `/graph.png`

Shows your overall status on Exercism. Note that this endpoint is basicaly just nice version of their OG Image (https://exercism.org/profiles/mobilex1122.jpg).

### Parameters

|  Name  |   Type   | Description                          |
|--------|----------|--------------------------------------|
| ?u=    | String   | Exersism Username (Defaults to mine) |

### Response

![Exercism Graph](/assets/images/exercism-graph.png)

## GET `/tracks.png`

**DISCLAIMER:** This endpoint is WIP and doesn't support other users!

Shows track progress for user (Right now only me).

### Parameters

**NONE**

### Response

![Exercism Tracks](/assets/images/exercism-tracks.png)
