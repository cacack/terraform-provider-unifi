---
page_title: "unifi_user_group Data Source - terraform-provider-unifi"
subcategory: ""
description: |-
  unifi_user_group data source can be used to retrieve the ID for a user group by name.
---

# Data Source `unifi_user_group`

`unifi_user_group` data source can be used to retrieve the ID for a user group by name.



## Schema

### Optional

- **name** (String) The name of the user group to look up. Defaults to `Default`.
- **site** (String) The name of the site the user group is associated with.

### Read-only

- **id** (String) The ID of this AP group.
- **qos_rate_max_down** (Number)
- **qos_rate_max_up** (Number)


