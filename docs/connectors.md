# Add Connectors Between Your Class Blocks

Once you have created all the class blocks for your diagram, the next step is to add arrows and other connectors to denote the relationships between classes. There are two ways to add those connectors in draw.io, you can either create a new connector starting from one class block and customize it to the style you need to mark a particular relationship, or you can use the prebuilt connectors from the UML section of the Shapes panel. Since it's sometimes easier to manage the connection points with custom arrows, this page will start by teaching you how to make custom connectors, and then briefly touch on using the prebuilt connectors.

## Using Custom Connectors

1. **Select** connection as the default line type from top bar, if it is not already.

![](./assets/default_connector.png)

2. **Select** your preferred default line shape from top bar. 

![](./assets/default_line_shape.png)

!!! note

     For a UML Class diagram, you are most likely to want bent lines (which draw.io calls "Waypoints") or straight lines. The shape of any line can be changed later.

3. **Hover** over the class block you want to start from to see its connection points.

!!! note

     While the block is selected, you can only see the large arrows. These arrows will create connections with the middle of the side of the class block that will automatically switch sides if you later move the connector around. **Deselect** the class block to see all the available connection points. The x's along the block edge will create more specific connections that will stay in place unless you move them. 

![](./assets/hover_points.gif)

4. **Click** a connection point and **Drag** a connector to the class block you want to point to.

5. **Hover** over second class and **Release your Drag** when  the connection point you want is highlighted.

!!! note 

     The green line highlight allows connection to any point, while the blue line highlight connects to a point along a side, but will automatically switch sides of the block as you move things around.

![](./assets/connect.gif)

6. **Click** on a line to select it.

7. **Click and Drag** line segments to arrange the line into the desired shape. A line segment will only move parallel to its direction. Lining up parallel segments will automatically remove bends, while moving end or connected block can add bends.

![](./assets/move_line.gif)

8. *Optional:* **Double Click** a line to add attached text.

!!! warning
     Text added this way will be bound to the line and move with it, even if you move it away. More importantly, if you duplicate text attached to a connector via **Right Click** --> [Duplicate], the duplicate also remains bound to that connector even if you move it away. Use **Right Click** --> [Copy] and **Right Click** --> [Paste Here] to avoid this. See [troubleshooting](troubleshooting) for how to handle if things move unexpectedly when you move other things.


9. **Select**and **Drag** the text box to move it for readability, or use the arrow keys on you keyboard for fine maneuvering.

![](./assets/add_line_text.gif)

### Adjust Connector Atttributes

Once you have created a connector you can adjust its appearance in the Style tab of Format panel to create any of the arrow styles used to denote different relationships in UML diagrams.

1. **Click** the [Pattern] selector to change the solid line to a dashed line.

![](./assets/line_pattern.gif)

2. **Click** the [Line Start] selector to change the line head shape.

3. **Click** the [Line End] selector to change the line end shape.

![](./assets/change_line_ends.gif)

4.  **Increasing/Decrease** the px number in the right-hand input to adjust the line start/end size.

![](./assets/line_ends_sizes.gif)

## Using Prebuilt Connectors

For the more complicated connector styles, it may be easier to use the prebuilt connectors.

1. **Click and Drag** the desired connector from the UML section of the Shapes panel to the canvas.

2. **Connect** each end of the connector to the desired block as in steps 4 and 5 of the instructions for using custom connectors.

3. Continue with the custom instructions for arranging arrows.

When you added all you connectors, you can [export your completed diagram](export).