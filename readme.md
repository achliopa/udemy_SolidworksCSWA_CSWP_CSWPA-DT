# Udemy Course: SOLIDWORKS: Become a Certified Associate Today (CSWA)

* [Course Link](https://www.udemy.com/solidwokrs-go-from-nothing-to-certified-associate-level/)
* [Course Repo]()

## Section 1 - Starters and Course Overview

### Lecture 3 - What is SOLIDWORKS?

* SolidWorks (stylized as SOLIDWORKS), is a solid modeling computer-aided design (CAD) and computer-aided engineering (CAE) software program that runs on Microsoft Windows. The SolidWorks is produced by the Dassault Systèmes.
* SOLIDWOKRS is reportedly used by more than 3.5 million users around the world.
* [This video](https://www.youtube.com/watch?v=ogKYHcprYlU) explains what is SOLIDWOKRS.

### Lecture 4 - Exploring the Benefits for SOLIDWORKS Certifications as a User!

* Take a look at this [video](https://www.youtube.com/watch?v=mHoNakua8rM) which discusses the benefits of having SOLIDWORKS Certificates. The video is centred around the companies [ULC Robotics](https://ulcrobotics.com/) and [MakerBot](https://www.makerbot.com/). However, the same could apply for lots of other companies.

## Section 2 - Basic SOLIDWORKS Interface and Navigation

### Lecture 7 - Starting a New Part

* New file => Part => Ok

### Lecture 8 - Know about the Command Bar, Canvas and Design Tree

* we open the model from courseRepo 'Interface and Navigation model_2013.SLDPRT'
* on top we have command bar: it has all the commands we need to create our model
* in the middle we have the canvas with the model we are working on. on top it has commands related with viewing the model like display style
* on bottom left of canvas we see the 3 axes (x,y,z)
* on the left we have the design tree (all the features and sketches that compose the model)

### Lecture 9 - Adjusting the Document's Measurement Units

* all our solidworks models are based on actual units.
* we set the prefered units in bottom right of bottom menu bar. 
* if we dont like the options we can choose 'Edit Document units' making our custom units

### Lecture 10 - Utilizing the Mouse for More Efficient Models Control and Creation

* RCLICK on canvas, design tree or command menu: more options 
* LCLICK on canvas => mouse scroll = zoom in/out (use cursor as center of movement)
* CLICK+HOLD mouse scroll button => move mouse = 3d rotation

## Section 3 - Let's Start Sketching

### Lecture 13 - Select a Plane to Sketch on

* Sketching is the first step towards creating a 3D model
* We must select a plane to sketch on from design tree. 
* solidwork provides we have 3 basic planes (top, front, right)
* we select top plane => sketch tab => sketch command (OR when clicking plane select sketch option)
* to exit sketch mode select the command of icon on canvas
* in sketch mode we have several sketch related command sin command menu

### Lecture 14 - WATCH OUT!! Always Link your Sketches to the Origin

* when in sketch mode we see the origin (coordinates 0,0) as 2 intercecting red arrows
* we must always have our sketch linked to the origin (fully defined)
* for circle is good practice to make the center of the circle the origin
* always start sketching from the origin

### Lecture 15 - Sketching Basic Shapes Part 1 - Rectangles and Lines

* when in sketch mode the command menu has all available shape
* we select right plane and sketch
* we click line move to irigin and start adding cascading lines. sanp lines are avaialable and indication on vertical and horizontal. to stop drawwing lines DOUBLECLICK or ESC
* we close our polyline to origin (only two lines are fully defined)
* we use the rectangle option to scetch a rectange (there are various types avaialble)
	* corner rectangle. select one corner and move opposite corner
	* center rectangele. select centrer point and expand moving top right corner (rest is symmetrical)
* any complex shape can be broken into simpler shapes

### Lecture 16 -  Sketching Basic Shapes Part 2 - Circles, Arcs and Ellipses

* select top plane and sketch
* we draw a standard circle (center on origin and expand on radius) ESC to stop
* we sketch an arc (centerpoint arc). we seletc the center (of imaginary circle.) then the radius of the imaginary circle and then start drawing the arc along the perimeter
* to delete a sketch (exit sketch => delete)
* to sketch an elplse we click it in command menu => select center then define the main radius and then the secondary. 
* where we do the second click is th max radius point

### Lecture 17 - Using Dimensions (Distances) to Define Your Sketch

* we will implement a rectangle of 6in wide and 4in height
	* set doc to inches
	* we draw the rectangle (start from origin) on top plane (dimensions dont matter)
	* click smart dimension
	* click on line => drag dimension => release mouse => enter desired dimension (and optional units)
* a rectangle that is dimensioned and anchored (or with set dimensions) from origin is black lined (fully defined)
* to be able to move or resize need to remove the dimension or the anchor to origin respectively
* we draw a circle. again i  click smart dimension => click on perimeter => enter dimension. its fully defined as well (center anchored to origin)
* we will sketch and dimension an elipse 25mm height and 70mm wide on top plane
* change doc to mm
* draw the elipse
* unlike the circle smart dimensiong => click on param does not trigger dimensioning
* the  way to add dimensions on an ellipse is to click on each diameter (small and large) end points which trigger dimension for each
* ellipse is not fully defined with these 2 dimensions. it needs a 3rd (the distance ox x or y axis between an endpoint of large axis and small axis or center). the condition is to not be on same horizontal or vertical
* this is because i can rotate the elipse althoug anchored and axis defined
* if i try to add more than necessary dimensions. i get a warning. the sketch will be overdesigned. if i keep not necessary dimensions.. they are grey in color

### Lecture 18 - Yes, we can use Angles too!

* in previous lecture we used dimensions to define our sketch
* we want to define a triangle of 100mm base with left angle 60o and right andle 80o
* i draw a triangle with 3 lines. i dont care about size or angles
* click smart dimensioning and set base line to 100mm
* to dimension angle i click on both side lines then i see the angle dimension
* i define both sides angles and my triangle is fully defined (origin is anc)

### Lecture 19 - Using Relations to Define your Sketch Part 1 - Between Lines and Points

* Relations we will go through:
	* Horizontal
	* Vertical
	* Merge
	* Midpoint
	* Coincident
	* Parallel
	* Perpendicular
	* Equal
* Relations are ways to define parts of the sketch by linking them to each other or the sketch plane
* **Horizontal & Vertical Relation**
* in sketch mode we add to random lines (not related)
* the hor or ver relationship is regarding to the plane axis
* if i click on a line in properties (left menu) i see 3 relationships (ver hor fix)
* clicking on one is added on existing relations and is applied (added as green icon)
* if i move the line it moves holding the applied relationship
* if i click on one point + CTRL + Click on the other line point i get more relations options (point-to-point) regarding the relationship of one to the other. I chose vertical (both points on same vertical line)
* so my 2 lines are bound to each other by this point2point relationship
* **Merge,Midpoint,Concident**
* clicking on 2 points (on different lines) and chosing merge relationship merges both points to 1
* I click on a lines point + CTRL + click on line. i get point to line relationships (midpoint or coincident)
	* midpoint places the point to the middle of the line. moving the poiint or line maintains the relationship
	* coincident places the line to a place so that if it expands on its direction it will meet the point
* **Parallel,Perpendicular**
* we add 2 lines . click on both (using CTRL) to see the line-to-line relationships. 
* i select parallel. if i move one the other maintains the relationship
* if i choose perpendicular both are vertical one to the other
* if i choose equal the will have equal size to each other
* to fix regarding origin. i click a line and orign and click concident 

### Lec 20 - Using Relations to Define Your Sketches Part 2 -Between Circles, Ellipses, Lines

* we will implement a sketch composed by 4 circles 2 elipses and 3 lines.
* we will apply relations: horizontal, vertical, tangent, cocentric, equal and coincident
* we start at front plane
* we draw the elements without caring on relations or dimensions
* we start setting the relations between circles
* click 1st cricle CTRL click 2nd curcle => apply Cocentric. both now share the same center. we do the same for other group
* outer circles are equal. so i click on both (CTRL) and set equal. same for inner circles in both groups
* outer circles must be tangent to each other (touch)
* centers are horizontal (click on both and add horizontal)
* distance between circles is .5 inches. we add smart dimension (click on one circle perimeter then click on the other)
* right outer circle is tangent to right line (click line and circle and apply Tangent rel) do the same for left
* we want end of line on both sides to be coincident with circle perim. click end of line and circle perimeter apply Coincident. do it both sides
* elipses are cocentric. we apply the rel
* outer elipse is tangent to both circles. y apply tangent between elipse and each of the 2 circles (2 relations)
* elipses large axis are horizontal. we select all points of minor azis and make them horizontal
* major axis points on both elipses are coincident
* other point is midpoint on horizontal line. we apply the rel
* we apply smart dimension between two elipses minor axis points (.5in)
* i fiz bottom left corner to origin
* left line is 5in (add smart dim). bottom same (equal rel)
* we see in sample that center point of circles is in same vertical with outer elipse midpoints
my design is fully defined

### Lecture 21 - SOLIDWORKS Applying Relations Automatically!! How does that work!?

* solidworks adds relations automatically while we sketch
	* horizontal
	* vertical
	* coincident
	* midpoint
	* tangent 
	* cocentric
* we scetch or right plane
* if i start a line from origin i get concentric relation 
* yellow rel color is a rel currently applied (temp) once i finish the element it becomes permanent 
* if i move a line horizontaly or veritcaly i get these relatios to the plane for free
* if i drag a new line point on an existing line i get coiccident rel available. when i pass from middle point of existing line i get midpoint
* if i draw an area element (circle) and touch the line i get tangent rel 
* if i start a new circle with same center i get cocentric relationship

### Lecture 22 - Knowing and Deleting Active 

* if we get a sketch with a lot of relationships we want to kow about them.
* in sketch mode if i click on an element in the proiperties i see the applied relationships. if i click on one i see the element or point it is applied with highlighter. in the list i can delete relationships
* if i highlight all sketchj in the properties i see all applied rels
* if i hover on a rel icon i see the involved entities

### Lecture 23 - Additional Lines: Construction Lines and Center Lines

* a centreline is available in command menu as an alt line
* construction geometry is used to assist in creating the sketch entities and geometries. they are ignored when the sketch is used to create a feature. Some call them construction lines while others  call them centerlines
* say we want to draw 4 circles centered on 4 tips of a square. we dont want the square to be visible or contstructed
* we draw a square centered around the origin and apply equal rel
* then i draw 4 circles around each edge. i apply equal rel to all of them
* we are ready relation whise. we dont want to show the rect as constre element
* if we delete them we will lose the relationship
* i select all 4 lines and in properties bottom click 'for constrution'. rect is now dashed

### Lecture 24 - More Sketch Commands: Mirror, Offset, Patterns and Trim

* In this lecture we will learn additional comands that will help us sketch faster and easier:
	* Patterns
	* Trim
	* Mirror
	* Offset
* we will sketch a  sawtooth like shape which has a lot of repetition and symmetry
* we select right plane and sketch two angled lines
* we add a vertical relation between the external point of the angled line and origin
* between the external point of the vertical line and origin we add a horizontal relation
* between origin and vertical point i add a dim of .5in from horizontal point to origin 1.5in
* we set a dim to angle between lines of 45deg
* our base shape is fully defined.
* in the template the base set repeats 4 times on each direction.
* we will use the 'Linear shape  Pattern' command from sketch command menu
* in the properties (left menu) we click into the box entities to pattern and turns red. we then select the elements to add to the pattern (2 lines)
* we add the repetition count to add on X-axis (horizontaly) to 3 (instance-count)
* we then add dimension x spacing to 1.7in (we can also drag the line)
* we click OK 
* if i dont click fix the axis direction our other 3 shapes are not fully defined. i can move the pattern up or down (individual patters are connected with pattern rlation)
* to fully define it manually i add horizontal relation between first point of 1st to 2nd shape. i also add point to vertical line a coincident relation
* we draw a horizontal line to origin
* i want to remove 3 small vertical lines. we ll use 'Trim Entities' command from sketch
* with "PowerTrim" option i select an area to trim. or i can us it as cutting line. whatever touches it gets trimmed
* our whole sketch is reflected on the other side (vertical mirror) and use 'Mirror Entities' to do it. before we do it we need a mirror line
* we add a centerline vertical on origin
* we click 'Mirror Entities' and select the entities to mirror (thy get added in the list in options)
* we click mirror about and select the celnterline. it mirrors and we click ok
* the final sketch has the saw linewith an offset difference
* we select 'Offset Entities' command and set distance to ,3in
* we then select our sketch. we see an outside equal shape with offset is added. we click OK
* our sketch is final and fully defined

### Lecture 26 - Teaser to the next Section: GOING 3D

* in next section we move to 3d working in Features tab
* we can use extrude to add the 3rd dim

## Section 3 - Let's Start Applying Basic Features

### Lecture 30 - Our First Features: Extrude Boss, Cut Extrude, and Fillet

* we will design the 3d cube of '/courseRepo/lec30-Extrude-Cut-And-Fillet.PNG'
* We will use first the **Extruded Boss** command from Features tab: it pushes outa 2d scetch into the 3rd dimensionadding material
* **Extruded Cut** cutts the 2d sketch into the 3rd dimension removing material from the outside extruded shape
* **Fillet** rounds sharp edges
* To recreate the cude we need to plan our steps:
	* extrude boss
	* cut extrude
	* fillet
* we create a new part. we select the top plane to sketch
* we draw a center rect around the origin and add equal relationship to make it square
* we make the side 5in
* our sketch is fully defined. we exit and hit Feature tab and click Extrude Boss. according to the draw the height is 5in so we set in props dim 5in and hit OK (our extrude type is Blind so 1dir)
* we move to Step2. we select a plane. with box created we have 6 planes. each side can be used as a plane. we have still the 3 original planes of the canvas
* if i select a side of the cube i can edit a sketch of it
* i click on top side of box and select sketch command. the origin appears but i am in 3d orientation. from orientation menu i select top (or in design tree click on sketch) and click 'Normal To'. ia m now in 2d. i draw another square around origin of size 3in. it is fully defined
* i exit the sketch and select Features => extruded cut
* i play with orientation to see it in 3d. i set dim to 5in and hit apply (I can use Through all instead of Blind) to cut all
* For fillet i choose 'Fillet'. i have to select items to fillet and then fillet params
* in items fillet i put edges to fillet. i select inner and outer square lines as edges. i rotate and select on the bottom side the edges
* as all edges are on one surface. if i click on the surface all edges are selected (in list it appears as Face). 
* according to the template the radius is .25in. we set it in Fillet Params

### Lecture 31 - Let us Edit and Delete Features.

* 