# Modifications for our Setup

https://git.rwth-aachen.de/bcs/projects/dronelab/firmwares/crazyflie-firmware/-/commit/5cc7a7aecbdaeb5b6bd8dd504816b0883a448022

* Compile with `-DDISABLE_LIGHTHOUSE_DRIVER=0` by creating `tools/make/config.mk`
* Change estimation method to 0
* Insert our new base station calibration, see [inventory](https://git.rwth-aachen.de/bcs/projects/dronelab/general-info/-/wikis/Inventory#basestation-poses).


More to come?