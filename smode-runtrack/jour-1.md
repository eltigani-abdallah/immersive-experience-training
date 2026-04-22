
# SMODE

## installation

install smode community (latest version) from smode.io


## directory 
create the following directories in the **external** disk (D:)

	`repository-motionlab-yourname`
		audio
		export
		media
		project
		stuff
		compo

## creating a new composition

In smode go to browse files from the left hand menu, then select the folder icon in the top of the center menu and add the repository created earlier

once done, go to `file>new standalone compo` from the nav bar at the very top of the window 

frame rate = 60 (depends on physical installation)

rest stays default



## interface

left: file and folder browser
	you may right click files and folders and click "reveal in file explorer" in order to view the files in windows file explorer
	you can rename files and folders in the file browser by right clicking and selecting `rename`

center top: project workspace

center bottom: timeline

right up: object list

right down: parameters of objects and files selected

### modifying the workspace

the interface is module based, it can be customized by clicking right at the top on the default workspace and creating a new workspace by duplicating it, then customizing the new workspace by clicking the workspace button at the very top right of the view port.


## preferences

in the nav bar `edit> preferences` you can edit the video input and outputs

in `edit>preferences>Media > Auto Save` you may turn on or off the auto save feature, change the frequency of auto save and change the maximum number of versions to auto save

## on air mode

when turning on on air mode (top right of the smode window) the  project becomes unavailable in the project workspace in the center in order to optimize resources to start showing the composition

in `edit>preferences>media>previews computing` changing it to off will allow for adding and removing files even during on air mode


## folder configuration

in `edit>preferences>about>reveal configuration in explorer` you may save and restore settings specific to smode in order to move the smode configuration to another machine (for example moving settings to motion lab from container 11)

**THE SMODE VERSION MUST BE THE SAME ON BOTH DEVICES** 

## creating a device

to output a composition you need to add an output device in `edit>preferences>engine>video outputs`

in the standard video output you may choose a different video output from the list: NDI, spout, and standard

you may also rename outputs by double clicking the current name of the output.

once all is chosen press `apply changes` and exit back to the smode menu

## checking devices used

in the file browser workspace, you can click the "devices" tab you may check the outputs and storage devices available to monitor their status

### launching a composition

you may output a composition by using the output button (top right of the screen) or by using the keyboard shortcut `ctrl+alt+shift+W`. to change output settings you may change the parameters in the `devices>VIDEO OUT` as seen previously.


## adding content

in the object hierarchy window you may create a test pattern by right clicking and going to `2D Layers> Test Pattern`.

### adding a new composition

this same method will be used to create two new compositions in the same window `right click>create compo` and name it VP-JAR

when creating a new composition inside an existing composition it inherits the previously existing resolution of its parent

in the new composition in the inspector>renderer you have  2 important settings "anchor" and "position"

the anchor is in the middle by default; and it can be changed from %  to X and Y coordinates in pixels by clicking on the units button on the very top and changing it from percentage to pixels

the target is to change the anchor to 0,0 px and move the position of the compo to 0,0, then halve the size of the composition to have it fill half the the workspace.

then we will duplicate the composition by selecting it in the menu and using `ctrl+D` then we will rename the the new composition to VP-COUR

the next job will be to move VP-COUR to the middle of the screen to make it show side by side with VP-JAR, to do that you need to go to the position setting of VP-COUR and move the X position to the middle of the view, this is done by simply typing `resolution/2` where resolution is the resolution of the main composition AKA the projection area,  so if we work with a resolution of 1920 x 1080 then the x position of VP-COUR will be `1920/2` which will evaluate to 960

you may export a composition created as above (so VP-COUR or VP-JAR) by dragging it with the mouse to the file explorer within smode itself

