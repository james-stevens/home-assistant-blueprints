# home-assistant-blueprints
My Home Assistant Blueprints

## motion_light_dim_sensor.yaml
This is a copy of the standard HA `motion_light.yaml` but adding light/dark detection,
so the lights only come on if the sensor thinks it's dark.

I have SNZB-03P motion & light sensors from eWeLink (Sonoff). They expose the `illumination` as a `sensor` 
which has the value `bright` or `dim`.

If your light detectors behave differently, you may need to make changes, but this blurprint
doesn't require the illumination & motion are done by a single sensor.
