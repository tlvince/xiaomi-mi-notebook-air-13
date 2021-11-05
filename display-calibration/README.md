# Display Calibration

[ICC profiles](https://wiki.archlinux.org/index.php/ICC_profiles) by [zluk310884](https://web.archive.org/web/20190921024145/http://en.miui.com/thread-418478-1-1.html), mirrored with permission.

* Calibrator: X-Rite i1Pro 2

Identify your display's model with [edid-decode](https://aur.archlinux.org/packages/edid-decode-git/):

```
edid-decode < /sys/class/drm/card0-eDP-1/edid
```

Known models:

* [Sharp LQ133M1JW15](sharp-lg133m1jw15) (SHP Model 1447)
* [Samsung 133HL09-M01](samsung-133hl09-m01)
* [BOE NV133FHM-N52](boe-nv133fhm-n52)
