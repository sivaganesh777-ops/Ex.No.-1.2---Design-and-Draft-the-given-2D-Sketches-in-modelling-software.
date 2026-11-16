# Ex.No.-1.2-Design and Draft the given 2D Sketches in modelling software.

## AIM
 To sketch the given drawing with dimensions using fusion 360 tool.
 
## REQUIREMENTS
 1. Autodesk fusion 360
 2. Windows 10
 3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
 4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
 
 ## PROCEDURE
 
 Step 1 – Set Up Reference Axes and Base Grid
 
   1. First, draw the main vertical and horizontal centre lines so that they intersect at the origin (0,0).
   2. Offset the vertical centre line 50 mm to both the left and right sides to create two parallel lines at X = -50 mm and X = +50 mm.
   3. Similarly, offset the horizontal centre line 60 mm upwards and downwards to create lines at Y = +60 mm and Y = -60 mm.
    
Mark the six outer hole centres at the following coordinates:

  Top-left: (-50, 60)
  
  Top-right: (50, 60)
  
  Middle-left: (-70, 0), 20 mm further left from X = -50.
  
  Middle-right: (70, 0), 20 mm further right from X = +50.
  
  Bottom-left: (-50, -60)
  
  Bottom-right: (50, -60)
  
Finally, check that all six hole centres are correctly positioned according to the given dimension

 <img width="466" height="390" alt="Screenshot 2026-11-15 095416" src="https://github.com/user-attachments/assets/81bb07d7-5087-4f74-85a3-629cf2ac37d7" />


Step 2 – Draw Central Geometry

   1.From the centre origin (0,0), draw the innermost circle with a radius of 16 mm (R16).
   
   2.Draw three more concentric reference circles with radii of 21 mm (R21), 32 mm (R32) and 40 mm (R40).
   
   3.Draw two vertical parallel lines through the centre, keeping them 3 mm away from the centre line on both sides (X = +3 mm and X = -3 mm). 
      This creates a total gap width of 6 mm.
      
   4.Construct six radial slots or spokes within the circular region between R21 and R32.
   
   5.Make sure all circles and the central web pattern are properly aligned with the origin.

<img width="697" height="587" alt="Screenshot 2026-11-15 095952" src="https://github.com/user-attachments/assets/6689d110-4146-4950-b7f2-86fbec8eeea3" />

  
   Step 3 – Construct Outer Circular Features
   
       1. Draw circles with a radius of 15 mm (R15) at all six outer hole centres.
       
       2. At the top-left, top-right, bottom-left and bottom-right positions, draw outer arcs with a radius of 21 mm (R21).
       
       3. At the middle-left and middle-right positions, draw concentric outer circles with a radius of 20 mm (R20).
       
       4. Check that all six circles are properly aligned with their respective centre points.

   Step 4 – Connect Tangent Lines and Fillets
       
       1. Draw straight tangent lines connecting the top-left and middleleft outer arcs.
       
       2. Similarly, connect the bottom-left and middle-left arcs using straight tangent lines.
       
       3. Repeat the same process on the right side by connecting the top-right and middle-right arcs,
         followed by the bottom-right and middle-right arcs.
       
       4. Create internal fillets with a radius of 20 mm (R20) between the top-left and top-right outer arcs,
          ensuring they connect smoothly with the central R40 boundary.
       
       5. Repeat the same fillet construction at the bottom by connecting the bottom-left and bottom-right outer arcs.
       
       6. Finally, check that all tangent lines and fillets are smoothly connected without any gaps or overlaps.
       

   <img width="697" height="587" alt="Screenshot 2026-11-15 095952" src="https://github.com/user-attachments/assets/f42aebe2-059b-4cd8-a8c0-e80f30557df5" />


    Step 5: Final Cleanup & Dimensioning 
       
       1. Trim all overlapping construction geometry to leave a clean outer boundary and inner features.
       
       2. Apply centerlines, dimensions, hatch/shading, and radius annotations matching the technical drawing.
       


 ## OUTPUT

   <img width="971" height="707" alt="Screenshot 2026-11-15 151056" src="https://github.com/user-attachments/assets/6a6387a2-0c90-4d4a-9d11-814d4a659a7b" />

   <img width="858" height="507" alt="Screenshot 2026-11-15 102226" src="https://github.com/user-attachments/assets/e5343364-af13-46e9-9568-7a59f36d1ec4" />




 
 ## RESULT
 Thus the given sketch is drawn and drafted using fusion 360 tool.
