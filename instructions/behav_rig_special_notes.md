# Building notes
- Do not build the entire tower out of the anodized extrusion bars first. Start with the base, then build each unit on top of the next. 
- Use the labeled tower diagram to make sure bars are not mixed up (components A, B, C, etc. in `tower_frame/rat_box_assembly.png`). Each component has its own specification, such as which ends are tapped, which are not, etc. 
- Read the whole document (especially "Idiosyncracies for construction"). 
- Laser-cut and prepare all custom modifications for a *single* unit (the bottom unit) first. Only once you are satisfied with the base unit, then can cut more pieces for each unit. 

## Custom components
- All laser-cut pieces
- MicroRax frame & attachment pieces (LED, camera, sensors) for all components near the head and lickport area inside the main vestibule
- wiring: LEDs (IR for camera, etc.), phidget sensors (IR reflective sensor for head-detection & to lick spouts)
- tubing: helpful to have an extra, long piece of tubing to attach to the lick ports when flushing the system for cleaning. Supergluing a small rubber black O-ring to the cross-section of tube will help create a snug fit onto the rounded lickport spout

## Modifications related to laser-cut parts

### Pieces that need tapped holes
- `lickHolder`: needs 2 tapped holes for M2.5 screws
- `frontPanelFrame` (clear):  needs 4 tapped holes for M3 screws (tap M3x0.50)
-side door frame (black, captured):  needs 1 tapped hole at the top if using thumb-screw for panel

### Pieces with added holes
- `monitorMount` ("big"): make spacing of 4 through holes match whatever mount the monitor needs\
- `touch_sensor_panel` (for `phidget_mounts`): drill little holes above each sensor board for zip-ties to hold soldered wires straight up (prevents bending)

### Bulk acrylic order adjustments
- Make sure large, bulk pieces fit the laserbed, for ex., cut in half (18.5" and 17.5", not 36") to fit
- `phidget_mount` and `touch_sensor_panel` (clear): cut with 1/8" acrylic (not 1/4")
- might need more black 1/4" for `side_door_frame` depending on size (capture inside extrusion rivets)
- `cage_head_thruHole` (for gluing to front of rat cage where head pokes out): use 1/8" rather than 1/4" acrylic for spacing

## Idiosyncracies for construction:
1. If using spring-loaded spacer pieces (which can also be used for optional air flow) should be installed *before* putting in the lid/bottom panels. These pieces go on the underside of the top frame of the vestibule, so it is easier to screw them on (springs, screws, etc.) when the panel is upside down than when installed.
2. If using repurposed metal brackets from the colony cage system, for a snug fit, helpful to add: one 1/4" acyrlic spacer set on bottom (use M5x20s), and two stacked 1/4" spacers attached to top/lid piece (use M5x25s).
3. All vertically-oriented extrusion pieces should be screwed in to its lower horizontal piece before stacking the next unit on top of rack. Otherwise, you cannot access the end-fastener at the bottom of the vertical piece once it is in place.
4. `main_vestibule/lid/Lid` and `base/Bottom`: These are the black acrylic panels that are fitted into the extrusion frames forming the top (lid) and floor (bottom) of the main vestibule holding the plastic rat cages. The etched text (in the laser cut pattern) should be facing up. And, "insert this side first" means that end goes toward the monitor first.
5. `main_vestibule/sides/sidePanel_final_rot`: Side panels for main vestibule should face the same direction, so the text should be facing leftward, if facing the monitor.
6. `main_vestibule/front_clear/frame` and `front_clear/attachment` pieces  are clear acrylic panels that should be screwed together before inserting (i.e., don't just put the frame in alone while building up the extrusion pieces around it without screwing on the attachment piece, too)

### Helpful ordering of main vestibule:  
(a) Get bottom extrusion frame (3 pieces, sides and front), but without the front piece connected yet, and slide in the acrylic bottom panel. The spacers & metal cage frame should be screwed in already (Note 2 above).
(b) Approximately align the top horizontal extrusion pieces (into which the lid panel will fit) with the horizontal extrusion piece that is  resting above the clear acrylic front panel/attachment
(c) Then, slide in the side panels.
(d) Separately, build up the door (bottom and side extrusion bars, but without the top bar connected). Connect this partial door to the extrusions making up the bottom of the vestibule. Make sure that the side acrylic panels are fitting into the vertical extrusion bars of the door as you screw the door into the end fasteners on the bottom frame's extrusion bars.
(e) With the top extrusion bar of the door still off, slide in top acrylic panel for the lid. Then, slide in the extrusion bar that will connect the edge closest to the door of the top panel and the top of the door.

### Some more notes:
- For securing the top/bottom acrylic panels, manuever the pieces so that for each panel, 3 edges (two sides and the edge closer to the monitor) are resting on the extrusions that make up the sides and front (closest to monitor) of the vestibule. Place the 4 panel pieces (sides, top, bottom) in the approximate places, and don't tighten until things are well in place. Make sure all panels are securely backed all the way in (toward the monitor), i.e., the acrylic panels should nestle fully into the rails of the extrusion bars.
- Make sure clear acrylic front panel attachment is screwed onto the front panel frame when inserting into extrusions during building (extrusions on top of the frame were sitting too low, so the front panel attachment did not fit.  had to shave off a little bit off the top of the attachment piece)\
- Add support extrusions to bottom carriage to provide extra support across the longer axis (rigs may bend forward otherwise). Use 2 M6 T-slot nuts, with acrylic piece, same length as 4 main carriage extrusion pieces.


