---
c: Copyright (C) Daniel Stenberg, <daniel@haxx.se>, et al.
SPDX-License-Identifier: curl
Long: vlan-priority
Arg: <num>
Help: Configure VLAN priority
Added: 8.9.0
Category: connection
Protocols: All
Multi: single
See-also:
  - type-of-service
Example:
  - --vlan-priority 4 $URL
---

# `--vlan-priority`

Set VLAN priority as defined in IEEE 802.1Q. (Added in 8.9.0).

The valid range for \<num\> is 0 to 7.
