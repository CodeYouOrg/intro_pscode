# client-b.md

## A simple warehouse store map app

### Create a tile map of the of the warehouse store.
- Interface will use the aisles, shelves, and storage bins to tile map the store.
- Aisles, shelves, and storage bins will be oriented north/south , or east/west.
- ID locations of the major material categories, such as 2X4s, plywood, electrical, etc., and the entrance to the store.
- Add tile mapping location descriptors for each of the material IDs.
- Aisles will be labeled. 

### Create a graphical user interface to show the way to get from the main entrance to any materials location, and to go from any material location to another material location.
- Interface will show the tile map of the store w/ the selected material locations labeled.
- Interface will allow the customer to  select a 'to' and 'from' material/main entrance location and then press a 'go' button.
- When the 'go' button is pressed a walking map will be generated showing the path to the selected material location using a dashed line going thru the needed aisleways.
- The main entrance location wil[ be defaulted in as the 'from' input.
- Dropdown lists will allow the selection of the locations.

### Other features
- There will be a 'clear locations' button for the to/from inputs.
- Consider a 'reset' button to clear inputs and stop any background processes so the customer can truly start over.

### Error(s) to be considered and corrected,
- Only one location input is selected. 
- After a selected amount of time and the 'gp' button has not been pressed.