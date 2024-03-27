.ymap file adds interior to Valentine Greenhouse.

.xml file places 2 desks and 1 set of bunk beds on the first floor, and 4 sets of bunk beds on the second floor of the Green House in Valentine.

Requirements
[objectloader](https://github.com/kibook/redm-objectloader)

Install

Create a folder named greenhouse in your resources folder.

Copy the .ymap and .fxmanifest files in this repository to that folder.

Create a folder named greenhousefurniture in your resources folder that stores your .xml maps. -- [mapster]
Create a copy of the fxmanifest and replace the files { with: 

dependency 'objectloader'

files {
	'greenhousefurniture.xml'
}

objectloader_maps {
	'greenhousefurniture.xml'
}

Copy the .xml and NEW fxmanifest to that folder.

Add ensure greenhouse to resources.cfg.
Add ensure [mapster] to resources.cfg.
