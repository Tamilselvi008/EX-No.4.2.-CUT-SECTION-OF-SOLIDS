# EX No.4.2. CUT SECTION OF SOLIDS
## DATE:

## AIM: 
To create the solid model from given drawing and section the solid model

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

### A. Create the side-profile sketch

1. Open the Fusion 360 design and switch to the **Design** workspace.
2. In the **Solid** tab, select **Create Sketch**.
3. Select a vertical plane, such as the **XZ plane**. The goblet’s side profile must be sketched on a plane that contains its vertical center axis.
4. <img width="1920" height="1010" alt="Screenshot (146)" src="https://github.com/user-attachments/assets/ed3171e5-7e6b-4a55-b9eb-fb9762ace986" />

5. Choose **Create → Line**.
6. Draw the first vertical line, with a length of **1.501 m**. This establishes the main vertical extent of the profile. If this line is intended to be the revolve axis, make it a **construction line** by selecting it and pressing **X**.
7. <img width="1920" height="1007" alt="Screenshot (256)" src="https://github.com/user-attachments/assets/a1e7b0ee-bdc4-4310-8e35-fef988ead4ad" />

8. From the appropriate endpoint, draw a horizontal line of **1.366 m** to form the base’s width.
9. From the end of that horizontal line, draw a vertical line of **0.148 m**.
10. Draw a second horizontal line, parallel to the first, with a length of **1.366 m**. This defines the other side of the base profile.
11. Use the **Line** tool to draw the slanted segment from the base region toward the bowl. This line begins the goblet’s outer contour.
12. Use **Sketch Dimension** (`D`) to set the specified line lengths:
    - Select a line and enter **1.501 m**.
    - Dimension the horizontal base line to **1.366 m**.
    - Dimension the short vertical line to **0.148 m**.
    - Dimension the second horizontal line to **1.366 m**.
13. Apply sketch constraints to keep the profile aligned:
   <img width="1920" height="1014" alt="Screenshot (257)" src="https://github.com/user-attachments/assets/160534de-81d8-4b0d-866d-9f6dbae243a4" />

14. Choose **Sketch → Modify → Trim**. Click unwanted line portions that extend past the intended outline. Keep the segments needed for the foot, stem, and bowl.
<img width="1920" height="1031" alt="Screenshot (266)" src="https://github.com/user-attachments/assets/646cb08f-6874-45ec-b8a9-324dc25d3747" />

### B. Draw the bowl curves and close the profile

1. Choose **Create → Arc → 3-Point Arc**.
2. Create the outer bowl curve:
   - Click the point where the slanted side transitions into the bowl.
   - Click the point where the curve should reach the rim.
   - Move the pointer outward and click to set the arc’s bulge and shape.
   - <img width="1920" height="1014" alt="Screenshot (258)" src="https://github.com/user-attachments/assets/ee22ff5b-8b0f-49d6-9ca9-30061eeeba63" />

3. Create the inner bowl curve in the reverse direction, from the rim toward the lower bowl.
4. Keep the inner and outer curves separated by the intended wall thickness. 
5. Use **Line** to draw a short segment across the rim, joining the inner and outer curves.
<img width="1920" height="1014" alt="Screenshot (259)" src="https://github.com/user-attachments/assets/765b491c-066d-4b2e-b395-a089df8e81b2" />

7. Inspect the sketch:
   - Endpoints that should touch must be joined with **Coincident** constraints.
   - The cross-section must be closed so Fusion can revolve it as a solid.
   - Move the pointer over the profile. A closed region should shade.
8. If there are gaps, zoom in and use **Coincident** constraints to connect the endpoints. If extra segments remain, use **Trim** again.
9. Select **Finish Sketch**.
<img width="1920" height="1019" alt="Screenshot (269)" src="https://github.com/user-attachments/assets/6f69f74e-3c73-4d88-bb8d-b0d162f4800c" />

### C. Revolve the profile into a 3D goblet

1. In the **Solid** workspace, choose **Create → Revolve**.
2. In the Revolve dialog, click **Profile** and select the closed goblet cross-section.
3. Click **Axis** and select the vertical construction line through the center of the goblet.
   - If you did not make a construction line, select the vertical sketch line that represents the goblet’s center axis.
4. Set **Angle** to **360°**.
5. Set **Operation** to **New Body** if this is the first solid in the design.
6. <img width="1920" height="1004" alt="Screenshot (262)" src="https://github.com/user-attachments/assets/38320c79-1ddc-4dc6-9655-ea27396cb880" />
<img width="1920" height="1007" alt="Screenshot (263)" src="https://github.com/user-attachments/assets/839f763d-3efa-4831-a369-f4b7be4df763" />

9. Click **OK** to create the 3D model.

### D. Round the top and bottom edges

1. Choose **Modify → Fillet**.
2. Select the intended top edge of the goblet and the intended bottom edge of the foot. Rotate the model or zoom in if necessary to select the circular edges accurately.
3. Enter the required fillet radius. If you do not have a specified radius, increase it gradually and watch the preview.
<img width="1920" height="1006" alt="Screenshot (264)" src="https://github.com/user-attachments/assets/c62bc731-e16c-4aa4-810b-85ddfaf41f32" />

5. Click **OK** to apply the fillets.

### E. Create the 2D drawing

1. Save the 3D model.
2. From the design workspace, choose **Design → Drawing → From Design**.
<img width="1920" height="1020" alt="Screenshot (268)" src="https://github.com/user-attachments/assets/b132c453-7f43-466a-81a2-cecd98596391" />



5. Place a front view that clearly shows the goblet’s height and profile.
6. Place a top view to show the circular rim and foot.
7. Add an isometric view to show the overall 3D shape.
8. Use **Dimension** tools to add the required measurements, including the overall height, base width, stem dimensions, bowl dimensions, and wall thickness where applicable.
11. Save the drawing and export it in the required file format.


## INPUT:

![image](https://user-images.githubusercontent.com/113594316/199409656-c021c100-857a-4ae4-9752-9ae59465c9c2.png)

## OUTPUT:
<img width="1920" height="1004" alt="Screenshot (254)" src="https://github.com/user-attachments/assets/61899540-0d62-4ef4-aabe-e122f742123c" />


## RESULT:
Thus, the cut section for solid model is created.


