---
id: "aspose-3d-for-net-25-3-release-notes"
slug: "aspose-3d-for-net-25-3-release-notes"
linktitle: "Aspose.3D for .NET 25.3 Release Notes"
title: "Aspose.3D for .NET 25.3 Release Notes"
weight: 10
description: "Aspose.3D for .NET 25.3 Release Notes – the latest updates and fixes."
type: "repository"
layout: "release"
---

{{% alert color="primary" %}}

This page contains release notes information for Aspose.3D for .NET 25.3.

{{% /alert %}}
## **Improvements and Changes**
|**Key**|**Summary**|**Category**|
| :- | :- | :- |
| THREEDNET-1653 | Add support for virtual entity half space | Task |
| THREEDNET-1654 | Add support for BooleanObject | Task |
| THREEDNET-1655 | Add support for advanced B-Rep | Task |
| THREEDNET-1657 | Fix the critical issues detected by SonarQube | Task |
| THREEDAPP-2194 | GLTF to OBJ conversion issue | Bug fixing |
| THREEDNET-1660 | B-Spline curve tessellation failed | Bug fixing |
| THREEDNET-1661 | Mesh created from Advanced BRep cannot be used as Boolean operand | Bug fixing |
| THREEDNET-1662 | Mesh generated from Linear Extrusion is not manifold | Bug fixing |
| THREEDNET-1664 | Exported GLB file with animation cannot pass glTF validation | Bug fixing |

## API Changes ##

### Added class **Aspose.ThreeD.Entities.BooleanOperand**
### Added class **Aspose.ThreeD.Entities.BooleanOperator**
### Added class **Aspose.ThreeD.Entities.HalfSpace**

New classes used for creating enhanced Boolean operation as an entity.

### Added members to class **Aspose.ThreeD.Entities.NurbsCurve**:

{{< highlight csharp >}}
        int Degree{ get;set;}
{{< /highlight >}}

This allows you to get or set the degree instead of Order of the NurbsCurve.



### Added members to class **Aspose.ThreeD.Profiles.ArbitraryProfile**:

{{< highlight csharp >}}
        System.Collections.Generic.List<Aspose.ThreeD.Entities.Curve> Holes{ get;}
{{< /highlight >}}

The new property allows you to define holes by closed curves for ArbitraryProfile.
