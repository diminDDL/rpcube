# rpcube

Welcome to `rpcube`, the ultimate compact solution for integrating the RP2040 into your designs seamlessly. This project presents an all-in-one small BGA package that brings the powerful RP2040 to your fingertips. 

![rpcube Top View](https://github.com/diminDDL/rpcube/blob/main/images/render.png)

## Features

- **Compact Size**: With a tiny footprint of just 16.5x16.5mm, `rpcube` is designed to fit into the smallest of spaces while providing the full capabilities of the RP2040.

  ![rpcube Bottom View](https://github.com/diminDDL/rpcube/blob/main/images/kicad_FCu.png)

- **Integrated Components**: The package includes EEPROM, all necessary bypass capacitors, and an LDO to allow for direct 5V input, stepping it down internally.
- **Full GPIO Access**: All GPIOs as well as the SWD lines of the RP2040 are exposed and accessible, ensuring you can leverage the full power of the microcontroller for your projects.
- **Versatile Assembly Options**: Whether you prefer to use solder paste and stencils or go for manual soldering with an iron, `rpcube` accommodates various assembly methods to suit your workflow:
  - **Top Side Assembly**: Begin by assembling the top side using solder paste and hot air or a reflow oven.
  - **Bottom Balls Creation**: Create the bottom balls using a soldering iron with flux and a substantial amount of solder, or stack several stencils to dispense ample solder paste, then blast it with hot air for balls to form.
  - **Target PCB Solder Paste Method**: You can use the same stencil as for the bottom side on the target board, or if you already have the balls done, use just a bit of flux and reflow, the balls will attach themselves.
  - **Target PCB Via in Pad Integration**: You can also use untented vias in your target PCB. Incorporate untented vias in the places of the balls and solder them one by one with an iron.
  - **Wire Attachment for Prototyping**: Alternatively, attach wires directly to `rpcube` for quick and easy point-to-point prototyping.
