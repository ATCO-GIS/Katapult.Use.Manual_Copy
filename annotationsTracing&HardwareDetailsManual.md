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

