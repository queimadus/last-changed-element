# Last-changed-element
Display when the entity was last changed in home assistant picture element.

![Example](https://raw.githubusercontent.com/queimadus/last-changed-element/main/last-changed-element.png)

### Installation
Add this repo to `HACS` as a custom repository and install it. You're all set!

### Usage

Use it as a custom element inside a `picture-elements`.
```
elements:
   - type: state-icon
     entity: binary_sensor.my_occupancy
     style:
       left: 50%
       top: 45%
   - type: 'custom:last-changed-element'
     entity: binary_sensor.my_occupancy
     style:
       left: 50%
       top: 50%
image: /local/images/floorplan.svg
type: picture-elements
```
