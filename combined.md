## Table of Contents

- [Office Power Tools Manual](#office-power-tools-manual)
  - [Multi Edit Attribute](#multi-edit-attribute)
  - [Multi Delete](#multi-delete)
  - [Tally by Polygon](#tally-by-polygon)
  - [Copy Nodes](#copy-nodes)
  - [Join All Poles](#join-all-poles)
  - [Show Un-Associated Photos](#show-un-associated-photos)
  - [Un-Associate Photos](#un-associate-photos)
  - [Insert Sections](#insert-sections)
  - [Address Data](#address-data)
  - [Fix Map Errors](#fix-map-errors)
  - [Clear Warnings](#clear-warnings)
  - [Star Height Photos](#star-height-photos)
  - [Fix Company Names](#fix-company-names)
  - [Draw Polygon](#draw-polygon)
  - [Bulk Pole Loading](#bulk-pole-loading)
  - [Offset Lines](#offset-lines)

- [Photos Overview and Classification Manual](#photos-overview-and-classification-manual)
  - [Katapult Pro Photos Layout](#katapult-pro-photos-layout)
  - [Photo Colors](#photo-colors)
  - [Classification](#classification)
  - [Calibration](#calibration)
  - [Photo Info and Editing](#photo-info-and-editing)

- [Annotations, Tracing, & Hardware Details Manual](#annotations-tracing--hardware-details-manual)
  - [Cable Tracing View](#cable-tracing-view)
  - [Placing Markers](#placing-markers)
  - [Entering Marker + Trace Details](#entering-marker--trace-details)
  - [Communication Pole](#communication-pole)
  - [Drop Pole](#drop-pole)
  - [Pole Class](#pole-class)
  - [Identification Placement of Attachments on a Pole](#identification-placement-of-attachments-on-a-pole)
  - [Electric, Fiber Optic, Telephone Copper, and Coaxial Cable Identification](#electric-fiber-optic-telephone-copper-and-coaxial-cable-identification)
  - [Guys, Overhead Guys, and Anchors](#guys-overhead-guys)

- [Katapult OSP Training](#katapult-osp-training)
  - [Anatomy of a Pole](#anatomy-of-a-pole)
    - [Power Pole](#power-pole)
    - [Transmission Power Line](#transmission-power-line)
    - [Distribution Power Line](#distribution-power-line)
    - [Communication Pole](#communication-pole)
    - [Drop Pole](#drop-pole)
    - [Pole Class](#pole-class)
  - [Identification Placement of Attachments on a Pole](#identification-placement-of-attachments-on-a-pole)
  - [Electric, Fiber Optic, Telephone Copper, and Coaxial Cable Identification](#electric-fiber-optic-telephone-copper-and-coaxial-cable-identification)
  - [Guys, Overhead Guys, and Anchors](#guys-overhead-guys-and-anchors)
  - [Strand and Lash](#strand-and-lash)
  - [Transfer of Attachments](#transfer-of-attachments)
  - [Mid-Span Tap (Attachment/Crossover)](#mid-span-tap-attachmentcrossover)
  - [Common Underground Facility Markers and Equipment](#common-underground-facility-markers-and-equipment)
  - [Placement](#placement)
  - [Right of Way](#right-of-way)
  - [Standard Ground Clearance](#standard-ground-clearance)


# Photos Overview And Classification

Photo Classification is the process of classifying, calibrating, and entering initial data onto the photos that were gathered during the field collection process. Calibrating is essential for helping the software calculate accurate heights. Classifying photos is crucial for inputting information that helps Katapult Pro automatically associated photos, provide intelligent warnings if photos are associated to the wrong entity (i.e. a midspan incorrectly associated to a pole), provide visual feedback when specific critical crossing make ready clearances are violated, scraping photo inputs onto nodes, and more.

After uploading photos to a job, find the Photos page from the App Tray. 

<img src="img/grid.png" width="300">

This will open a new Photos page, which is synced to the Map page. If you have a job open in the Map page, Katapult Pro will open the Photos page with that job selected.

If you don't have a job open, you'll use the Job Chooser at the top left of the page to find the job.

<img src="img/selectjob.png" width="300">

You can navigate to other jobs by searching for the job in this Job Chooser dropdown at any point.

    ⚠️ The folder icon to the right of it will "Open Job Chooser," which may make it easier to find the job if you organize them in folders.

You can use the “Collection Sets” button to the right of the "Open Job Chooser" button to filter photos from the job based on when the photos were uploaded. The days uploaded will be displayed, and you can check which days' photos you want to view.

The button to the right of the Collection Sets button is used to select all the photos within the job (and is aptly named "Select All Photos.") When this button is pressed, the photo thumbnails at the bottom will all be highlighted yellow, and a blue button will appear at the bottom right to show the number of photos selected.

<img src="img/selectedphotos.png" width="300">

You can select the “X” to deselect the photos, or click the three-dot menu to see various options.

<img src="img/unassociate.png" width="300">

Clicking the three dots will give you the option to unassociate photos from their location on the map, associate photos to the appropriate location on the map, delete photos from the job, or sort the photos by various categories.

Selecting photos can also be done by holding the “Ctrl” key on the keyboard and clicking the photo thumbnails from the bottom ribbon that you want, or holding shift and clicking to a photo to highlight a sequential series of photos. Again, click the “X” to deselect the photos.

<br></br>

## Katapult Pro Photos Layout

<img src="img/photolayout.png" width="500">

As you select a photo from the bottom photo ribbon, the photo will be displayed in the center of the page. You can see which image you are currently on at the top of the window.

<img src="img/image.png" width="300">

Here you can see the photo above would be photo 2 of 39. You can see a preview of the previous and next photo to the sides of the selected photo.

You can move through the photo set by clicking the forward or back arrows to the left and right, or by using the arrows on your keyboard. You can also click on any photo within the ribbon.

The little upward-facing carrot arrow at the bottom of the picture, "^," will open the Photo Details for photo info and editing.

<br></br>

### Photo Colors

<img src="img/colors.png" width="300">

As the photos are classified, the color of the thumbnail within the photo ribbon will change.

- **Blue** - These are sync shots that have been entered with the job details information.
- **Gray** - These are photos that have no data on them yet. They have not been classified.
- **Green** - These are photos that have been classified or contain height data.
- **Orange** - These are photos that are classified as “Cable Tag”. They are a different color to make it easier to go through the photo ribbon and find Cable IDs.
- **Red** - This is the photo that is currently displaying in the middle of the screen in Katapult Pro Photos.
- **Yellow** - These are photos that are selected, which can then be unassociated, deleted or sorted

<img src="img/tips.png" width="300">

- **Darker Tip** - If the photo has a darker shade of its color cap at the top, it means the photo is associated to a node within the job.
- **Red Tip** - The cap will turn red if there is a location selected in the Maps page to indicate that those photos are associated with the selected location.

<img src="img/cyan.png" width="200">

- **Cyan Tip** - The cap will turn cyan if those photos are associated to the same location that the selected photo (the red photo tab) is associated to.

    <img src="img/grey.png" width="150">

        ⚠️ If you see a dark gray tab, this is a photo that was unable to fully upload because the upload process may have been interrupted. You'll have to re-upload the pictures. You can re-upload the whole picture set, and any duplicates will be skipped.


## Classification

To start classifying photos, click on your starting photo in the photo ribbon. You can start anywhere along the ribbon, and multiple users can classify photos in the same job.

    ⚠️ If multiple users are in the same job classifying, you will see the other user’s avatar over top of the photo they are currently working on.

<img src="img/pole.png" width="500">

Next, click on the photo to create a temporary input marker, opening the one-click-menu, and click on the 
black icon to the left of the dropdown, the Photo Toolset Chooser. This button allows you to switch between photo toolset picklists that would be used in annotation and classification for different workflows. Choose the "Classify" option under this button. 

Once selected, you can use the dropdown to see the pick list of current classification options. There will also be a keyboard shortcut in parenthesis after each classificaiton.

As you classify, a photo data chip (or photo chip) will be added to the photo at the top right of the photo window for that photo.

<img src="img/hallway.png" width="300">

You can click on the chip to expand its details. Using the three dot menu, you can add or remove attributes, or you can delete the chip by clicking the trash can icon.

If a photo contains multiple pieces of information used for classification, you can enter as many classifications as you need. For example, if a photo had two pole tag numbers in it, you could have two "pole_tag" chips on that photo with each one having data for the different tag. If the photo also contained the birthmark, you could classify the photo as a birthmark shot as well.

## Calibration

For any photo that will require calibration (Midspans and Pole Heights), once the classification is selected, a routine will start within the software.

For example, if you have a midspan shot, and you click “m” on the keyboard to utilize the midspan shortcut, the software will start the midspan height routine.

<img src="img/over.png" width="500">

Once you select that, the software will start with the height routine. So your very next click will place a 16.5’ height marker. Zoom in on the photo to look for the top calibration sticker at 16.5'. Once your crosshair (circled in orange) is in the middle of the white square, go ahead and click.

    ⚠️You can hold the Shift key and click near the top calibration target sticker to use Katapult Pro's Target Detection without zooming in on the photo. 

<img src="img/zoom.gif" width="600">

As soon as you click, the software will automatically go to the next height in the routine, which is 14.5'. You can zoom out on the photo and zoom in at that next height calibration sticker, or you can use the down or up arrows on the keyboard to pan down or up the photo at your current zoom level. Each click will place the anchor and advance to the next anchor in the routine. Repeat this process until the routine has finished.
    
    ⚠️ The pole height and midspan height routines are designed for use with black calibration target stickers. If the standard black targets are obstructed, purple calibration target stickers may be used as alternates to denote whole-foot measurements.

You should see the calibration turn green, and the calibration line (yellow line) will extend up from the top of the height stick through to the top of the photo.

For pole height shots, there will be an extra step after the height routine, where you will need to place the pole top marker at the top of the pole. For midspan height photos the software will insert the Midspan Height chip and you will choose the midspan type, or what the span is over.

The software will also give you warnings depending on the approximate accuracy of your calibration.

    ⚠️ These warnings are useful if you need to place a calibration anchor on the red and white lines or purple target stickers because of a calibration target being covered. Just because the markers turn green does not guarantee the +/- 3 in. accuracy. You are guaranteed accuracy if you use the calibration targets or properly make use of the red or white lines on the stick.

<img src="img/yellow.png" width="400">

If the calibration is **yellow**, one of your anchor points is definitely off a bit.

<img src="img/red.png" width="400">

A **red** calibration shows that one or more is off to a greater extent. Double check that your anchors are placed correctly and that the stick is fully extended. Accuracy of measurements can only be guaranteed if the calibration is performed correctly at the given targets.

<img src="img/green.png" width="400">

If any calibration anchor markers are poorly placed, you can replace them using the Re-enter Calibration Anchor tool. This will prompt you re-etner the anchor marker using the same height measurement. 

<img src="img/placed.png" width="400">

    ⚠️ Once anchor markers are placed, you are NOT able to move them around or change the height. You will need to delete the marker or re-enter it.

<img src="img/poletag.png" width="400">

For classifications that require data to be entered, such as tags and birthmarks, you will be able to enter the necessary data in the text line of the chip's details.

## Photo Info and Editing

<img src="img/arrowup.png" width="400">

If you need to see the photo details or make any edits to the photo to help enter data, you can expand the window below the photo.

<img src="img/info.png" width="600">

The Info section will display the photo's information. Here, you can see all the camera and lens settings, as well as the date the photo was taken and the users that uploaded or edited the photo.

    ⚠️ If a midspan or pole height photo will not calibrate, you may see an error message that says "camera unrecognized." You can check the settings to see what might have gone wrong, but ultimately if the settings were wrong or an unapproved camera was used, the height photos will need to be retaken.

You can also click on the blue “FIND IN MAPS” button in this info section to zoom to the location in Katapult Pro Maps where the photo is associated.

<img src="img/edit.png" width="600">

Under Edit, you can mark a photo for re-upload, rotate the photo, and you can adjust the photo’s brightness and contrast. (Our software skips photos already uploaded to a job when photos are re-uploaded, so marking a photo for re-upload means that photo will get overwritten on re-upload.) Clicking the “Reset Filters” button will set the brightness and contrast back to zero.

<img src="img\display.png" width="600">

The last section will display the various make ready needed if the photo is in MR view.

To collapse this photo details window, click the arrow below the photo again.

<img src="img\buttons.png" width="600">

Lastly, the buttons at the top will change the view of the photo. The far left button is “Make Ready View.” Clicking this button will switch the photo to display the make ready clearance violations. The middle lock button is “Read Only” mode. Just as in Maps, you will be able to view photos in read only mode, but you will not be able to make edits. The last button to the right of read only mode is “Cable Trace View”. Clicking this button will open up the trace view, where the height of attachments can be marked.

# Annotations, Tracing, & Hardware Details Manual


## Cable Tracing View
Annotations are used to mark up the heights of attachments on poles, and Tracing is how we carry their connections throughout the job. We do both steps at once using the "Cable Tracing View."

<img src="img\buttoncircle.png" width="200">

To turn this on, click on the “Cable Trace View” button at the top of the Map page after opening Katapult Pro in Chrome. When the view is on, the button icon will turn blue, and there will be a highlight behind the connections on the map.

Now you are able to click on the connections (not the nodes or sections) to open up Cable Trace View in Katapult Pro Photos. Start at the first connection at one end of the job.

<img src="img\orangearrow.png" width="500">

Clicking on this reference span (the pink span with the orange arrow pointing to it) will open Photos in a new tab. Here you will see a multi-panel view. In the above case, a midspan and pole would be displayed.

    ⚠️ Having dual monitors is helpful because you don’t need to keep switching between the Photos tab and the Map tab.

<img src="img\2pictures.png" width="500">

If you need to switch the order of the photos in this view, you can click on the “Swap Photos” button located at the top middle of the page. Choose a photo order that makes sense to you and simplifies the annotation and tracing process.

## Placing Markers

<img src="img\crossarm.png" width="500">

At this first span, start on the pole photo, and open the One-Click Menu by left-clicking on the photo, which places a temporary input marker. Then, if you have the option, click on the black icon (we call this the Photo Toolset Chooser) and make sure you are using the Measure picklist (or the Measure Photo Toolset).

Once you have your Photo Toolset selected, you will see a list with different assemblies, equipment, and wires.

<img src="img\crossarm2.png" width="500">

Some of them might also have a letter or number in parenthesis to show the keyboard shortcut associated with the option.

Start at the top of the pole and work your way down when annotating attachments.

To add a marker, select the correct or closest option from the dropdown. You can filter out the options in the picklist by typing in the search bar.

<img src="img\crossarm3.png" width="500">

Once you find the correct option, click it. If it is a routine, the software will run you through the entire routine. For example, if the "Ridge Pin & 2 On Arm (2)" was selected, the top ridge pin would be placed first, and the next click on the photo would place the 8' arm with 2 pins nested in it. (The 2 in parentheses tells us that we could hit '2' on the keyboard instead of left-clicking to open the One-Click Menu to run through this routine.)

<img src="img\crossarm.gif" width="500">

When you place a marker on the photo, you want to make sure you click where the bolt goes through the pole face you are measuring for consistency. Be sure to account for parallax that occurs; if the bolt is not on the front-facing side of the pole, it may mean that the bolt hole is slightly above or below the bolt, depending on what side of the pole it's on.

Now that the markers are placed, you can move them by clicking on the handle of the marker (not the circle). Simply left-click and hold, then move the marker to where you need it and release the click.

## Entering Marker + Trace Details

If you right-click on a marker, it will open up the details window for that marker. When items are nested, right click on the item you need to edit. For example, in the above GIF, you could right-click on the brownish 8’ arm marker to edit the spec of the arm. If you want to edit the insulator, you should right-click on the greenish portion of the handle. Lastly, if you have to make edits to the wire, right-click on the bluish purple marker.

<img src="img\marker.png" width="500">

For wires, you will have two tab options: Marker and Trace. Marker attributes pertain to any data that should exist only on that specific marker where the attachment is located in the picture. Trace attributes will contain any data that should be updated throughout the wires' trace in the job and will be shared across multiple markers (such as the Company, Cable Type, etc.).

<img src="img\markercheck.png" width="500">

Under the trace tab, you will find Cable Type and Company attributes. You can change the cable type at any time by clicking in the textbox and searching for the appropriate option from the pick lists. You are able to do the same thing with "Company." Look through the pick list to find the correct company.

For the Utility company, you may want to check the box to set it as the default. This will allow you to quickly place utility wires and equipment. With the default box checked, the company name will auto-fill.

<img src="img\utilitycompany.png" width="500">

Up at the top of the wire menu towards the right will be 4 symbols. Clicking the carrot arrow will collapse or expand the wire menu. The stacked boxes with an arrow pointing from one to the other will remove the item from where it is nested, popping it out of the annotation(s) it's inside.

## Nested Markers

<img src="img\marker.gif" width="500">

You can remove a wire from an insulator, and you can also remove an insulator with a nested wire from an arm. So make sure you are at the correct item when you click the button to 'pop out' that item.

The wire or 'insulator and wire' bundle will be placed at the same height when the button is clicked. (See GIF above.) If you need to nest a wire or bundle into an arm, just left-click and hold on the bundle you want to move into the arm. Make sure the cursor is over the marker you want to add to, and once you see the “Drop to Add” text, you can release the click. Again, you are going off the cursor position, not the circle that marks the height of attachment.

<img src="img\primary.png" width="500">


## Marker + Trace More Options
<img src="img\marker2.png" width="500">

Moving along the wire's menu at the top, clicking the Three Dot Menu will open more options. Under the Marker tab, you will be able to add or remove attributes if needed.

<img src="img\marker3.png" width="500">

The available options under the Trace tab deal with the trace of the wire. Clicking the "Proposed" option that's listed first will mark the wire as 'proposed.' Doing this will add a proposed checkbox to the wire. You can click on the checkbox to unmark the wire as 'proposed.'

Under these options, you can also add a marker to a trace, remove a marker from the trace, split the trace of the wire (used when wires are incorrectly traced in a job, discussed more in the Helpful Tips section of this manual), and delete the trace.

## Delete Markers

<img src="img\trashcan2.png" width="500">

The last button in the top right of the marker's menu is the trash can icon or delete button. This will delete the marker and anything nested in the marker as well.

## Power Space

<img src="img\powerspace2.png" width="500">

Once the top assembly is marked up, keep moving down the pole. Look for any equipment or other attachers you need to mark. In the above image, the next wire is a neutral at 30'-6". You can click on the photo to place a temporary input marker, then search for a neutral option.

    ⚠️ The picklist will come from the pole loading analysis platform you are using. If you are not doing PLA, you will be able to use a “wire” marker and select the cable type after the wire is placed. You will not need an insulator.

<img src="img\tag.png" width="500">

Because you set the Power company as the default, you will not need to go into the trace options of the wire to enter the company. If you need to change anything, you can right-click on the insulator or wire to open its details.

Continue moving down the pole, marking all attachments and equipment.

## Photo Chooser
<img src="img\photocircle.png" width="200">

If you need to, you can click on the “Photo Chooser” button at the bottom left of the photo to see all reference photos for that pole location. Use these photos to identify communication owners, check for equipment, and see other angles of the pole.

If your field crews did take multiple pole height shots, you can also set which one is best and should be used as the main photo by clicking the star icon at the top right of the photo. To exit the Photo Chooser view, click the gray space on the photo. This will take you back to your main photo for trace view.

## Communication Space
<img src="img\verticalline.png" width="500">

When you get to the communication space, find your 'wire' option. For those who don’t have PLA or don’t have communication bundles, it will only be “wire," while for those who have bundles, find the "insulator, messenger, and wire" option so that you can build the communication bundles properly.

Again, click on where the bolt goes through the pole while accounting for parallax. Once you click the wire option, the software will automatically go into the trace routine (it will want you to trace that wire to where it is at the midspan).

<img src="img\click.png" width="300">

You will know you're in the software's trace routine when you see the notification in the bottom left corner of the screen that says "Click on the makers to connect."

    ⚠️ If you are just starting out, hit the Escape ("Esc") key on the keyboard to cancel out the trace routine.

Then you can fill in the Cable Type and Company. If you can’t identify the company yet, you can list them as “Unknown” until you are able to find a comm ID photo.

<img src="img\marker4.png" width="500">

Because the wires are traced through the job, anything you update or change in the trace tab of one wire will propagate throughout the entire trace. So once you update the Company name at a single location, the company will update throughout the rest of the markers that were traced together.

<img src="img\line.png" width="500">

If communication wires are boxed and run through the same span, include both attachments. In the above example one is a fiber optic cable, and the other is a telco attachment. The wires are placed at the same height of 23'-2”.

## Copying + Pasting Markers
<img src="img\line2.png" width="500">

If you have multiple wires from the same company, you can use a copy and paste shortcut so that you don’t need to click on the photo and add a wire and its details for each one.

To copy a marker, left-click on the wire, equipment, or bundle you want to copy (you should see a yellow highlight around the item), then hit "Ctrl + C" on the keyboard. This will copy the marker, and you will see a notification pop up at the bottom left (boxed in orange in the above image), letting you know you successfully copied the marker.

Now left-click on the photo again to remove the yellow border around the marker. You can now hover your mouse cursor over the photo where you need to paste the marker. You do not need to click the mouse again. If you press "Ctrl + V" on the keyboard, the marker will be pasted at the height of the cursor.

<img src="img\morelines.png" width="500">

    ⚠️ You can use the copy and paste shortcut even if the wires, bundles, or equipment are not exactly the same. Often, copying then changing some details (i.e. a spec or a company) is quicker then clicking, adding a new marker, and filling out all its details.

Once the pole is all marked up, you can now start tracing the wires across to the midspan(s).

## Tracing Cables
<img src="img\2monitors.png" width="500">

You will have two options for tracing the wires to the midspan. You can do one wire or bundle at a time by hitting “~” on the keyboard (to the left of the "1" key). Or you can hit "Alt + ~” to initiate a trace routine (which we call the Extraction Loop) that will start at the top of the pole and work down automatically.

If you press only “~,” you will see that notification at the bottom left of the screen to “Click on the markers to connect.” You will now be able to click a marker on the pole (make sure to click the outermost portion of the handle if you are clicking on a bundle).

<img src="img\monitor.gif" width="600">

Once you have your marker selected, you will see a yellow border around the marker. You can now move your mouse cursor to the midspan photo and zoom in on that wire in the midspan. When the tip of the cursor is placed correctly, left-click to place the wire.

    ⚠️ As soon as you start the trace, a quick left-click will place the wire, so be intentional about where you click. You can always left-click and hold to move the photo around, but a quick left-click will place the marker. Also, make use of the wheel on your mouse to zoom in on the photo to accurately place the wire.

<img src="img\3.png" width="600">

Now that the wire is placed, the trace action will end. You can see how the wire is traced because a yellow border will be around the wire in the midspan, and a yellow rectangle will appear to the left of the nested neutral on the pole. (If it wasn't nested in an insulator, it would be highlighted in a yellow border as well.)

If you change anything in the trace tab of the marker, it will update throughout the entire trace. You can also delete the marker in the midspan if needed; this is especially helpful if you accidentally traced the wrong wire.

Repeat this process until all appropriate wires have been traced to the midspan.

    ⚠️ This method is good for one off wires or for taps coming off a pole line, but generally you should use the trace routine, or Extraction Loop.

## Extraction Loop
<img src="img\4.png" width="600">

Hitting "Alt + ~" will commence the Extraction Loop. (Use "option + ~" if you are using a Mac.) The Extraction Loop will start at the top marker and work down. You will know you are in the routine if you see the notification pop up at the bottom left of the screen that says "In extraction loop. Press Esc to go onto the next item," which you can do if you don't need to trace the wire to that midspan.

<img src="img\4.gif" width="600">

As you click to place the wire in the midspan, the routine will automatically go to the next marker in the photo based off of height. So again, make sure you only left-click on the midspan photo to place the correct marker. If you need to move the photo around to have a better field of view, long click and move the photo, then release the click once the photo is in a good position.

<img src="img\5.png" width="600">

When you get to wires that are boxed, the software will first go to the marker handle that is higher up on the photo (even if they are at the same height). So just make sure you are aware of which marker the software has selected (which one is highlighted) when tracing to the midspan.

To skip a marker that's not in the midspan but is highlighted on the pole, click escape (Esc) on your keyboard.

When you get done with the last marker, the Extraction Loop will end automatically. You can now reposition wires if needed or right-click on a wire to add data or attributes.

<img src="img\7.png" width="600">

Once the pole and midspan are set, keep the Photos page tab open, but return to the Map page and click on the next connection. In the above photo, this will be the first aerial connection. Clicking the connection will open up that span’s photos; in the above instance, this is the pole-midspan-midspan-pole photos.

<img src="img\2.gif" width="600">

Now, because the one pole is already done, you can use the Extraction Loop routine to trace the wires to the midspan(s) and to the next pole.

Again, use the "Alt + ~" shortcut to start the Extraction Loop (or "option + ~" on Mac). Now you will need to click on the first midspan, then the next midspan, and finally the location the marker should be at on the pole to completely trace the marker. Once that is done, the routine will go to the next marker to trace through.

Remember, whichever photo your cursor is over, that is the photo you are currently interacting with. You can zoom in and out of each photo independently.

When you get to the communication wires, because the diameter was already set, you do not need to set it again, but you can adjust the diameter if the wire size does change.

<img src="img\8.png" width="600">

    ⚠️ It is helpful to position the photos in a way that makes marking the communication wires easier. Try framing the midspan(s) and next pole photo in a way where you are zoomed in enough to accurately place the wire but aren’t too far in that you need to keep zooming out or in for each wire.

During this step, you should only be worried about tracing the wires to the next pole. Even if new attachments are on the next pole, you are only worried about placing the traced markers correctly on the pole. Once the Extraction Loop is finished, you can then go to the new pole and go from the top down to fix any specs or add equipment or additional wires if there are any.

    ⚠️ It is best to completely mark up this pole before moving on in the cable tracing process.

## Photo Warnings

We have developed photo warnings to bring your attention to potentially problematic data that should be fixed, typically in relation to the annotations you place, but sometimes there will be warnings with the photos themselves. These warnings are provided on height photos where measurements are used, so they will appear if there is an issue once they are calibrated and have annotations. The severity of the warnings correlate with the software's confidence that the entered data is erroneous. There are three severity levels:

<img src="img\i.png" width="100">

- **Info** We are bringing your attention to something that may need fixing. The icon is a blue circle, depicted to the left. 

<img src="img\caution.png" width="100">

- **Warning**. We are more confident that the entered data is an issue and should be addressed in some manner. Exercise good judgement when addressing these warnings. The icon is a yellow triangle, depicted to the left.

<img src="img\!.png" width="100">

- **Error**. This will most likely affect the accuracy of the software's output. We strongly recommend retaking the height photo to correct the mistake that was initially made when capturing the height photo.

Whether you're viewing the height photo in the Maps page or on the Photos page, photos that have any warnings will have a warning icon in the bottom right corner of the photo, corresponding with the style of its most severe warning.

<img src="img\orangewarning.png" width="500">

    ⚠️ Use the Toggle Measurement Area button (brown icon) in the bottom left of any height photo. This will outline the area of the photo where the pole should be visible. Any measurements placed outside of this framing may produce photo warnings. This feature will also create yellow and red bands at the top of the photo where measurements do not fall within the standard accuracy.

<img src="img\rectangle.png" width="400">

For example, this height photo's most severe warning is an informational warning. Clicking the warning icon in the bottom right of the photo (circled in orange above) will open the Photo Warnings window. Here we see that there are two warnings for markers, identified by their height. If the photo itself had a warning (for example, if the main camera operator took the photo too close to the pole), that would show up in this window as well.

<img src="img\9.png" width="600">

Markers with warnings will also show the warning icon to the right of their height, corresponding with the warning's severity. Click on the "i" icon to open the warning's information. This is the same warning that is provided in the Photo Warnings window.

### Currently, our software will flag the following issues:


- **The marker is too close to the edge of the photo.**
    - Severity: **Info**. Frame the subject of the photo with more space above and below and frame it in the center of the photo to reduce the effects of distortion around the photo's edge.
- **The marker is not centered.**
    - Severity: **Info.** Frame the subject in the center of the photo to reduce the effects of distortion around the photo's edge.
- **The orientation isn't portrait.**
    - Severity: **Warning.** Photos taken in landscape orientation have fewer usable pixels for calibration as well as cable identification than photos in portrait landscape.
- **The marker is off the edge of the photo.**
    - Severity: **Error.** If your marker is off the edge of the photo, there is no data whatsoever to confirm its height.
- **The main camera operator took the photo while standing too close to the pole.**
    - Severity: **Error.** The pole is closer than recommended. Close proximity can magnify errors in stick placement, calibration, leaning or warped poles, parallax, and lens distortion.

## Helpful Tips
 - **If you don’t see an equipment type or cable type in your picklist, either add them to your catalog or client and add them to the [Model Editor.](https://guide.katapultengineering.com/model-editor-manual)**

- **When tracing, most times the extraction loop will be quicker,**

<img src="img\11.png" width="600">

but if you have just one or two taps coming off the pole to a reference (like above), it may be quicker to use “~” and select the correct wires to trace.

- **You can add the attribute "Wire Tension" to a wire and select the appropriate tension for that wire.**

<img src="img\12.gif" width="600">

Full tension is the default, so you only need to adjust the tension when appropriate.

- **Holding the Control ("Ctrl") key on the keyboard and left-clicking on markers will allow you to multi-select markers.** This is a good way to add attributes to multiple markers at once.

- **If you miss-click when trying to trace and a temporary input marker pops up, just hit escape ("Esc"), delete the marker, and run the trace routine again.**

- **When you finish a trace for a wire, that wire will become faded when you trace again** so that you can’t accidentally trace the same wire twice. Equipment and anchor calibration points will also be faded to denote that those can not be selected.

- **As you need to mark up equipment on the pole that contains a routine, the step of the routine will be displayed at the top left of the page.**

<img src="img\13.png" width="600">

Look for what measurement you should be clicking on. In the above example, the next click will place the top bolt of a transformer. Once you left-click on the photo to place that marker, the routine will then advance to the next measurement you need to mark for that equipment.

    ⚠️ This is typically the case for transformers and street lights.

- **Two people can perform cable tracing on a job together.**

<img src="img\14.png" width="600">

Each should start at a different end of the job. Once you get to the point where you meet up, you will need to join the traces together. For this, you will need to run “~” to trace and select the wire only -- even in bundles. You can then select what wire on the other pole you want to join to. Be sure to select the correct wire, because splitting the trace after the fact can be tricky. Do this for each wire.

- **If you get to a wire in a trace that is marked differently,** (in the below example, the Fiber Optic Com was Unknown on the left pole and the Fiber Optic Com was identified as Fiber on the right pole), **you will have the option of which value you want to keep.**

<img src="img\15.png" width="600">

Here, Fiber would be selected since it was identified. Once you select a company and click “Join,” the company of the trace will be updated to the one you selected through the entire trace.

- **If you need to split a tracing error where wires were joined incorrectly, go into the Trace tab of the wire, and click “Split.”**

<img src="img\split.png" width="400">

This will open up a window to split the trace. Click “Okay” and return to Maps. **The wire’s trace will be highlighted blue on the map.** If you only wanted to check where a trace is within the job, you can click "Cancel" at this point.

<img src="img\cyan.gif" width="600">

Or you can now draw a polygon around the poles and sections you want to keep in the trace. This will disconnect markers outside the polygon from the trace.

- **If you have a vertical transition, mark each bolt on the pole, but do not trace the wires together on the pole.**

<img src="img\17.png" width="400">

Just trace the appropriate wire to its corresponding midspan.

- **If you are doing a workflow that uses communication bundles, overhead guys will not use the bundle.**

<img src="img\19.png" width="400">

You will simply enter them as wires and select the Cable Type as a guy (power guys will be labeled as power guys in their Cable Type attribute).


- **If you have a stub pole, where the communication wires have not transferred yet, typically we place them on the new pole.**

<img src="img\20.png" width="400">

This way we can call for a transfer height during the Make Ready step.

    ⚠️ Only trace the wires that are found in a connection. If you have a crossover, and only some communication wires hit the crossover, trace those wires to the crossover. The power and other communication wires that do not hit the crossover should be joined using a separate connection.

- **If a midspan was not collected, you can always use the “Insert Blank Photo for Measuring?” button at the bottom to insert a dummy photo to trace the wires.**

<img src="img\insert.png" width="200">

This should only be used if the midspan contains no violation, and it's typically used as a last resort to help build the 3D model of the pole. Most often, you should have your crews recollect sections or poles that were missed.


# **Katapult OSP Training**

## **Anatomy of a Pole**

### **Power Pole:**

<img src="img/poleanatomy.jpg" width="500">


### **Transmission power line:**

Electric power transmission is the bulk movement of electrical energy from a generating site, such as a power plant, to an electrical substation. The interconnected lines that facilitate this movement form a transmission network. Referred to as primary lines with highest voltage to provide power to substations.

### **Distribution power line:**
Electric power distribution is the final stage in the delivery of electricity. Electricity is carried from the transmission system to individual consumers. Referred to as secondary lines with lower voltage for services.

## **Examples of Power Poles:**

**Power pole with distribution and transmission power:**

<img src="img/powerpole.jpg" width="500">
<br></br>

**Power pole with transmission power:**

<img src="img/dist.jpg" width="500">
<br></br>

**Power pole w/ distribution power:**

<img src="img/transmission.jpg" width="500">
<br></br>

<br></br>

<img src="img/powerequip.png" width="700">

<br></br>

<img src="img/powerline.png" width="700">

### **Communication Pole:**

Typically, communication companies (copper, fiber and coaxial cable have a shared space below power on the power pole. On occasion, communication will have its own pole line with no power attachments as pictured below.

<img src="img/22.png" width="250"><img src="img/23.png" width="206">

## **Drop Pole:**

Whenever power or communication need to provide a service drop to a customer, sometimes a drop pole is used to provide the service to customer that resides at further distances from the mainline distribution poles. Below are a few examples.

<img src="img/drop.png" width="400">

## **Pole Class:**

Utility poles are divided into ten classes, from 1 to 10. The classes' definition specifies a minimum circumference that depends on the species of tree and the length of the pole. This circumference is measured 6 feet from the butt of the pole. There is also a minimum top circumference that is the same for all species and lengths. A 35-foot pole is a typical length used in cities to carry one or two crossarms.



<img src="img/table.png" width="500">

## **Identification Placement of Attachments on a Pole**

<img src="img/attachment.jpg" width="500">

The diagram above is a general representation of placement of power utilities and communication utilities on a utility pole. The shared communication space can include singular or any combination of copper, fiber, and coaxial cables.

## **Electric, Fiber Optic, Telephone Cooper, and Coaxial Cable Identification**
<img src="img/identify.jpg" width="500">


Electric utilities are identified above in 3 basic areas: Primary – highest voltage to substations. Secondary – lower voltage to transformers. Service – lowest voltage to provide individual service. Electric will also include a power neutral; all communications cables reside below this neutral.

Coaxial cable can be utilized by communication companies to provide telephone, internet and cable services to customers. 
<img src="img/cross.jpg" width="300"><img src="img/transformer.jpg" width="300">

Several items help to identify coaxial cables, the most noticeable are the tension loops which are common with aluminum cables.  They look like a dipped area that appears to be almost accidental, but their purpose is to keep the cable from becoming too taught in extreme weather conditions. Coaxial splice cases are almost always a bullet-shaped case with all of the cables and services coming out of the same end, the flatter end. Coax also has regular amplifiers, galvanized steel cases with straight slotted vents on the side. Coaxial cable also has splitters.  These are usually a light olive green and rather squared in shape.  They also tend to have numerous cables and services coming from the splitters.

<img src="img/CATV.jpg" width="600">
<br><br>
Telephone copper cable can be utilized by communication companies to provide telephone and internet services.
<br><br>
<img src="img/1.jpg" width="300"><img src="img/2.jpg" width="332">


Telephone cables are usually the top communication cable.  This is because of the extensive period in which the telephone was the only communication method.  Coaxial and fiber cables came along much later. The only telephone cables you are likely to see will be black polyethylene, and rather thick.  They have a rectangular splice box. Telephone cables vary in thickness depending on the number of pairs in the cable. Usually larger than coaxial or fiber.

Fiber optic cable can be utilized by communication companies to provide internet services. Fiber optic technology has become a primary source for communication companies that want to provide high speed internet services. 

<img src="img/snowshoe.jpg" width="400"><img src="img/3.jpg" width="265">


Fiber optic cables always have that black polyethylene jacket and are rather small in diameter. Their most noticeable feature are the snowshoe loops, a pair of hoop attachments where the fiber cable is looped back and forth multiple times. Fiber splice cases are usually more rounded on the ends than phone splice cases. Fiber cables also often have orange bands attached at various places along the pole line to quickly identify them.

## **Guys, Overhead Guys, and Anchors**

A guy-wire, guy-line, guy-rope, down guy, or stay, also called simply a guy, is a tensioned cable designed to add stability to a free-standing structure. Utility poles are buried in the ground and have sufficient strength to stand on their own; guys are needed on some poles only to support unbalanced lateral loads due to the utility wires attached to them, or to resist ground movement. Guys are particularly needed on dead-end (anchor) poles, where a long straight section of wire line ends, or angles off in another direction. Over-head guys are lines between two poles to secure a pole on opposing side of street when a down guy and anchor is not possible.

In ground-anchored guys, the structure which attaches the guy-wire to the ground is called an anchor.[2] The anchor must be adequate to resist the maximum tensile load of the guy wires; both the dead load of the tension of the wire and the maximum possible live load due to wind. Since the guy wire exerts its force at an angle, the anchor has both vertical and lateral (horizontal) forces on it. The anchor relies on the lateral shear strength of the soil to resist the forces from all the guys attached to it. 
<img src="img/drop1.png" width="300"><img src="img/guy.png" width="266">

## **Strand and Lash**
Strand and lash consist of a steel support strand used to support any type of communications cable, typically held in place with a stainless steel lashing wire. A lasher can lash with one strand of lashing wire (single lashed) or with two strands (double lashed)
<img src="img/lash.jpg" width="500">
<img src="img/strand.png" width="500">

## **Transfer of Attachments**

Power companies will often replace existing poles with new. In many cases they will remove the top of the old pole after they have transferred their attachments to the new pole. This will result in 2 poles in same location. Power companies are dependent on communication companies to remove old pole/attachments and reattach to new pole. 

<img src="img/30.png" width="150"><img src="img/31.png" width="250">

## **Mid-Span Tap (Attachment/Crossover)**
Communication lines will occasionally utilize what is called a mid-span tap. These are always accompanied by a splice case nearby. The purpose of these is to distribute cable in multiple directions when no pole is present or even possible to place.
<img src="img/tree.png" width="350"><img src="img/sky.png" width="250">

## **Common Underground Facility Markers and Equipment**

When performing pre-fielding, fielding, design and construction of communications facilities, it is sometimes necessary to use an underground approach rather than aerial. In these cases, it is important to be able to identify existing underground facilities. In most cases, it is common to utilize the same areas when constructing a new communication line. Below are some common facility markers and equipment that communication and electric companies use.

<img src="img/ped.jpg" width="500">

Pad mount Electrical Transformer indicates buried electric facilities. In aerial placement there is a pole mounted transformer.

<img src="img/gas.jpg" width="350">

Indicates buried gas lines, usually communication tries to stay away from gas lines whenever possible.

<img src="img/hydrant1.jpg" width="370"><img src="img/hydrant2.jpg" width="250">

Fire hydrants are good indication of water lines. Communication also tries to avoid waterlines as well.

<img src="img/marker1.png" width="200"><img src="img/marker2.jpg" width="300"><img src="img/marker8.png" width="250">

Fiber optic markers, handholes, and pedestals indicate buried fiber optics. Fiber markers are always orange and white and can be a cylinder or square post, Fiber handholes or tubs are usually placed flush with the ground and can be rectangular or a cylinder. They also come in many different sizes. Fiber pedestals are not as common but are usually square or round and come in several sizes. Fiber bedestals are made of plastic.

<img src="img/case1.jpg" width="200"><img src="img/case2.jpg" width="315">

Copper pedestals indicate buried copper telephone lines, these pedestals are almost always square, These pedestals are usually metal.

<img src="img/ax.jpg" width="350"><img src="img/ax2.png" width="181">

Coaxial Cable pedestals indicate buried cable television lines. These pedestals are usually square and can be made of medal or plastic depending on how long it has been there.

## **Placement**

It is usually the general rule that when constructing new underground communication routes, you almost always want to follow existing buried communication facilities. Below are a few examples of multiple utilities in the same area.

<img src="img/placement.jpg" width="250"><img src="img/placement2.jpg" width="250">

Another general rule when placing new underground facilities is to place access points in similar locations. It is always a good idea to place them on property lines between houses or businesses to provide easy access to multiple locations from one access point. This will minimize number of access points required to serve customers. Here is an example. Notice that access points are placed in between every other house along with existing buried facilities.

<img src="img/access.png" width="600">

## **Right of Way**

<img src="img/row.png" width="600">

A right-of-way (ROW) is a right to make a way over a piece of land. A right of way is a type of easement granted or reserved over the land for transportation purposes, such as a highway, public footpath, rail transport, canal, as well as electrical transmission lines, oil and gas pipelines.

Right-of-way is important when pre-fielding, fielding, designing, and constructing new or existing aerial and underground communication lines. It is important to remain within all right of ways with all new or existing communication lines. Right-of-way can vary depending on location. If in doubt, it is best to consult local transportation authorities in that area. 

Some common rights-of-way are 33 feet or 16.5 feet from the center for rural roads. Another common one is 66 feet or 33 feet from the center for city roads. And the last common one is 100-150 ft or 50-75 feet from the center for major highways. It is always better to check with local traffic authorities to be 100% sure.

## **Standard Ground Clearance**

<img src="img/clearance.jpg" width="500">

Ground clearance refers to the distance between the ground and the lowest conductor at its lowest point. Ground clearance differs from area to area and can be dependent on what the line is crossing over. For national standards, it is best to follow NESC standards for ground clearance. 

Ground clearance is important when pre-fielding, fielding, designing, and constructing new or existing communication lines. Ground clearance plays a role in determining if there is enough space on a pole for new communication lines. If proper ground clearance is not achievable, the solution is either a taller pole line or moving to buried communication lines.

# **Office Power Tools Manual**
The Office Power Tools toolset contains tools that perform a more custom function within the software. These are tools that have been created for a particular function and can’t be edited within the Model Editor.

Go to the "TOOLS" dropdown and select the Office Power Tools. Here you will see your list of office power tools.
<br>
<br>


### **Multi Edit Attribute**

<img src="img/pencil.png" width="50">

The tool that's typically first in the list is the Multi Edit Attribute tool, which is this blue-ish pencil icon tool that you'll find in the list of tools (shown above).

<img src="img/attribute.png" width="300">

When you click the tool, the window will appear where you can select an attribute from the picklist to either add, overwrite, or remove from multiple locations.

You can also select what items you want to edit: nodes, connections, sections, or a combination of the three.
Down at the bottom of the window will be various selection options. You can either “Select All,” which would affect all items, “Select By Type,” where a window will pop up, giving you the option to select which types of nodes, sections, and/or connections you want to edit, or "Select Items," which will affect items that you either click on or draw a polygon around.

<img src="img/types.png" width="300">

When you choose "Select By Type" and have the types selected, hit “DELETE ATTRBIUTE" (or "ADD ATTRBIUTE" if you chose the "Add" or "Overwrite" option).

<img src="img/drawing.gif" width="800">

The last option, “Select Items,” will allow you to click on or draw a polygon around the set of locations you would like to affect.

You will need to do this for each attribute you want to multi- add, remove, or overwrite.

<img src="img/multiaddd.png" width="300">

When removing an attribute, you can remove that attribute altogether or remove a specific instance of the attribute. For example, you can remove the "Pole Class” attribute from selected nodes, or choose to remove “Pole Class” attributes in the instance where the Pole Class is “3” from selected nodes.

    ⚠️ If you want to add more than one attribute at once, there is a way to do this: create a group attribute that includes all the attributes you want to add, and then select that group attribute you created when using the Multi Edit Attribute tool to add an attribute.
<br>
<br>

### **Multi Delete**

<img src="img/trashcan.png" width="60">

The Multi Delete tool allows you to delete multiple design items within a job at once. When you click the tool, you will be able to draw a polygon around items within the map.

<img src="img/delete.gif" width="800">

Then you can select whether you want to delete all nodes, connections, or sections contained in the polygon. (Notice at the bottom left corner, a counter pops up to show how many nodes, connections, and sections are contained in the polygon.)

    ⚠️ Because the existence of connections are dependent on their nodes, connections to nodes will be deleted when the node is deleted. Same for sections; because the existence of sections are dependent on the connections they exist on, they will be deleted when the connection is deleted.

When you click “Finish,” the software will ask if you are sure you want to delete the items, and if you are, you can select “Delete.” The items can’t be returned once deleted, so you can hit “Cancel” to cancel this action if you don't want the items permanently deleted.

<br>
<br>

### **Tally by Polygon**
<img src="img/polygon.png" width="60">

The Tally by Polygon tool is used to count the items contained within the job or a desired section of the job. When you click on the tool, the software will prompt you to click to add points to the map for a polygon, outlining the section you want to count.

<img src="img/polygonimg.png" width="600">

As items are surrounded by the polygon, a nodes, sections, and connections dropdown window will appear to the left. You can click on the dropdown to see a breakdown of the node and sections types and counts in the selected area, and a breakdown of the connection types and footages in the selected area.

Click on the “X” of the window at the bottom middle to cancel out the Tally by Polygon routine.

<br>
<br>

### **Copy Nodes**
<img src="img/copy nodes.png" width="60">

The Copy Nodes tool allows you to copy nodes or cut and paste nodes to another job. You can select an existing job or create a blank job for the nodes' destination when you copy or cut and paste them.

<img src="img/cpynodes.png" width="600">

When you click the tool, the window to copy the nodes to another job will pop up. You can use the dropdown to pick the desired job or create a new one. Then you can choose whether you want to copy and paste or cut and paste nodes.

You can choose to include connections and photos when copying/cutting and pasting. If you have any trace data, that data will also be copied if you choose to include connections and photos.

<img src="img/select types.png" width="300">

The buttons at the bottom of the window let you choose how and what to copy. If you choose "Copy Type...," you will have the option to specify what node type you want to copy based on the node types that exist in your job. In the above example, nodes with type "pole" and type "reference" are available to copy. If you choose "Copy All," all nodes (and connections, if "Connections" is checked under the "INCLUDE" portion) will be copied.

If you select "Choose Nodes..." you can then either draw a polygon around the nodes that you want to copy and paste or click on the nodes to select them.

<img src="img/copynodes.gif" width="800">

To draw a polygon around the nodes you want to select, click on the Map where you want the corners of your polygon to be (in the order that you would draw the outline). You can click and drag these points or right-click to remove the most recently placed polygon point. If you'd rather select nodes by clicking them, you can do this as well. Notice the window in the left corner of the screen that shows you the count for nodes (and connections) that will be included. The dropdown provides details of what type of node (or connection) is included.

<img src="img/warning.png" width="300">
   
    ⚠️ All node data from the job will be copied to the other selected job. If the two jobs have different map styles, you will see a warning asking if you want to proceed.

<br>
<br>

### **Join All Poles**
<img src="img/joinpoles.png" width="60">

The Join All Poles tool is typically used in the **pre-design** or scoping step. If you hover your mouse over the tool, it will warn you that it should only be run once.

When you click the tool, it will add an aerial connection between each pole. However, it will string the poles together in a single line. So if your route should have breaks or branching, it may be best to use the conventional join tool found in the field toolset. Should you run it again, you will have multiple connections layered on top of each other connecting the nodes, so only run it once.

<br>
<br>

### **Show Un-Associated Photos**
<img src="img\unassociated.png" width="60">

The Show Un-Associated Photos tool is used when photos have been left unassociated during the association step. This tool is a legacy tool that allows you to quickly see all affected photos at a glance, which will then help fix any association errors.

If you click on this tool, a photo tray will appear to the left of the map.

<img src="img/canon.png" width="300">

The photo tray will display all unassociated photos. At the top of the window will be the camera that photos were not associated for. You can then see where the photos likely belong, and drag and drop them from the tray to the map location.

At the bottom of the tray window is a menu.

<img src="img/menu.png" width="300">

Clicking on the red “X” button will close the tray. The light blue button next to it with the arrow pointing out of the top right corner of a box will open the tray in a new window. The darker blue button with an image icon will toggle whether associated photos are also visible or not. The green button is for toggling the collapsed view, while the grey button with the trash can will delete all the unassociated photos from the job.

<br>
<br>

### **Un-Associate Photos**
<img src="img\x.png" width="60">

If you had any errors in associating the photos, you can click the Un-Associate Photos tool to unassociate photos from the nodes and midspans/sections in the job.

<img src="img/uap.png" width="300">

When you click the tool, a window will appear in the center of the page. If you did have any photos where you have already manually moved or associated them, you can check the box to keep those photos at their current location.

<br>
<br>

### **Insert Sections**
<img src="img\triangle.png" width="60">

The Insert Sections tool will automatically insert a midspan section along all connections where no section currently exists.

    ⚠️ You should still be collecting midspans in the field. Marking “Done” in mobile is what actually places the section symbol (typically a blue triangle). This tool should only be used if you didn’t need to collect the midspan, but want to add dummy photos during the Cable Tracing process to assist in that workflow.

<br>
<br>

### **Address Data**
<img src="img\point.png" width="60">

You can quickly insert address data for locations on the map by using the Address Data tool.

When you click on the Address Data tool, the address data window will pop up to select various options. At the bottom you can select what address attributes you wish to add to the node locations.

<img src="img/addaddress.png" width="300">

With the "Add individual address attributes" checked, you may select or deselect the individual address attributes you wish to add. If you only have "Add 'Formatted Address' attribute selected, it will add a single "Address" attribute which contains the formatted address. The "Abbreviate State Name" will enter the state's abbreviation for the "State" attribute (if adding individual address attributes), otherwise the "State" attribute will have the full state name. Once you have the appropriate options selected, you have the choice to add to all nodes, add by node type, or manually select which nodes will get address data.

For most occasions, use the “Add By Node Type” to choose what node type will get address data.

Once you have the type(s) you wish, click “Get Address Data”. The software will automatically request address data on the desired locations. The address attributes will be added directly to the Node Info panel.

<br>
<br>

### **Fix Map Errors**
<img src="img\bandaid.png" width="60">

The Fix Map Errors tool is the band-aid icon in the toolset. This tool cleans up any corrupted data so that a job isn't prevented from exporting. Always get in the habit of clicking this tool before downloading exports, including PLA exports.

     ⚠️ If you have an underground project, save a snapshot of the job before running Fix Map Errors. This tool may delete faulty connections.

<img src="img\noerrors.png" width="300">

If there are no errors, a notification will pop up at the bottom left of the page. If there were errors, the notification will tell you the amount of data cleaned up.

<br>
<br>

### **Clear Warnings**
<img src="img\clearwarnings.png" width="60">

The Clear Warnings tool will remove the attribute “Warning” from all locations. In most cases, the "Warning" attribute is added to locations to provide any photo association warnings. This tool is clicked after you have fixed association errors and want to clear all the warnings at once (if you didn't already remove them manually one at a time as you fixed association errors).

<br>
<br>

### **Star Height Photos**
<img src="img\star.png" width="60">

Typically, when you associate photos you can auto-star height and midspan photos (as long as they have the "Midspan" or "Pole Height" photo chip on them). The Star Height Photos tool will allow you to run that again even after photos are associated. With this tool, you also have the option to star the first photo found if there is no height photo on the node or section.

<br>
<br>

### **Fix Company Names**
<img src="img\suitcase.png" width="60">

When you run this tool, you'll be able to change a company name found in cables and traces. For example, if you mistook one company for another while tracing, you could run this power tool to correct that everywhere that the incorrect company is annotated.

When this tool is run, the following window will display. It'll show you companies that are found in the job to the left, and your Company dropdown attribute to the right.

<img src="img\fix names.png" width="300">

<br>
<br>

### **Draw Polygon**
<img src="img\drawpolygon.png" width="60">

The Draw Polygon tool allows you to draw polygons inside Katapult Pro. The powerful aspect of polygons is the ability to not only edit the polygon, but any nodes/connections/sections inside it. 



When you run the tool, you'll see a modal at the bottom of the screen telling you to click to draw your polygon. Once you're satisfied with your polygon and click "Create," you'll name it, give it a description (optional), update the color (optional), and select a layer to add the polygon (if there aren't any, you can quickly create one using the displayed "CREATE NEW LAYER" option). This layer is tied to the job. 

<img src="img\createlayer.png" width="300">


The layer the polygon was added to is then turned on and off through the "Imported Layers" part of the map layers menu (bottom left corner of the software). In the above screenshot, the layer is called "Dillsburg Area," and is turned on since it's checked. (More than one polygon may be added to a layer.) The solid mouse icon next to its name indicates that it's selectable. This will allow me to edit the job or use the powerful job editing functions. 

<img src="img\polygonedit.png" width="300">


Starting with the icons to the left underneath **"Polygon Editing"** and moving to the right, we have the following:

**Polygon Editing**
- **Edit Feature** - change the polygon's color, fill color, and border size
- **Edit Feature Points** - move the points of the polygon to edit its border
- **Copy Feature** - copy the polygon (you can choose to copy it into a different layer)
- **Delete Feature** - delete the polygon (this will not delete its layer)


#### **Job Data Tools**
These tools can be used on an entire job itself from the job's tools or settings. Using these tools on a polygon from its menu essentially allows you to run those functions on the polygon as if the polygon and its contents were a job in and of itself.

- **Multi Edit Attribute** – select an attribute from the picklist to either add, overwrite, or remove from multiple items inside the polygon  
- **Multi Delete** – delete multiple design items within the polygon  
- **Tally by Polygon** – count the items contained within the polygon  
- **Copy Polygon Nodes to Job** – copy the items in the polygon to a job (existing or new)  
- **Download by Polygon** – export information from items inside the polygon (same format choices found in the download manager)  
- **Share by Polygon** – share items contained in the polygon with another company  
- **Transfer by Polygon** – transfer items contained in the polygon with another company (a new job will be created with all the information contained within the polygon and then transferred)  


<br>
<br>

### Bulk Pole Loading
<img src="img\arrow.png" width="60">

The Bulk Pole Loading tool will load your poles all at once and appropriately insert a pass or fail value to an attribute of your choosing. If you've properly annotated and **prepped your job for pole loading**, all you'll need to do is ensure that your nodes have a Load Case or Loading Analysis.

    Click the tool to run bulk pole loading. First you'll be asked to draw a polygon around the nodes you want to load at once.

<img src="img\bulkpole.png" width="300">

In the prompt at the bottom of the screen, click "Select All" to select all nodes or draw a polygon around nodes to select a particular subset and click "Continue." As you draw a polygon, the number of nodes is counted towards the left and can be broken down to the count based on map styles.

<img src="img\bulkload.png" width="300">

Once nodes are selected, choose whether you want to load your selection under existing conditions or proposed conditions. Then you can choose an attribute and its value to set on the node if it passes loading, as well as an attribute you want to set to a specific value if it fails. The default for passing and failing is the Loading Result attribute set to pass and fail, respectively.

<img src="img\loadresults.png" width="600">

Once the poles are loaded, the results will display in a window. We creation an **Action** to track who runs pole loading, so there is a toast in the bottom left corner to alert this Action has been recorded.

<br>
<br>

### Offset Lines
<img src="img\offset.png" width="60">

This power tool will place reference lines on either side of a connection based on the offset input by the user. This can be useful, for example, for placing a visualization of the right of way of state roads.

Run the tool, click on the connection, and it takes care of the rest. The offset you're providing will be either north/south or east/west, depending on the general orientation of the connection you select to base the offset on.

<br>
<br>

### Notes
The Office Power tools were created by our developers and can not be edited in the Model Editor. You can remove tools you do not use or need from the Toolsets section in Model Editor, but if you need assistance modifying existing power tools, or want an estimate to create a power tool, reach out to ***support@katapultengineering.com***.
