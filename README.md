# Creality K1 XY Rails Mod

## Description

This mod fixes K1 quality issues, namely excessive ringing/echo, makes printer quiet.

**You must use camera mount from this mod, it is 8mm lower than original.**

**This mod does not change print area.**

This mod uses two MGN12 rails with MGN12H carriages for Y and one MGN9 rail with MGN9H carriage for X axis.

It uses POWGE 7.7 mm belt and corresponding idler pulleys
but you can use 6 mm belt with stock idlers if you add washers to compensate size differences (POWGE idlers have 10.4 mm height), also you can
use F604ZZ flanged bearings.

**You must replace motor pulleys, 7.7mm belt does not fit stock pulleys.**

I replaced stock motor pulleys with 20T pulleys for 15mm belt (`rotation_distance` needs to be adjusted to `40` and `driver_SGTHRS` must be tuned `printer.cfg`). You will need a bearing puller to do that (some people use printed pullers e.g. https://www.printables.com/model/515503-pulley-puller), you have to be careful to avoid damage to motor shafts. If pulleys sit too tight you can use dremel and make cuts to relax pulleys.

You can install non-stock motors e.g. Leadshine 42cm06 1.8 or LDO-42STH48-1684MAC 0.9 (requires `full_steps_per_rotation: 400`). There are separate motor mounts.

X rail has max length of 331 mm, 320 mm between far left and far right holes.

Y rails have max length of 314 mm (safe 310 mm), 300 mm between far left and far right holes.

Recommended printing materials are PA-GF, PA-CF, ABS-GF, ABS-CF or anything else that is rigid and can sustain high temperatures.

## License

All work in this repository falls under the Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).

https://creativecommons.org/licenses/by-nc-sa/4.0/

### Notes

Partially this work is based on [creality-k1-max-xy-rails-mod](https://github.com/kemsky/creality-k1-max-xy-rails-mod) and uses some CAD files made by [Henlor](https://www.printables.com/@Henlor).


### BOM, Assembly, etc.

This is work in progress.
