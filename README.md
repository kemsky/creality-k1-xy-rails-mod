# Creality `K1` XY Rails Mod

## Description

This mod fixes `K1` issues namely excessive ringing/echo, unstable print quality, frequent maintenance, also it makes printer quiet.

It should be compatible with regular `K1` (tested), `K1C` and `K1 SE` (not tested, likely heat sink needs to be replaced with heatsink from regular `K1`).

 - **This mod does not change print area**
 - **You must use camera mount from this mod (8mm lower than original)**
 - **You must remove stock motor pulleys (or use non-stock stepper motors)**

#### Belts, pulleys, motors

This mode uses `POWGE` 7.7 mm belt and corresponding idler pulleys. You can use 6 mm belt with stock idlers if you add washers to compensate height differences (`POWGE` idlers have 10.4 mm height), also you can use `F604ZZ` flanged bearings (not tested).

You have to remove stock motor pulleys. You can use a bearing puller to do that (some people use printed pullers e.g. [pulley puller](https://www.printables.com/model/515503-pulley-puller), you have to be careful to avoid damage to motor shafts. If pulleys sit too tight you can use dremel and make cuts to relax pulleys.

I used 20T motor pulleys for 15 mm belt (`rotation_distance` needs to be adjusted to `40` and `driver_SGTHRS` must be tuned `printer.cfg`).

You can install non-stock motors e.g. `Leadshine 42cm06 1.8` or `LDO-42STH48-1684MAC 0.9` (requires `full_steps_per_rotation: 400`, loud, limited acceleration but potentially better print quality).

#### Linear rails

This mod uses two `MGN12` rails with `MGN12H` carriages for Y and one `MGN9` rail with `MGN9H` carriage for X axis.

X rail has max length of 331 mm, 320 mm between far left and far right holes. X axis requires 15x15x2 mm aluminium tube (the same length as rail). It is important to use quality rails for X axis (with minimal backlash).

Y rails have max length of 314 mm (safe 310 mm), 300 mm between far left and far right holes. 

#### Materials

Recommended printing materials are PA-GF, PA-CF, ABS-GF, ABS-CF or anything else that is rigid and can sustain high temperatures. I don't recommend printing toolhead with pure ABS.

## License

All work in this repository falls under the Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).

https://creativecommons.org/licenses/by-nc-sa/4.0/

### Notes

Partially this work is based on [creality-k1-max-xy-rails-mod](https://github.com/kemsky/creality-k1-max-xy-rails-mod) and uses some CAD files made by [Henlor](https://www.printables.com/@Henlor).

## Photos

![1](/images/assembled/IMG_20241211_051136.jpg)

![2](/images/assembled/IMG_20241211_051154.jpg)

![3](/images/assembled/IMG_20241211_051206.jpg)

![4](/images/assembled/IMG_20241211_051212.jpg)

![5](/images/assembled/IMG_20241211_051230.jpg)


### BOM, Assembly, etc.

This is work in progress.
