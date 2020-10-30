# aframe-datguivr-example

*A-Frame component for [datGUIVR](https://github.com/dataarts/dat.guiVR)*

- This is a proof of concept & is not developed any more
- I created an example that works with A-Frame 1.4.0 (kind of).
- the example shows how you can link DAT-GUI to your A-Frame scene

## Note

- "stateless" controllers only, meaning you can't attach controllers directly to JS objects
- you CAN listen to controller changes and update anything accordingly, though.

## Limitations & Bugs

- only sliders, checkboxes and buttons
- labels are not displayed for Aframe > 0.9.0
- dat.guiVR is basically dead 🙁