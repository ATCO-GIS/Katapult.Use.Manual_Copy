# **Office Power Tools Manual**
The Office Power Tools toolset contains tools that perform a more custom function within the software. These are tools that have been created for a particular function and can’t be edited within the Model Editor.

Go to the "TOOLS" dropdown and select the Office Power Tools. Here you will see your list of office power tools.
<br>
<br>


## **Multi Edit Attribute**

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

## **Multi Delete**

<img src="img/trashcan.png" width="60">

The Multi Delete tool allows you to delete multiple design items within a job at once. When you click the tool, you will be able to draw a polygon around items within the map.

<img src="img/delete.gif" width="800">

Then you can select whether you want to delete all nodes, connections, or sections contained in the polygon. (Notice at the bottom left corner, a counter pops up to show how many nodes, connections, and sections are contained in the polygon.)

    ⚠️ Because the existence of connections are dependent on their nodes, connections to nodes will be deleted when the node is deleted. Same for sections; because the existence of sections are dependent on the connections they exist on, they will be deleted when the connection is deleted.

When you click “Finish,” the software will ask if you are sure you want to delete the items, and if you are, you can select “Delete.” The items can’t be returned once deleted, so you can hit “Cancel” to cancel this action if you don't want the items permanently deleted.

<br>
<br>

## **Tally by Polygon**
<img src="img/polygon.png" width="60">

The Tally by Polygon tool is used to count the items contained within the job or a desired section of the job. When you click on the tool, the software will prompt you to click to add points to the map for a polygon, outlining the section you want to count.

<img src="img/polygonimg.png" width="600">

As items are surrounded by the polygon, a nodes, sections, and connections dropdown window will appear to the left. You can click on the dropdown to see a breakdown of the node and sections types and counts in the selected area, and a breakdown of the connection types and footages in the selected area.

Click on the “X” of the window at the bottom middle to cancel out the Tally by Polygon routine.

<br>
<br>

## **Copy Nodes**
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

## **Join All Poles**
<img src="img/joinpoles.png" width="60">

The Join All Poles tool is typically used in the **pre-design** or scoping step. If you hover your mouse over the tool, it will warn you that it should only be run once.

When you click the tool, it will add an aerial connection between each pole. However, it will string the poles together in a single line. So if your route should have breaks or branching, it may be best to use the conventional join tool found in the field toolset. Should you run it again, you will have multiple connections layered on top of each other connecting the nodes, so only run it once.

<br>
<br>

## **Show Un-Associated Photos**
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

## **Un-Associate Photos**
<img src="img\x.png" width="60">

If you had any errors in associating the photos, you can click the Un-Associate Photos tool to unassociate photos from the nodes and midspans/sections in the job.

<img src="img/uap.png" width="300">

When you click the tool, a window will appear in the center of the page. If you did have any photos where you have already manually moved or associated them, you can check the box to keep those photos at their current location.

<br>
<br>

## **Insert Sections**
<img src="img\triangle.png" width="60">

The Insert Sections tool will automatically insert a midspan section along all connections where no section currently exists.

    ⚠️ You should still be collecting midspans in the field. Marking “Done” in mobile is what actually places the section symbol (typically a blue triangle). This tool should only be used if you didn’t need to collect the midspan, but want to add dummy photos during the Cable Tracing process to assist in that workflow.

<br>
<br>

## **Address Data**
<img src="img\point.png" width="60">

You can quickly insert address data for locations on the map by using the Address Data tool.

When you click on the Address Data tool, the address data window will pop up to select various options. At the bottom you can select what address attributes you wish to add to the node locations.

<img src="img/addaddress.png" width="300">

With the "Add individual address attributes" checked, you may select or deselect the individual address attributes you wish to add. If you only have "Add 'Formatted Address' attribute selected, it will add a single "Address" attribute which contains the formatted address. The "Abbreviate State Name" will enter the state's abbreviation for the "State" attribute (if adding individual address attributes), otherwise the "State" attribute will have the full state name. Once you have the appropriate options selected, you have the choice to add to all nodes, add by node type, or manually select which nodes will get address data.

For most occasions, use the “Add By Node Type” to choose what node type will get address data.

Once you have the type(s) you wish, click “Get Address Data”. The software will automatically request address data on the desired locations. The address attributes will be added directly to the Node Info panel.

<br>
<br>

## **Fix Map Errors**
<img src="img\bandaid.png" width="60">

The Fix Map Errors tool is the band-aid icon in the toolset. This tool cleans up any corrupted data so that a job isn't prevented from exporting. Always get in the habit of clicking this tool before downloading exports, including PLA exports.

     ⚠️ If you have an underground project, save a snapshot of the job before running Fix Map Errors. This tool may delete faulty connections.

<img src="img\noerrors.png" width="300">

If there are no errors, a notification will pop up at the bottom left of the page. If there were errors, the notification will tell you the amount of data cleaned up.

<br>
<br>

## **Clear Warnings**
<img src="img\clearwarnings.png" width="60">

The Clear Warnings tool will remove the attribute “Warning” from all locations. In most cases, the "Warning" attribute is added to locations to provide any photo association warnings. This tool is clicked after you have fixed association errors and want to clear all the warnings at once (if you didn't already remove them manually one at a time as you fixed association errors).

<br>
<br>

## **Star Height Photos**
<img src="img\star.png" width="60">

Typically, when you associate photos you can auto-star height and midspan photos (as long as they have the "Midspan" or "Pole Height" photo chip on them). The Star Height Photos tool will allow you to run that again even after photos are associated. With this tool, you also have the option to star the first photo found if there is no height photo on the node or section.

<br>
<br>

## **Fix Company Names**
<img src="img\suitcase.png" width="60">

When you run this tool, you'll be able to change a company name found in cables and traces. For example, if you mistook one company for another while tracing, you could run this power tool to correct that everywhere that the incorrect company is annotated.

When this tool is run, the following window will display. It'll show you companies that are found in the job to the left, and your Company dropdown attribute to the right.

<img src="img\fix names.png" width="300">

<br>
<br>

## **Draw Polygon**
<img src="img\drawpolygon.png" width="60">

The Draw Polygon tool allows you to draw polygons inside Katapult Pro. The powerful aspect of polygons is the ability to not only edit the polygon, but any nodes/connections/sections inside it.


When you run the tool, you'll see a modal at the bottom of the screen telling you to click to draw your polygon. Once you're satisfied with your polygon and click "Create," you'll name it, give it a description (optional), update the color (optional), and select a layer to add the polygon (if there aren't any, you can quickly create one using the displayed "CREATE NEW LAYER" option). This layer is tied to the job.

<img src="img\createlayer.png" width="300">

The layer the polygon was added to is then turned on and off through the "Imported Layers" part of the map layers menu (bottom left corner of the software). In the above screenshot, the layer is called "Dillsburg Area," and is turned on since it's checked. (More than one polygon may be added to a layer.) The solid mouse icon next to its name indicates that it's selectable. This will allow me to edit the job or use the powerful job editing functions.

<img src="img\polygonedit.png" width="300">

Starting with the icons to the left underneath "Polygon Editing" and moving to the right, we have the following:

**Polygon Editing**
- **Edit Feature** - change the polygon's color, fill color, and border size
- **Edit Feature Points** - move the points of the polygon to edit its border
- **Copy Feature** - copy the polygon (you can choose to copy it into a different layer)
- **Delete Feature** - delete the polygon (this will not delete its layer)

**Job Data Tools**

These tools can be used on an entire job itself from the job's tools or settings. Using these tools on a polygon from its menu essentially allows you to run those functions on the polygon as if the polygon and its contents were a job in and of itself.

- **Multi Edit Attribute** - select an attribute from the picklist to either add, overwrite, or remove from multiple items inside the polygon
- **Multi Delete** - delete multiple design items within the polygon
- **Tally by Polygon** - count the items contained within the polygon
- **Copy Polygon Nodes to Job** - copy the items in the polygon to a job (existing or new)
- **Download by Polygon** - export information from items inside the polygon (same format choices found in the download manager)
- **Share by Polygon** - share items contained in the polygon with another company
- **Transfer by Polygon** - transfer items contained in the polygon with another company (a new job will be created with all the information contained within the polygon and then transferred)

<br>
<br>

## Bulk Pole Loading
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

## Offset Lines
<img src="img\offset.png" width="60">

This power tool will place reference lines on either side of a connection based on the offset input by the user. This can be useful, for example, for placing a visualization of the right of way of state roads.

Run the tool, click on the connection, and it takes care of the rest. The offset you're providing will be either north/south or east/west, depending on the general orientation of the connection you select to base the offset on.

<br>
<br>

## Notes
The Office Power tools were created by our developers and can not be edited in the Model Editor. You can remove tools you do not use or need from the Toolsets section in Model Editor, but if you need assistance modifying existing power tools, or want an estimate to create a power tool, reach out to ***support@katapultengineering.com***.

