# Fermentation-Control-System

## ToDo: Next Release (0.85):
- Line 656 [CURR_TEMP = (int)CURR_TEMP_F;] --> 594
- Change   [if (temp_fridge > 0) { CURR_TEMP_F = temp_fridge; }] to
  if (


## Release 0.84:
- Check calculation of character positioning in line 938
- Implement delay to switch off the compressor (configurable in seconds)

## Release 0.83
- Solve bug in line 140

String ext_url = doc["EXTERNAL_URL"];     
EXTERNAL_URL = mqtt_broker.c_str()

## Release 0.82:
- Change of steering logic (line 592-618)
- Solve error in setting variable COOL_HEAT = 20
