---
layout: default
title: Working with Lookup Tables
nav_order: 7
has_children: false
parent: Guides
---

<!--© 2024 Laserfiche.
See LICENSE-DOCUMENTATION and LICENSE-CODE in the project root for license information.-->

# Working with Lookup Tables

The Lookup Table OData API allows users to interact with data stored in their Lookup Tables. If follows the [OData version 4 standard](https://docs.oasis-open.org/odata/odata/v4.01/odata-v4.01-part1-protocol.html) which allows you to use that standard to access and perform CRUD on your Laserfiche Lookup Tables from any application. Major use cases include reporting in Power BI or Excel. For more information on how to use an OData API [see the OData documentation](https://www.odata.org/getting-started/basic-tutorial/).

## Authenticate and use the API

Follow the instructions in the [authentication](./../../api/authentication/guide_authenticate-to-the-laserfiche-api) guides to authenticate and start using the API. The Table API supports both **Bearer** authentication, with an OAuth Access Token, and **Basic** authentication, with a username and password generated from the Developer Console.
