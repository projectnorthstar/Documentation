---
description: Pulled from https://leapmotion.github.io/ProjectNorthStar/3dprints.html
---

# Initial Release 3D Printing Reference

{% hint style="success" %}
Note, this refence is for the initial Version 1 Release, however it has useful information for 3D printing in general and is still worth reading.
{% endhint %}

{% hint style="info" %}
Use your slicer's part orientation tools to ensure flat contact with print surface. In Simplify 3D, it can be found in the menu "Edit > Place Surface On Bed"
{% endhint %}

## **Optics Bracket**

The optics bracket is the most difficult part to FDM print. The toed-in optics and long thin beams require a tuned printer and large print bed (200x250mm). To reduce the chance for print failure, support material is manually removed where it is thin and tall (see image below). Furthermore, to alleviate the finishing work, the print is separated into 2 print profiles: fast and high-res. The high-res profile's goal is to reduce stepping on the near-horizontal crossbeam. Afterwards, a file and 220-grit sandpaper very quickly make the surface passable without the need for filler. Although printing the entire bracket with one profile also produces good brackets, this hybrid solution saved time and produced better results without much effort. Makes sense if a file and sand paper is already available.

All the optical components are mounted to this bracket. Take your time, be meticulous. It's crucial that care is taken in producing a good print. This will save time during calibration.

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_opticsBracket.png)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_OpticsSupports.png)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_6551.jpg)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_9233.jpg)

{% embed url="https://leapmotion.github.io/ProjectNorthStar/imgs/timelapses/opticsBrackWHITEBigTabs_20180425052347.mp4" %}

| Print from: 0 - 5mm: |                 |
| -------------------- | --------------- |
| layer height         | 0.25mm          |
| infill               | 20% rectilinear |
| top/bottom layers    | 3               |
| perimeter walls      | 2               |
| temperature          | 200 C           |
| supports             | yes, 60% infill |

| Print from: 5 - 32mm: |                 |
| --------------------- | --------------- |
| layer height          | 0.15mm          |
| infill                | 20% rectilinear |
| top/bottom layers     | 6               |
| perimeter walls       | 3               |
| temperature           | 200 C           |
| supports              | yes, 40% infill |

| Print from: 32mm - end: |                 |
| ----------------------- | --------------- |
| layer height            | 0.25mm          |
| infill                  | 20% rectilinear |
| top/bottom layers       | 3               |
| perimeter walls         | 2               |
| temperature             | 200 C           |
| supports                | yes, 60%        |

## **Halo**

Choose the correct halo for the Leap Motion module you're using. There are currently two variants: one for the released Leap Motion Controller and one for our custom ultra-wide FOV module not yet available.

![](https://leapmotion.github.io/ProjectNorthStar/imgs/alternateHalo.jpg)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_halo.png)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_6514.JPG)

{% embed url="https://leapmotion.github.io/ProjectNorthStar/imgs/timelapses/HaloOptimized_20180426171820.mp4" %}

| layer height      | 0.25mm          |
| ----------------- | --------------- |
| infill            | 20% rectilinear |
| top/bottom layers | 3               |
| perimeter walls   | 3               |
| temperature       | 200 C           |
| supports          | yes             |

## **Lid**

Choose the matching lid for the halo you're using. There are currently two variants: one for the released Leap Motion Controller and one for our custom ultra-wide FOV module not yet available.

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_haloLid.png)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_8902.JPG)

{% embed url="https://leapmotion.github.io/ProjectNorthStar/imgs/timelapses/LatestLid_20180423202548.mp4" %}

![](https://leapmotion.github.io/ProjectNorthStar/imgs/lidAlternative.jpg)

| layer height      | 0.25mm          |
| ----------------- | --------------- |
| infill            | 20% rectilinear |
| top/bottom layers | 3               |
| perimeter walls   | 2               |
| temperature       | 200 C           |
| supports          | yes             |

## **Electronics Tray**

Only needed for the custom hand tracking module. If you're using the Leap Motion Controller inside a metal housing, you don't need this part.

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_electronicsTray.png)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_5822.JPG)

{% embed url="https://leapmotion.github.io/ProjectNorthStar/imgs/timelapses/ARElectronicsTray_20180425012536.mp4" %}

| layer height      | 0.25mm          |
| ----------------- | --------------- |
| infill            | 20% rectilinear |
| top/bottom layers | 3               |
| perimeter walls   | 2               |
| temperature       | 200 C           |
| supports          | no              |

## **USB Strain relief**

Only needed for the custom hand tracking module. If you're using the Leap Motion Controller inside a metal housing, you don't need this part.

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_strainRelief.png)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_9208.JPG)

{% embed url="https://leapmotion.github.io/ProjectNorthStar/imgs/timelapses/USBStrainRelief-CamSafe_20180425010142.mp4" %}

| layer height      | 0.25mm          |
| ----------------- | --------------- |
| infill            | 20% rectilinear |
| top/bottom layers | 3               |
| perimeter walls   | 2               |
| temperature       | 200 C           |
| supports          | no              |

## **Display Tray**

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_displayTray.png)

{% embed url="https://leapmotion.github.io/ProjectNorthStar/imgs/timelapses/DisplayTrayLatestLowTempOptimizedMirrored_20180425183308.mp4" %}

The print is done using multiple print profiles to minimize the need for support material. By printing the feature at a lower temperature the plastic can span longer distances without support. Also, align the print roughly as shown (\~45 degrees) to prevent the support material from printing orthogonal to lip, which makes it harder to remove in post.

After printing, remove and clean up any support material so that the display slides in easily. We used a sharp chisel to scrap away any remaining plastic burs.

Check the lip of the part is flat and consistent throughout to prevent any extra light leaking from the edges of the LCD panels.

Optional step is tapping the screw holes to make sure any extra plastic is removed and the screws will fasten smoothly.

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_2692.JPG)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_5909.JPG)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_1365.JPG)

| Print from: 0 - 3mm: |                 |
| -------------------- | --------------- |
| layer height         | 0.25mm          |
| infill               | 20% rectilinear |
| top/bottom layers    | 3               |
| perimeter walls      | 2               |
| temperature          | 200 C           |
| supports             | yes             |

| Print from: 3mm - end: |                 |
| ---------------------- | --------------- |
| layer height           | 0.25mm          |
| infill                 | 20% rectilinear |
| top/bottom layers      | 3               |
| perimeter walls        | 2               |
| temperature            | 190 C           |
| supports               | yes             |

## **Hinges (left and right pairs)**

There are two styles of hinges to choose from depending on the headgear you're using.

### **Hinges for Miller branded headgear**

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_hingeA.png)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_hingeB.png)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_1130.JPG)

{% embed url="https://leapmotion.github.io/ProjectNorthStar/imgs/timelapses/hingesPair_20180425213458.mp4" %}

{% embed url="https://leapmotion.github.io/ProjectNorthStar/imgs/timelapses/hingesPairTracks_20180425230035.mp4" %}

### **Hinges for 3M Speedglas branded headgear**

![](https://leapmotion.github.io/ProjectNorthStar/imgs/alternateHingeParts.jpg)

| layer height      | 0.25mm          |
| ----------------- | --------------- |
| infill            | 20% rectilinear |
| top/bottom layers | 3               |
| perimeter walls   | 2               |
| temperature       | 200 C           |
| supports          | yes             |

### **Slide endcaps**

![](https://leapmotion.github.io/ProjectNorthStar/imgs/bedPlacement\_endCaps.png)

![](https://leapmotion.github.io/ProjectNorthStar/imgs/IMG\_5852.JPG)

{% embed url="https://leapmotion.github.io/ProjectNorthStar/imgs/timelapses/endCaps_20180425203542%202.mp4" %}

| layer height      | 0.25mm          |
| ----------------- | --------------- |
| infill            | 20% rectilinear |
| top/bottom layers | 3               |
| perimeter walls   | 2               |
| temperature       | 200 C           |
| supports          | yes             |

## [Back to Build Guide](initial-release-assembly-guide.md)
