---
page_title: "unifi_ap_group Data Source - terraform-provider-unifi"
subcategory: ""
description: |-
  unifi_ap_group data source can be used to retrieve the ID for an AP group by name.
---

# Data Source `unifi_ap_group`

`unifi_ap_group` data source can be used to retrieve the ID for an AP group by name.

## Example Usage

```terraform
data "unifi_ap_group" "default" {
}
```

## Schema

### Optional

- **name** (String) The name of the AP group to look up, leave blank to look up the default AP group.
- **site** (String) The name of the site the AP group is associated with.

### Read-only

- **id** (String) The ID of this AP group.


