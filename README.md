# Open Rat Box
This repository contains part files and instructions for high-throughput behavior rig towers (current and previous designs).

## Components 
- cage: cage info (mounting point dimensions, etc...)
- camera: webcam info
- displays: small computer monitor & optional usb touchscreen display
- frame: 80/20 extrusion bars 
- acrylic panels: structural (walls, ceiling, floor), and useful mounts  
- plumbing: 1/4" ID tubing for connecting water pump to the lick ports (feeding needles attached with luer locks)
- pumps: syringe pumps that can be programmed to deliver set amounts of fluid based on speed, tubing diameter, etc.
- sensors: IR reflector to detect presence/absence of the head poking out of the cage, touch sensors wired to feeding needles (lick ports) to detect lick or no lick

## Instructions
`instructions`: Start here!

`instructions/behav_rg_special_notes.md`: Contains construction notes and additional tips.
`instructions/behav_rig_specs_final.xls`: Optional spreadsheet to sort out what size bulk acrylic to buy based on dimensions of custom cut acrylic pieces (disclaimer: might not be fully accurate).

## Design files
`add_ons`: Additional acrylic pieces for the tower.
- `add_ons/cage_hole`: Creates an acrylic hole for the rat's head during training. The `inner_plate` attaches inside the cage and the `outer_plate` mates to it on the outside. Both plates are not necessary if just gluing the plates directly to the cage. Start by drilling or cutting a large hole in the cage, then place the acrylic plate with the (more nicely) laser-cut hold on top to create a smoother opening for the head.
- `add_ons/extrusion_support`: Add these to provide support at the junction connecting two extrusion bars. Use the through holes and M6-slot bolts placed on either side of the connection between the bars.
- `add_ons/power_squid_mount`: Convenient mount to hold up a powerstrip for a given training box. We used a power squid rather than a strip.
- `add_ons/spacers`: For use with repurposed metal frames that hold cages in portable colony racks. These are useful to make the metal rack fit snuggly between the top and bottom panels of the main vestibule.

`displays/usb`: Option mounting piece for attaching a little touchscreen display to control each computer.

`foamboard`: Additional pieces to block out light around the separate front area where the monitor is, in front of the rat and main vestibule (can ignore the foamboard folder in `front_area`)
-- `foamboard/rack_top`: captured piece for the top and bottom of the front vestibule that contains the monitor
-- `foamboard/front_slim`: Fills the gap above the main vestibule (the "L" shape of the box creates blank space above)
-- `foamboard/side_captured`: If not using an acrylic side panel (see `main_vestibule/sides`), can just use a foamboard to close the area on the side.

`front_area`: This is the part of the training box that does not contain the rat cage, but just the monitor, separate from the main vestibule.
-- `front_area/monitor_mount`: acrylic panel with through holes for mounting a monitor to the extrusion bar
-- `front_area/side_frame`:  Can be used with `side_door` or `side_slotted`. This panel creates a frame whose outer edges are fit into the extrusion rails. It has holes to then attach a door, either via thumbscrew (`side_door`) or fully screwing in at all four courners (`side_slotted`)
-- `front_area/side_door`: If using `side_frame`, this is a simple rectangular piece that can be detached/attached with a thumbscrew. Useful for closing off the side, but can be removed (if using oe of the frame pieces) to access wires and such on the monitor-side of the vestibule.
-- `front_area/side_slotted`: Screws into `side_frame` with 4 screws, and has a small slotted opening for wires to come through

`main_vestibule`: Where the rat cage is
-- `base`: bottom or floor of the vestibule
-- `door`: door that attached with hinges and has a handle to make it easy to open/close the box
-- `lid`: top of vestibule
-- `sides`: sides of vestibule (they should be oriented the same way)
-- `front_clear`: `frame` fits into the extrusion rails, and is meant to make the `attachment` window pane removable. The `attachment` panel screws into the `frame` in 4 corners, and also contains slotted holes to allow wiring from the lick ports to come through, out of the front vestibule.

`sensors`: Mounts to hold various sensors
-- `head`: If using an IR reflector sensor to detect head presence/absence, holds that phidget sensor in place. Not really critical, as the small PCB can be directly screwed onto the MicroRax frame that sits between the `main_vestibule/front_clear` panel and the rat's cage hole.
-- `lick`: 1 or 3 lick ports (clear). Holds the feeding needles that deliver reward, which are also metal (conductive). A small hole should be tapped at the top (M2.5) to hold the lick spout in place, like a set screw. A flat washer can be placed under the screwhead with a wire soldered on in order to create a connection between the lick port and the little touch sensor board outside of the vestibule.
-- `phidget_mounts`: A mount to hold the USB-phidget which connects all the different sensor boards (IR reflector, touch sensors for the lick port detection, etc.)

`tower_frame`: All specifications for the custom-cut extrusion bars, and additional notes.

`x_everything`: When in doubt, all the pieces (might not contain everything though). Always use the most recent version.



