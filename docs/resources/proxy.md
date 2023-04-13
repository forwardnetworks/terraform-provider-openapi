---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "forwardnetworks_proxy Resource - forwardnetworks"
subcategory: ""
description: |-
  
---

# forwardnetworks_proxy (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `host` (String) The host of the proxy.
- `network_id` (String) The network ID used to manage the proxy.
- `port` (Number) The port of the proxy.
- `protocol` (String) The protocol used by the proxy.

### Optional

- `disable_cert_checking` (Boolean) Whether certificate checking is disabled for the proxy.
- `password` (String, Sensitive) The password for the proxy.
- `username` (String) The username for the proxy.

### Read-Only

- `id` (String) The ID of this resource.

