These tests are designed to mitigate harm and ensure patient safety during operation.
These are suggestions and a work in progress and require further specification... please suggest/edit/add/comment, etc...

NOTE:

1. These tests should be performed on swabs that have *already undergone sterilization*.
The sterilizaiton process (e.g. autoclave) may affect material properties of the swabs.

2. These tests should be performed at various temperatures (freezing and room temperatures).
Drive-through clinics can have the swabs sitting in freezing conditions.
Indoor hospital can have the swabs at room temperature.


# Mechanical Testing Procedures
1) static load breaking test (represents bending the swab - shouldn't shatter, and should break at break-point)
   - fix proximal end of swab (hand side)
   - apply static load to distal end (absorbent side)
   - measure angle and load at which breaking occurs
   - note location of where breaking occurs (e.g. at snap-point or on neck or bulb)
   
2) axial load deformation/breaking test (represents pushing against an obstruction)
   - fix distal end of swab (absorbent side)
   - starting from 0, increase axial load to proximal end of swab (hand side)
   - measure load at which swab plastically deforms or breaks
   - measure where breaking occurs (e.g. at snap-point or on neck or bulb)

3) dynamic load breaking test (represents patient recoil of head)
   - fix proximal end of swab (hand side)
   - apply static load to distal end (absorbent side)
   - measure breaking with load
   - measure where breaking occurs (e.g. at snap-point or on neck or bulb)
   
4) bending plastic deformation test (represents any curvature the swab faces in nasopharynx)
   - fix proximal end of swab (hand side)
   - apply static load to distal end (absorbent side)
   - release load and allow swab to "relax"
   - measure deformation angle of "relaxed" swab with load
   - ensure swab bends and flexes less than maximum angle and more than maximum angle
   TODO: *specify maximum angle-per-load constraints*

5) elasticity test - spring-back (represents slight bump that swab has to go over when inserted)
   - fix proximal end of swab (hand side)
   - apply static load to distal end (absorbent side)
   - release load and allow swab to relax
   - measure deformation angle of swab
   - measure bending angle with load
   - ensure swab bends and flexes less than maximum angle and more than maximum angle

6) rotational test - turn until failure (this is to simulate the tip getting stuck/caught while the swab is being rotated in the nasopharynx) 
   - fix distal end of swab (absorbent side)
   - apply rotation (torque) to distal end (hand side)
   - measure torque-theta profile
   - measure number of rotations until failure/breakage
   - measure point of failure 
   - note maximum torque until plastic deformation
   
7) rotation test in curved tube (to simulate turning of the swab in the nasopharynx after being bent)
   - use a bent piece of tubing (like surgical tubing, but fixed in shape (3d print one?)
   - insert distal end of swab into tube up to breakpoint
   - apply rotation (torque) to distal end of (hand side)
   - measure torque-theat profile over the course of multiple turns
   - note maximum torque

8) tip abrasion 
   - measure dry weight of swab
   - place distal end of swab (absorbent end) next to simulated tissue (todo: spec pressure and material (e.g. moist chicken?)
   - apply rotation to distal end (hand side) at hand twirling speed (60 RPM?) for 10 seconds
   - remove swab and wash and dry
   - measure new dry weiht of swab
   - note difference in swab weights (to measure wheter / how much tip has abraided)
   
9) tip crushing 

10) cycle loading

# Absorption Testing Procedures
Use food coloring and viscous solution (match nasopharyngeal fluid viscosity => glycerine / honey? TODO: find good mix)

1) absorption test (to test how much fluid is absorbed by swab)
   - measure swab dry weight using a microgram scale (tare with a plate)
   - fill a glass/vial/beaker with fluid (ideally match nasopharyngeal fluid viscosity > water)
   - dip swab until tip into container
   - pull swab out
   - measure swab wet weight using a microgram scale
   - record difference in swab weights
   
2) absorption & release tests (to test how much fluid is absorbed and then released by the swab into reaction chamber)
   - measure dry weight
   - measure 
   
OTHER METHODS   
   TODO: *quantify absorption of current swabs and test against current/old standard*
   method #1 with water, narrowest graduated cylinder you can find or tape a ruler/measuring tape to a test tube
   - fill tube with a known volume of water, note initial volume from bottom of the meniscus
   - slowly submerge the entire tip (all of the swabbing features) into the water, keep submerged for 5s, slowly withdraw
   - repeat for total of 10 swabs
   - measure the change in height of the water level, calculate total volume absorbed and average volume absorbed by each swab
   
   method #2 with water, wax paper/parafilm, microbalance (biology or chemistry labs should have one, some mechanical labs) [video](https://drive.google.com/file/d/1JOp8rVTZRIyFNDBDuPVH94QhuYIPi7Vu/view)
   - crease the wax paper so water will sit in the middle
   - place the paper on the microbalance and add ~1ml of water. Tare the balance
   - Hold the swab horizontally above the water droplet.  Slowly lower the swab into the droplet of water and rotate 180 degrees in both directions, ensuring the swab is completely submerged into the droplet and stays submerged for 2 seconds then slowly raise the swab to remove it from the water
   - repeat for a total of 10 swabs
   - record the amount of water removed from the scale and calculate the amount abosorbed by each swab.
   <img src="swab measure absorption weight.PNG" width="50%">

# Biological/Chemical Testing Procedures
1) test that swab absorbs viral RNA particles
2) test that swab does not interfere with PCA/reagents
   
# Sample Collection Testing Procedures
1) with Methylene blue stain solution
   - do cheek swab (try to air out mouth and pick a less saliva-coated part of the cheek) or NP swab
   - smear onto a glass slide
   *if the smear doesn't result in any visible material left on the slide, place 50ul of buffer solution (saline, PBS, EPA water, etc) on the slide and roll the swab around in the buffer, dragging the liquid around the slide surface. [Video here](https://www.dropbox.com/s/coizu1qvzxpvwau/cheek%20swab%26stain%20w%20methylene%20blue%20for%20spiky%20swabs%20using%2050ul%20buffer%20to%20wet%20swab.mp4?dl=0)
   - add 2 drops (~80ul) of methylene blue solution to the slide
   - cover with a cover slip and image
   - epithelial cells and bacteria should be visible under 4-10x magnification
   <img src="methylene blue NP swab 3xview.PNG" width="40%">
   
