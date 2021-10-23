# Last-changed-element
Display when entity was last changed in home assistant picture element.

![Example](last-changed-element.png)

### Instalation
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
