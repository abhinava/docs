---
title: Adaptive Routing
author: Cumulus Networks
weight: 120

type: nojsscroll
---
<style>
h { color: RGB(118,185,0)}
</style>
<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show interface \<interface-id\> router adaptive-routing</h>

Shows adaptive routing configuration settings on a specific interface.

### Command Syntax

| Syntax | Description |
| --------- | -------------- |
| `<interface-id>` | The interface name. |

### Version History

Introduced in Cumulus Linux 5.1.0

### Example

```
cumulus@switch:~$ nv show interface swp1 router adaptive-routing
                            applied
--------------------------  -------
enable                      on     
link-utilization-threshold  70  
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show router adaptive-routing</h>

Shows if adaptive routing is `on` or `off` on the switch.

{{%notice note%}}
Cumulus Linux 5.6 supports adaptive routing on Spectrum-4.
Cumulus Linux 5.5 and earlier supports adaptive routing on Spectrum-3 and Spectrum-2 as a beta feature for evaluation.
{{%/notice%}}

### Version History

Introduced in Cumulus Linux 5.1.0

### Example

```
cumulus@switch:~$ nv show router adaptive-routing
        applied
------  -------
enable  on
```
