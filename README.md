# Blueprints for Home Assistant
This repository fork from `[gmlupatelli/blueprints_repo](https://github.com/gmlupatelli/blueprints_repo)`

***User the Blueprint by your own risk***

## Install

1. You can import blueprints: Setting > Automations & scenes > Blueprints > Import Blueprint 
   1. URL: `https://raw.githubusercontent.com/J1A-T13N/blueprints_repo/master/low_battery_notification/low_battery_notification.yaml`
   2. URL: `https://raw.githubusercontent.com/J1A-T13N/blueprints_repo/master/unavailable_entities_notification/unavailable_entities_notification.yaml`

## How to use

1. Go to Setting > Automations & scenes > Blueprints
2. Choose 「Low-battery notification」 or 「Unavailable Entities Notification」
   1. If the blueprint didn't show up in the list please REFRESH the page
   2. If the blueprint is still not in the list, you need to clear the browser cache.
2. Enter required field.
3. The 「Excluded Sensors」 field is optional.

## Notice

1. 「Low-battery notification」 Return format support list and string
   1. `{{ sensors_text }}` is string
   2. `{{ sensors }}` is list, field: entity_id、name、area_name、state
2. 「Unavailable Entities Notification」Return format support list and string
   1. `{{ entities_text }}` is string
   2. `{{ entities }}` is list, field: entity_id、name、area_name、state
