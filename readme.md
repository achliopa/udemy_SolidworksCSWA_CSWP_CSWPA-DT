# Udemy Course #1: SOLIDWORKS: Become a Certified Associate Today (CSWA)
# Udemy Course #2: SOLIDWORKS: Become a Certified Professional Today (CSWP)
# Udemy Course #3: SOLIDWORKS: Become a Certified Drawing Specialist Today

* [Course #1 Link](https://www.udemy.com/solidwokrs-go-from-nothing-to-certified-associate-level/)
* [Course #2 Link](https://www.udemy.com/solidworks_pro/)
* [Course #3 Link](https://www.udemy.com/solidworks_drawing/)

# Course #1: SOLIDWORKS CSWA

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

## Section 4 - Let's Start Applying Basic Features

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

* we will take model from previous lecture and start editing the features 
* we have 3 active feats so far
* we click on boss extrude feat and click 'edit feature'
* we increase distance to 7in
* we edit fillet feature. we change radius and delete face1 from applied items
* we can even edit a sketch  wwe used to create a feat
* selecct a feat => expand => select the used feat => edit sketch
* changing the sketch makes the feat change as well
* to delete a feat RCLICK => delete. it deletes dependent feats but not he underlying sketch (by default)
* if i delete a base feat all the dependencies are deleted

### Lecture 32 - Let us do Chamfers now

* a chanfer is a way to remove sharp edges using an angled slope
* is like fillet but fillet is rounded. chanfer is straight
* we delete fillets
* in command menu in Fillet we click the drp down and select Chanfer
* we add the 2 faces to list
* we select chamfer type
	* in 'angle distance' we spec angle and distance
	* in 'distance distance' we spec 2 distances from the edge (symmetrical we spec 1)
	* in 'vertex we select a point (edge)' and define3 distances for a triangle around it

### Lecture 33 - Let us Practice our First Features!

* we will implement th drawing of 'lec33-Practice-Extrude-And-Chamfer-Drawing.PNG'
* we plan the creation of the drawing
	* extrude boss
	* chamfer around
	* chamfer edge
	* extrude cut holes
* select top plane for sketch
	* create the arc with center on origin
	* add 3 lines for rectangle
	* add dimensions. (radius, length of horizontal)
	* our sketch is fully defined. exit and extrude boss for 0.5in
* apply chamfer
	* on top face (except on edge)
	* distance -distance (.25height,.5 length according to drawing)
* apply chamfer on distant edge 
	* (distant distant 3/8in height 1.25 inch length)
* add 4 holes
	* select top face
	* sketch
	* click on sketch on design tree => normal to
	* add one circle
	* center of circle with origin (add horizontal rel)
	* add distance between circle  center and external a rc (1.25)
	* add smart dir for diameter (5/8)
	* circle is fully defined.
	* circle is repeated 4 times horizontally. 
	* i add linear sketch pattern X axis , 4, distance 1in
	* i fix distance and axis (my sketch is fully defined)
	* exit sketch => feature => extrude cut => through all

### Lecture 34 - Design Priorities_ A point in Design Intent

* we will address apoint in design intent. design priorities
* we will impleemnt apart in two ways and see how a change in dimensions affects each one
* implementation:
	* create a new part => go to top plane => sketch => corner rectangle from origin => add equal rel to 2 lines (square) => set smart dim to 6in
	* exit sketch => apply extrude boss 1in
	* select top face => sketch in design tree => normal to => draw circle ) => smart dim of diameter (1in). there are 2 ways to set circle to center
* 1st option: set smart dim of 3in betweencircle center and hor line and ver line of rectangle (fully def) => do the througout cut. If i change the square dim the circle (hole) wont be in the center anymore
* 2nd option: use centerlines to connect square points. in the intersecting point draw the circle (no dimensions  just relations). resizing the square creates no issues
* Set design priorities . think of the future. design accordingly

## Section 5 - Let's Start Applying more Complex Features

### Lecture 38 - The Features: Revolved Boss and Revolved Cut!

* we will implement 'lec38-Revolve-And-Revolve-Cut-' and 'lec30-Ball' parts
* Revolve Boss: Adding material by revolving a shape around a revolution axis 
* Revolve Cut: Removes material by revolving a shape around a revolution axis 
* a ball is a revolved D shape (half circle arc)
	* selct front plane
	* add sketch and draw an arc around circle + line
	* we can use the line as revolution axis
	* we exit sketch => go to feat => revolved boss => 360deg => set line as revol axis
* we can set direction of boss
* to do the next model: revolve boss => revolve cut => extruded cut
	* select front plane => draw rectancle => add dimensions => exit sketch => feats => revolve boss => select revolve line => 360deg => ok
	* select right plane => sketch => normal to => draw a square => dimension it => add a centerline as revolution line in the mid point of top and bottom. attach square to side (collinear line2line rel). => add a centerlin in square middle => set dimension from the top => it is now fully defined => exit sketch => feats => revolve cut => select revolve line on centerline
	* select front plane => sketch => edit => normal to => draw rect => dimension it > add centerline to face => midpoint coincident to centerline. rect dimension to top face => our sketch is fully defined => exit sketch => feats => extrude cut => through all both (both sides of plane) => ok

### Lec 39 - The Features: Swept Boss and Swept Cut

* we will model 'lec38-Revolve-And-Revolve-Cut'
* Sweep Boss: Adding Materials by sweeping shape through a designated path.
* to apply it to the sample model we need to use 2 sketches. one on each plane
* Sweep Cut: Removing materiasl by sweeping a shape through a designated path
* Plan for modeling the object: Sweep Boss => seep cut
* As we said to apply this feat we need 2 sketches on different planes. one reresetns the profile and the other the path (extrusion follows the path)
* Draw path: front plane => sketch => draw to parallel lines and one tangent arc => add dims and rels make it fully defined
* Draw profile: on right plane => sketch => draw elipse. dimension it => exit sketch
* Sweep boss: feats => swept boss. select profile add to profile slot in props .  select path and add it to path list in props => apply feat
* swept cut: select profile ==> sketch => normal to => add xircle => dienson=> xit sketch => features => swept cut => select circle as profile path as path apply. path is not seen.... => in canvas i have a part tree +. in sept boss select the sketch of the path APPLY
* to confirm that cut goes all in. i select in canvas Section view and drag it

### Lecture 40 - Reference Geometries: Making new Planes other than Base Planes and faces!

* in this lecture we will learn how to make planes that are
	* different than the base FRONT, RIGHT and TOP planes
	* different than other existing faces from features
* What specifies a plane? (Views of a model to sketch upon) 
* To specify a plane:
	* 3 points (vertices)
	* a line and a point (an edge and a vertex)
	* 2 lines (edges)
	* other planes (offset, midplane)
	* a plane and a line (a face and an edge)
	* a plane and a point (a face and a vertex)
	* a plane and a curve (a face and a curve)
* we will create the model from 'lec40-Refrence-Geometry-Planes-Drawing' and add planes on it
* right plane => sketch => rectangle from origin => tangent arc on top => change top line of rect to construction line (props => for construction) => add dims => its fully defined 
* we use offset entitites with a param of 1in and click on shape. we get the offset => ok => exit sketch
* add boss extrude (5in)
* we have to make apartial hole on top. we canntot use the top plane of the model because it is curved
* we need to create a new plane to draw the rect and set cut extrude
* Features => Refernece Geometry => Plane. on left in props i need to provide up to 3 defining references to specify it. we will use the curve and a face (botom floor of model). our new plane istangent to the side of the model. this happens because the relation to the bottom face is perpendicular . we change it to parallel. 
* the relation to the curved face is tangent. the plane is now touching the curved face from top and is fully defined
* we select the new plane => sketch => normal to => draw the rect dimension it
* we add a cnstruction line to midpoint of big shape and make it coincident to it on both sides. its fully defined => exit sketcvh 
* apply feat => extruded cut  .8in => ok DONE
* to hide the plane : design tree => plane1 (our plane) => click => hide
* we ll define a plane using 3 points : features => ref geometry. select 3 vertexes and get aplane
* we gdet a line and point plane, a line+line plane
* i can use any geometry plane to sketch on or apply feats
* i choose extrude boss 'up to next' to extrude till next face
* i define a plane from a face using an offset (distance from face). it pallies on straight faces
* if i pick to opposite faces i get a plane exactly in the middle
* if i click on line and face i get a perpendicular plane passing from both and itersecting face (or i cen set angle in props)
* if i choose a point and a face we get a parallel plane to the face concident to the point
* planes must be fully defined to be sketched

### Lecture 41 - The Features: Lofted Boss and Lofted Cut

* we will model the 'lec41-loft' file
* Loft Boss: Adding materials by connecting different cross sections (usually sketches in different planes)
* We can use guide curves with loft to 'Guide' the materials added between the section
* Loft Cut: Remove materials by connecting different cross sections (usually sketches in different planes)
* our plan to design the model: loft boss => loft cut
* the design has 4 different planes used to design the loft
* we generate these planes: take the right plane and create 3 more planes with offset 5, 5, and 7in
* we start with right plane => sketch +> add 1 circles and add dimensions
* we select plane1 => sketch => square => dims 
* we select plane 2 draw a circle of diam 4in
* select plane 3 => sketch => polygon se dim and coincident to centerline
* i am ready to apply loft boss: in props we have 1 list for profiles and 1 list for guides. we select profiles and then our sketches. we delete the loft. as we will use guide curves
* guide curves must intersect all sketches. select top plain => sketch. i hide the planes
* we draw a line connecting one side of points. to make them connect => 3d => click on point and CTRL shape (rel pierce) 
* we mirror the line on the other side ( use a centerline)
* we go back to lofted bost. select the profiles. select one full guide curve + ok and then the other + ok. our shape is ok
* we do lofted cut. we will use 2 sketches on 2 diff planes. we use one side face as plane to add the circle. and the other side plane to add the pentagon
* we do loft cut. we use only the 2 profiles

### Lecture 42 - PRACTICE!! Let's Model Something that uses some of those Complex Features!

* we will implement the complex model 'lec42-Practice-Sweep-Refrence-Planes-Revolve'
* we plan the creation of the model: 
	* revolve extrude
	* reference plane + extrude boss
	* sweep boss + extruded cut x2 + mirror
	* reference plane + extruded cut
	* fillet
* we start with outer shell: it is a cylinder so revolved boss and cut to our service: select front plane +> sketch (see the crosssection)
we add the cross section outline and dimension it. we add an offset insid at .5in and click reverso to be on the inside. we conect shapes (offset and initial) => exit sketch => feats => revolve boss => select revol axis => apply
* we will create a ref plane for the lid => ref geometry => plane => select top face => offset 0.5 => flip offset
* we use this plane to sketch => circle =>coradial with inner circle => exit => feats => extrude boss => .3 => flip direction (arrow) => hide plane
* we will use sweep boss feat for guides. we need a profile and path
* use top face for sketch => add circle dimnsion is make it horiz to center. i use offset for outer circle .1in
* we now have to make the path (selct the plane) front plane seems ok
* we click cross section in canvas and ok. we add the lines and dimension them
* we are ready for sweep boss. we select the profile (profile and path must be sketches). pipe is ready we need to open them. i select bottom pipe face and make a new sketch. i draw in angle view => add a circle and make it coradial with pipe inside +. exit = extrude cut => through all. we do the same for top => extrude cut => up to next
* i want to mirror all 3 feats composing the pipe (not to draw again)
* in feat menu => drop down linear pattern => mirror => add feats to the list (use designtree in canvas) =>  (on mirror face or plane we select right plane) => ok => exit cross section. we need a plane for it
* ref geom => plane => select rouch surface. planme is tangent. second ref parallel to 2 circles or front plane => scetch => add rect size . midpoitn to origign => extrude cut => feats mirror => select extrude cut => mirror on front plane.
* add fillets: select the edge apply radius

## Section 6 - Let's Explore Material and Mass Properties

### Lecture 46 - Selecting Materials for Your Parts

* we will learn to select materials for the parts we are modeling
* we create a cube of 5in
* we will specify a structural material for the cube
* in design tree there is a point for materials => RCLICK => edit material
* we get a long list of predefined standard materials. we select AISI 304 steel 
* we get info on the properties of the material
* we can select units (IPS) => click apply
* the appearane of the cube changes to match the material
* we select wood and appearance changes. also props change

### Lecture 47 - Viewing Mass Properties

* we use the cube we created in last lecture (made of oak)
* in top meny bar we select Tools => Evaluate => Mass Properties
* we get info about the model 
	* density
	* mass
	* volume
	* center of mass etc
* we change back to steel and check mass properties change.
* if i change model units to SI and come back to mass props i can recalculate

## Section 7 - Let's Start doing Assemblies

### Lecture 51 - Opening an Assembly File

* we will learn how to open an assembly file
	* open from nothing
	* open from a part
* open from nothing: new => assembly => we get prompted to add files => cancel => on left menu we get alist of parts opened (we can add from fs). we can browse for a part we created earlier. we open it. now in the design tree the root is the assembly and our part is hanging in the tree under the basic planes. in Assembly tab we can 'Insert Components' and add a second part. we can add multiple part files at once
* open from a part: if we have a part we are working on and want to create an assembly file => top meny bar => new (drop down ) => make assembly from part/assembly => save it => we go to the Begin Assemply prop menu to add parts (our current is there already) => click on canvas => design tree is populated and we view the part. if i close the assembly the part we worked on is open in background

### Lecture 52 - Types of Mates in SOLIDWORKS: Standard, Advanced and Mechanical

* Mates are the relations between parts in assembly. they are very similar to the relations we used in our skethes
* to use mates we need components. we add a rectangle and a triangle part in our assy
* in the Assy menu we have Mates command. we get a list of selected entities of parts. the entieis can be edges, faces
* below are a list of available mates (standard, advanced, mechanical)
* standard mates are:
	* coincident
	* parallel
	* perpendicular
	* tangent
	* concentric
	* distance
	* angle
	* lock

### Lecture 53 - A Point in Adding Parts _ Base Fixed Part

* we will address a point in adding parts (the fixed part) . in this the first part we add to an assembly is a fixed part. 
* all other parts create relations to this fixed part
* i create a new empty assembly and browse for parts. i add the triangle
* i go and add a second part => insert components => (i add the cube)
* the first part i added is the fixed part. if i click it and drag it with the mouse it doesnt move. if i do the same to the second part it moves
* the fixed part is indicated in design tree as (f)
* the fixed part plays the role of the origin in sketch

### Lecture 54 - The Standard Mates: Coincident, Parallel, and Perpendicular

* the mates we will learn are coincident, parallel and perpendicular.
* they are the same as in sketching but in 3d space
* we will use 4 parts and will use these three mates to put the parts in their slots in base part
* we open a new assembly file. we will add all 4 parts from courserepo
* we start by adding the base part (sloted one) so that it will be fixed
* we insert the other 3 components
* to put the rectangular shape in its slot: mate command => mate selections: upper face of rect to the upper face of base => click coincident.=> ok . i can now move the rect but always in the same plane as the base. i add one more mate: i click a vertex on the rect and a vertex on the slot of the base . coincident mate is applied and the rect takes its place. thow its not fixed i can rotate around coincident point, i add one more relationship between edges ( i can add a vertex mate). rect is fully bound so (-) disapears
* i click on triangle then Assembly => move components (move in space) => move comp (drop down) => rotate component => click on triangle and square and rotate
* bound the triangle: to face parallel to base top face (cannot fully rotate now remove an axis of freedom). imake face of triangle and inner face of base perpendicular (remove an axis of freedom). i add one more 2 edges coincident. i can move it up and down. i make top faces coincident. and triangle is bound to base

### Lecture 55 - The Standard Mates: Tangent and Concentric

* We will learn how to use the standard mates: tangent and concentric
* we use the parts in 'lec55-Standard-Mates-Tangent-Concentric' folder
* we create a new assembly and add first the base (fixed) and import the component 3 times
* i can make copies of items click + hlod CTRL + move and drop
* i wan to put a cylinder in the hole: click Mate: => click outer surface of cylinder + click inner surface of hole + select concentric. now it can only move up down and rotate. irestric up and down with coincident. to restrict rotation. if i want inner cylinder gap parallel to block edge: 2 edges + parallel mate or surface. cylinder is restrained
* for 2nd cylinder i do concentric with edges. applycoincident and perpendicular
* for 3rd i do tangent of surfaces

### Lecture 56 - Finding out Existing Mates, Deleting or Modifying them!

* we use the assembly from lec54
* there are 2 ways to identify mates: 
	* from the design tree
	* from the canvas
* in the design tree i can
	* see all mates of the assembly in its tree
	* see all mates restraining a part in its subtree
* if i hover on the mate i can see the involved entities
* i can RCLICK + DELETE to delete one
* on canvas if i select a part and RCLICK i get the option View Mates which shows a pop up with the applied mates
* i can RCLICK+ DELETE them or edit them etc or even temporarily Supress it

### Lecture 57 - The Standard Mates: Distance and Angle

* we create a new assembly and import base part from folder 'lec57-Standard-Mates-Distance-Angle' as fixed and insert wing part which we cp 3 times (4 in total)
* all my wings touch the base top face. i add the firce on edge with a coincident mate rel between wing edge and base edge. and then touching edges on both coincident (like a hinge). the i select 2 angled edges (or faces) and apply angle mate rel of 130deg. do the same for other side
* for the middle wing i apply 2 coincident mate to place it on top of base (sliding horizontaly) and i distance from side wing

### Lecture 58 - The Standard Mate: LOCK

* LOCK is one of the least used mates in solidworks
* we create a new assembly and import base part from folder 'lec57-Standard-Mates-Distance-Angle' as fixed and insert wing part and cp it 1 time
* i select mate => an element from both wings (verterx, edgw, face) and use LOCK rel. it locks both parts to each other on their curent position (one to other) so they behave as 1 part in olacement 

### Lecture 59 - Reference Geometries: Coordinate System

* we will add a new coordinate system ro a part and find the center of mass according to this new coordinate system
* we get a drawing 'Reference Geometries: Coordinate System' and a part and try to find the center of mass to the coordinate system shown in the drawing
* we open part 'lec59-Lab_ring_2015' and see the mass properties tools => eval => mass properties
* we see the center of mass location and the origin . we want to add a coordinate system to be used for mass center calculation
* Features tab => ref geometry =>we place the coord systm to our vrtex. 
* we need to orientate it. we select edges for the axes (we need to define them in order x->y -> z)
* in mass properties in report coordinate reference to i select the new coordinate system

### Lecture 60 - PRACTICE!! Let's Assemble something using Standard Mates

* we will assemble an assembly of 6 parts using mates. the parts are in courseRepo
* we add all parts (base first).
* we attach the ball to the handle (concentric)

## Section 8 - Let's Start doing 2D Drawings

### Lecture 64 - Opening a Drawing File

* there are 2 ways to open a drawing
	* open from nothing: new => drawing => select size => new drawing open. we can import parts or assembly, we click on drawing and views are added
	* open from part or assembly:  when working on a part => new (drop down) => make drawing from part/assy => on the right we see different views of our part

### Lecture 65 -  Adjusting Measurement Units' System in a Drawing File

* be sure to always work with the correct unit of measurement (bottom right corner)
* the unit of measurement in our drawings file, does not have to be the same unitwith what was used to create the part

### Lecture 66 - Creating Standard Orthographic Views from a Part

* we will learn to create orthographic views from a part using the part in 'courseRepo/lec66-Creating-Orthographic-Views'
* open it => new => drawing from a part => from the view palette on the right i select Front view> click and drag to a position
	* move mouse up get top view
	* move mousee down to get bottom view
	* move mouse right to get right view
	* move mouse left to get left view
	* move mouse diagonal to get isometric
* these are the orthographic views
* views are apearing in the design tree.
* if i move a view the others are linked and move as well
* first view i insert is base view . the others are linked to it
* isometric view is a standalone view and can move freely
* adding more views is easy. click on view palette icon on right menu bar

### Lecture 67 - How to Change the Drawing Scale

* we will use the drawing from previous lecture 'lec66-orthographic-views' to show how to scale
* i click on the base view (front) => scroll the left menu down => in scale we choose custom. i do user defined and set it 1:1.5
* i can select the isomentric view and scale it to 1:1

### Lecture 68 - Communicate your Drawings: Dimensions, Holes, Centerlines and Display Style

* we use the previous lecture drawing 'lec67-drawing-scale' as base
* to add dimensions from command menu tab => Sketch => Smart dimension
* adding dimensions is like sketching. dont overdue it, add as mush as necessary to communicate the design and intent to manufacturers , reviewers or users
* to communicate holes: Annotation => Hole Callout => click on hole and get annotation of radius and depth
* adding center mars also help with the understanding (show symmnetry)
* i can extend circle centermarcs or i choose Annotation => centerline=> click on two symmetric parallel lines and get centerline in middle
* i can change display style of views (CLICK => left menu => display style)
* i can show hidden lines
* usually isometric is shown realisticly

### Lecture 69 - That Information Block at the Bottom of the Drawing!

* we build on top of the last lecture drawing
* we zoomin the info table => RCLICK => Edit Sheet format
* we can highlight and edit info
* to finish editing RCLICK => Edit Sheet

### Lecture 70 - Exporting a Drawing as a PDF or an Image

* on top menu bar => save as => file format e.g pdf => save
* many file formats are avaialble

## Section 9 - Additional Stuff

### Lecture 73 -  Before taking SOLIDWORKS Certification Test _ Sample Test

* Before taking the SOLIDWORKS certification test. Check out SOLIDWORKS [page for the certification](https://www.solidworks.com/sw/support/796_ENU_HTML.htm).

# Course #2: SOLIDWORKS CSWP

## Section 2 - Features Bundle # 1

### Lecture 7 - Draft

* Draft Feature enables us to create tilted surfaces
* we will implement 'lec7-Draft-Lecture-Demo'
* design the base block: we start a new part => top plane => sketch => draw square (center at oigin) => dimension => exit sketch => feats => extrude boss
* we will add the conical shape on top: select top face => sketch => normal to => to easily draw a rect same as the top face we use Convert Entities command selecting the face in sketch mode => exit sketch => select sketch from tree=>feature=> extruded boss. we dont wont a cube but a conical shape. so in extruded boss menu we select Draft On and set the angle accoding to drawing (we can draft utward for bell style shape) => ok
* we repeat the same for bottom face but we draft outward
* we will now implement the draft style cut in the bottom of the bell => bottom face => draw square (origin center) => dimension from face edge. => exit sketch => extrude cut => draft 
* draft exists as a standalone feat in menu. we get draft angle
* in draft feat we set neutral plane (it is what gets unchanged in draft) for us is the inner square. we also select faces to draft (4)
* select a side face => sketch => draw square center to face => dimension  => exit => extrude boss
* use standalone draft for tilt on top select outer face (neutral plane select face to draft apply angle)

### Lecture 8 - Shell

* Shell enables us to easily empty parts from the inside
* we will implement the drawing in 'lec8-Shell-Lecture-Demo-Drawing'
* set to IPS => new => part => top plane => sketch => cetered circle. dimension => exit => extrude
* top face => sketch => convert entity => draw line (string) => dimension => make vertical => exit sketch => extrude cut (select conture)
* in feats => shell feat
* sheal feat has the following params:
	* dimension (thickness) of the shell
	* faces to remove (whatever i put here is removed)
	* Multi thickness (dimension)
	* Multi-thickness faces
* if i set thickness of shell and apply my whole body becomes a shell of that thickness
* if i slect top base as face to remove in the shell feat it is removed from shelled object
* in my drawing thickness of shell is different for side wall and bottom
* this is done with multithickness. select a face and set its particular thickness
* for bootom i want .5in thickness. i add bottom face to multithickness list and set its thickness

### Lecture 9 - Hole Wizard

* Hole wizard enables us to make a variety of slots and holes, threaded or not, that match well establshed industry standards
* we will implement the drawing of 'lec9-Hole-Wizard-Lecture-Demo-Drawing'
* we will create a cubical shell and use hole wizard to add holes in it
* top plane => sketch =>centered rect => dimension => exit sketch => feat => extrude boss
* Features menu => Hole Wizard 
* Hole Wizard offers standardized holes. we follow the drawing: 
	* Holetype: Counterbore
	* Standard: ANSI inch
	* TYpe: binding head screw
	* Size 10
	* Fit = Loose
	* End Condition : through all
* after seeting the config. we need to poistion the hole in the drawing => Positions Tab => Select face. face becomes a scetch plane we adjust the view clicking on the coordinate system in the canvas bottom left corner => we drop the hole. hole placement in whole wizard is done with points. whenwever we bind the point with rules and dimensions there will be the center of the hole. we add centerlines and mirror the hole point in both directions
* we drill hole b following the same procedure (just we use the custom param for countersink)
* we use hole wizard for type C thread is blind and 3in
* In positions tab we click 3d sketch as we want to place th thread in 2 faces. we center them with cenbterline
* if we go top view we see doted lines. these represent threads

### Lecture 10 - Reference Geometries: Coordinate System

* Lecture is same as Lecture 59 of CSWA course

### Lecture 11 - Linking Dimensions

* By linking dimensions. one dimension can be dependent on another one
* we will work on that implementing a triangle like 'lec11-Linked-Dimentions-Lecture-Demo-Drawing' 
* new part => front plane => sketch => draw a triangle with one vertex on origin and one 90o angle. 
* we dimension just 1 edge
* instead of using equality as a edge relation in sketch: we dimension the other edge of triangle. instead of giving a number val i write '='and click the other dimension. the value of the dim is ='D1@Sketch1' . i click ok. now the dim value on sketch is 'Σ 3.00' to show it is a linked dim
* now when i ressize the first edge. the other gets resized.
* the rational of using it is that we can us it for other sketches or features
* without exiting the sketch we go to feature => extrude and in dimension we enter = and click on the first dimension
* now if i chang eoriginal dim all the other change

### Lecture 12 - Let's Practice Together (Draft, Shell, Hole Wizard, Linked Dimensions)

* in this exercise
	* draw the model
	* select material
	* find weight 
	* change width
	* find new weight
* plan of implementation: rect => extrude boss => draft => hole wiz => shell => extrude cut
* to make holes symmetric and equally spaced i do linnear pattern. then select center of first, center of last and centerline and use symmetric rel

## Section 3 - Features Bundle #2

### Lecture 16 - Equations

* Equations are a more sophisticated way to link dimension
* we will be able to define variables and equations and link them to specific dimensions
* we will implement the 'lec16-Equations_Drawing'
* we set to mm in a new part
* we will go on to define variables
* The first way to define variables: Design Tree => Part root => RCLICK => Hidden Tree Items => Equations => Manage Equations
* We get a window with a list of Equations Global Variablers and Dimensions
* we define a global variable and click OK
	* Name: "A"
	* Value: =5
* equations are added to the design tree. in there is A as a global
* in top plane i sketch a triangle made of lines
* i dimension base edge. instead of entering a num i write = and get a list of options (Global Vars, Function, File PRoperties). In global variables is A and click ok..
* My second Global Var i define in a different way. I dimension another edge. in the dim i write ="B" . the global sign is appearing. i click on it and i am propted to enter a val i write 4 and ok. A global var of "B"=4 is created and edge is dimensioned.
* i dimension 3rd edge and i write ='A'/2 which is valid
* i define another global in manage equations (RCLICK on Equations in design tree):
	* Name: "C"
	* Value: "A"-"B"
* i set and use globals using ""
* i extrude boss using C for thickness
* now changing the vars i mod all my design

### Lecture 17 - Mirror

* Using mirror enables us to easily create symmetrical copies around a line, a plane or a surface
* we will vreate a mirrored model 'lec17-Mirror_1_Drawing' following the plan: Hex => extrude => extrude cut circles => mirror => add hex extruded on top => mirror extruded hex
* new part => inches => top plane => Sketch => polygon => base horixzontal => side dim 3 => extrude
* create side holes: top face => sketch => diemension. => mirror hole on centerline (mirro entities) => extrude cut
* i will now miror the whole shape: Feature => Mirror
* i need to add entities to the following lists
	* mirror face/plane: like centerline in sketch 
	* features to mirror: (select features to mirror)
	* faces to mirror: if we want to mirror just faces
* apply
* draw the face on top face => extrude => mirror. to mirror it i need to add a plane (using 2 edges of the shape)

### Lecture 18 - Features End Conditions

* End Conditions can provide us more control utilizing features like extruded boss and extruded cut
* we will implement the 'lec18-Feature Conditions_Drawing' in mm
* new part => front plane => sketch 2 lines and an arc => dimension 
* the angle of the arg is 75o. i add 2 centerlines add rel on angle and concinet the arc point 
* extrude boss (thickness to 8)
* we ll create central plate => select side face => sketch => cross section =>sketch => normal to => add rect => size and position
* extrude boss:
	* Up to Body => select curved feature (useful for multibody parts)
	* up to next face
	* up to surdace (select surface)
	* blind extrude type gos up to dimension
	* through all to the opposite face of the design
	* up to next to the next model face
	* up to vertex. to the next vertex i select
	offset to surface. like up to surface but i set an offset to the end of extrusion (it follwos the surface)
	* mid plane like blind but extrudes in 2 directions

### Lecture 19 - Multi-Body Parts

* with multi-body part we mean a part with more than one separate body. unconnected volumes
* a multi-body part is NOT an assembly
* we will implement th 'lec19-Multi-Body Parts_Drawing' in inches
* our plan is to create the 4 legs first and then the top body
* top plane => sketch a square => dimension it
* place it correcly i create centerlines and add dim from edge to over the centerlins. this addd the dim with centerline at midpoint.
* i mirror on both centerlines and extrude all squares
* this is a multibody part
* in design i have a solid bodies entry with 4 bodies
* we use mirror feat. but we dont have features to mirror . we have bodies so we click bodies to mirror selecting our bodies
* i select a leg top face => sketch => normal to => create a rect 
* i extrude boss it. in the mprps i see merge result. this appears every time o work with multy body part and my new feat will connect them.
* it asks if we want to integrate them all in one body
* now i have one solid body
* if i leave it unchecked i have 5 bodies
* in a multi-body design i can hide or isolate bodies
* if i want to send to manufacturers each bodysepearately for construction i have to save each separately (solied bodies => RCLICK => save bodies)
* Multi-body parts is a powerful design tool to design static objects because i can link dimensions between them but they do nt replace assemblies (its like a locked mate assembly)
* any dynamic interaction of parts can be done and analyzed with assemblies
* if i update my multi body part. separately saved bodies do not update. to make the updates apply i have to place the feats above the save bodies entry in list

### Lecture 20 - Feature Scope

* Feature scope works with multi body parts. it allows us to specify which body a specific feature will apply to
* we will implement the dsign 'lec20-Feature Scope_Drawing' in mm
* new part => top plane => draw a rect cp it 2 times with offset allong x (linear pattern) extrude. i have 2 solid bodies
* select an external fase and scetc a rect
* i want to apply extruded cut and only cut through the 1st and 3rd body
* select through all
* in bottom of props we have Feature Scope section. i can eithter select all bodies or select bodies => deselect auto select => select the bodies => apply
* i get a prompt which bodies to keep in m,y dsign. this promp happens when by applying a feat i split a body into two. i choose to select the m all and now i have 5 bodies

### Lecture 21 - Rib

* Rib is a special type of extruded feature. It is  also a very easy way to create ribs.
* To show rib feat we will implement the drawing 'lec21-Rib_Drawing' in inches
* our design plan will be: square => extrude => shell => rib => mirror => rib
* top plane => sketch => center rect => square => dim => exit => extrude => shell (remove top face)
* we ll now do the rib: select front plane => sketch => section view => drow one line to define the rib (an incline line defining like a triabngle with side and bottom face) => feats => Rib (without exiting sketch)
* line is highlighted
* if i apply it a rib of default thickness is added concident witht he line i drawn (line was extended to meet faces)
* Rib does not need a closed shape
* i define my line according to drawing => select Rib
* the options are:
	* how to calculate thickenss regarding the line
	* thickness
	* extrusion direction dict5ates towards which direction the rib will be extruded. horizontal or vertical
	* we can add draft (not linear but drafted sideway)
* i need to mirror rib ON RIGHT PLANE
* to draw the last rib we will use a reference geometry plane (offset from top plane) and draw the line + curve. we select Rib thickness and change direction.

### Lecture 22 - Let's Practice Together

* we will implement the 'lec22-Ex2_Demo_Drawing' in mm
* we willpractice the feats we learned
* desing plan: outer shell (extrude) => rib => hole => mirror => rib => mirror => extrude (multipart) => extrude (mulipart)
* right plane => sketch => create outline starting from origin => extrude boss (use midplane to keep design symmetrical to origin)
* use bottom fae as plane => sketch => straing slot feat => dimension it => extrude boss
* we add global vars
* we use inclined back surface for sketch plane => draw the wing => extrude boss => draw the circle => extruded cut (offset from surface) => select side face => draw the rib line => rib
* mirror symmetric feats
* we create 2 rods (separate bodies): use back inclined face as sketch plane => use both holes and 'convert entities' to create circles => extrude boss => up to surface => unclick merge resutl => we have 3 solid bodies
* do the hole: select top face => sketch circle => center => dimension => extrude cut (offset from surface)
* do the plug: slect top surface => sketch => plug is 0.5 mm in the hole so offset feature => exit sketch => extrude boss (up to next, dont merge result)
* again in top face => sketch => draw circle for plug top => draw circle extrude boss.
our extrusion is in contact with 2 bodies (plug and base) we want to merge it only with plug
* i use feature scope. select the plug and leave merge result checkecked
* we need to create a slot in the middle of the 2 rods: select right plane => add aline ffrom rod midpoint parallel to edges and size it. extrude cut (thin feat 1mm) 2 diresctions through all (feature scope selected bodies select 2 rods)
* edit material find mass
* change globasl and recheck mass

## Section 4 - Design Tables and Configuration

### Lecture 26 - Establishing a Design Table

* desgin tables is an efficient way to create multiple configurations of the same model utilizing MS Excel
* we will implement 'lec26-Establish-a-design-tables' in mm and then get multiple configurations based on a design table
* new part => top plane => sketch => centered rect and a triangle on top => dimension it
* by default our dimensions are named sthing like 'D1@Sketch1'. we will rename them to something easier to remenber for our design table
* extrude boss and select both regions to make 1 unique body
* i click on feat to see dims. i rename thickness as 'Thickness' in params
* top face => sketch => normal to => draw centered square => dimension it and name dim 'Key' => extrude cut  (through all)
* we have the model ready so now we will create the design table: in top menu bar Insert => Tables => Design Table => Autocreate
* we select only the dims we named from the popup list and we get an excel spreadsheet. default vals are in already
* in the spreadsheet we add 4 lines with 4 configs with different dimensions
* after filling the rows we click on canvas and the configurations are added to design table
* in design tree window we go to tab 'Configuration manager' and 1i see my 4 configurations. doubleclicking on my configs changes the model by changing the dims
* with this we abvoid creating multiple model files

### Lecture 27 - Modifying Established Design Tables

* we build up onour previous model and design table.
* we are asked to do the following mods
	* modify configuration 3, by making H1=20mm and Thickness=30mm
	* add a new config (h1=5,thickenss=5,key=2mm)
	* remove key slot from config 2 and 4
* in the configuration manager in design tree we click on Tables and see Design Table => RCLICK => EditTable. we get the excel sheet popup => ok.
* in the excel sheet we implement changes
* to remove key slot i need to be able to apply or not the feat based on the design table. to do this: select the next emtpy table column label cell => DUBLECLICK on the feat in the design tree. the default val is UNSUPPRESSED or U (applied) to disable it i need to set SUPPRESSED or S in config 2 and 4. leaving cell empty is equal to unsuppressed

### Lecture 28 - Configurations

* we will explore configurations without using design tables
* we will implement 'lec28-Configurations-Drawings' in inches
* new part => top plane => sketch => center rect => dimension => exit => extrude
* top face => sketch => normal tro => circle => dimension => exit => extrude cut => through all
* we will now add anew configuration to our model: design tree menu => configurationmanager => right click on part configurations => add configuration => name: A => ok . our new config appears in the tree
* beign in the config A i add the hole on the left
* top face => sketch => add circle => dim => extrude cut
* if i go back to the default config hole dissapears
* I Add one more config to ad done more hole
* every feature i add to a configration of a model is added to the rest but is disabled (supperessed)
* for C i use A as a base (more similar), i select it in feature manager and add a configuration
* to draw the rect i dgo to design tree => select cut extrude => suppress it
* select top face => sketch add rect => extrude cut
* in configurations we only set feats on and off (no dimension resize (we need desing tables))

### Lecture 29 - Let's Practice Design Tables and Configurations Together

* we will implement 'lec29-Ex 3_ Demo_Drawing' in inches using a made model and playing with configurations and design tables to create multiple versions of it in the same model
* from default we will create config A b and C . then C.2 changing the middle
* open model. create config with design table
* we select dimensions: body width, cut width, hole_diameter
* we select C. in the config mangnager we add config C2. in there we suppress extrud cut hole and add the square
* we select B and add config B-AISI 304. in it we select the material and edit adding the AISI304
* in configure material we see the material for each configuration

## Section 5 - Assemblies Advanced Mates

### Lecture 33 - Profile Center

* Profile center mate makes it very easy and fast to center two simple profiles in relation to each other
* we work with parts from '/courseRepo/lec33-Profile-Center'
* we create a new assembly and add MainBody part first as fixed
* we import the other 2 parts (cap and triangular sticker)
* we hide the sticker
* we will put the cap on top of the body using simple mates: select cap bottom face and body top face (coincident)
* we  need to center it: concentric mate => select edge on cap and body
* we can still rotate the cap
* to cp the cap to the botom i Ctrl + click and drag the part
* i will use the profile mate on the bottom cap to position it: mates => advanced mates => profile mate => select 2 surfaces to center to each other (bottom of cap and bottom of body). => i use Mate alignemtn to flip the cap
* so Profile Center = Coincident + Coccenric Mates
* Profile center offers options like:
	* offset
	* flip direction
	* lock rotation
* we unhide the sticker and use the profile center to stick it to a body face: mate => advanced mate => profile center => select face in triangle and body
* when we have a part that is not circle we get another option (Orientation) to rotate the part in symmetric positions
* we can only use profile center with:
	* full circular faces or edges
	* linear edges
	* regular polygons
* so i cannot use it between triangle and an irregular shape (top of cap)
* if i have a regular shape with a cut in it ican use it

### Lecture 34 - Symmetric and Width

* Symmetric Mate makes two similar entities symmetric about a plane
* A width mate constrains a tab between two planar faces
* we insert base component from 'lec34-Symmetry-Width' as fixed
* we import the other 2 parts
* i cp the antenna part
* i add concentric mate between antenna circular face and hole
* antena moves in 2 axis of freedom. i want to restain it to be in the slot.
* we use advanced mate Width to place it in the slot in symmetric distance from side faces: Mate => advanced Mates => width => In width selection we select the faces defining the wiidth => with tab selection we select a face form the part wewant to constraint (antenna). we select faces from both sides. 
* there are 4 available constraints for Width:
	* centered (place in middle)
	* Free (free to move between width faces)
	* Dimension (precise se of distance tab-widht face)
	* Percent (use % for position)
* width faces define a hard limit
* we do the same for the other antenns
* we will now implement a symmetric relationship between the antennas: Mate => Advanced Mates => Symmetric:
* we want a symmetric plant in the middel of base. i can use a plane of a part (base). => entities to mate: select two symmetric faces on both antennas => apply
* no if i move an antenna the other does symmetric move
* we want mate to fit in the slot . so we will use width on both axis.

### Lecture 35 - Distance and Angle Ranges

* Distance and angle ranges allow us to set movement ranges for both angular and linear movements
* we will use assembly 'lec35-distance-angle-ranges' to apply these mates
* i want to limit the movement of the screen to 0-130o
* also we want to limit the movement of the keys from 2 to 100mm
* Mates => Adv Mates => select the faces  (entities to mate) => set angle constraint (maximum value, minimum value)
* the same is for distance

### Lecture 36 - Path Mate and Linear/Linear Coupler

* Path Mate allows us to make a point in part to follow a specific movement folowing a set path
* Linear/Linear Coupler ratio allows us to link movements for different parts using a linear relation or ratio
* we will use the 'lec36-path-mate-linear-coupler' assembly to learn these mates. it has most of the mates defined.
* we want the ring to follow the wire path. Mate => Adv Mates => Path Mate
* we need to fill two lists: 
	* Component Vertex: (a point on the movable part)
	* Path Curve: Contiguus edge.curve etc as path
* for our example we want the component vertex to be the center of the ring hole: expand design tree and use the origin of the part
* we select a path from the seep sketch in wire part (by shoing it in sketch)
* i apply the mate and it works but i can rotate the ring through the wire
* path mate has additional options:
	* path constraint: how far in the path i can move
	* pitch/yaw control: follow path with one axis fixed
	* roll control: i can select an up vector and an axis so that the part is bount to an axis related to it
* i have one cylinder and one seeth moving cocentric but independently to a side slot
* we want to link them so that the movement of the inner tube is 3 * the movement of the seeth (a ratio)
* Mate => advanced Mates => Linear Coupler
* I need to spec:
	* Entity to Mate
	* Ref Component for Entity 1
	* Entityt to Mate 2
	* Ref component for Entity 2
	* Ratio
* as entitty one we select inner tube face ans as entity 2 the outer tube face
* we dont set ref components as we we will use the reference point of the assembly. 
* initial position is important for this mate

### Lecture 37 - Let's Practice Advanced Mates Together

* we will add mates on the 'lec37-practice' assembly
* we work on main cover:
	* concident rel of bottom edge with main body
	* width from main body side faces
* i add and angle restriction to one cover
* i mirror the cover with its mates. (i get the symmetrical for free)
* knocker:
	* coincident face to base
	* width both sides
* sliders (use coincident to base and width)
* bound slider to linear distance
* linear coupler between 2
* touch pad: profile center mate
* ring using path mate (block origin)
* i have aproblem as path is split into lines. to solve it: Selection Manager => Select Open Loop => click on path in sketch

## Section 6 - Assemblies Deep-Dive

### Lecture 41 - In-Context Features and External References

* In-Context features and External References will allow us to link dimensions of different parts in an assembly file
* create a new assembly => import base (fixed)
* import the middle block. note it is not dimensioned according to the spec
* we use profile center to put it on the block
* we want the edges of base and middleblock to be 0.25in
* We RCLICK on middleblock => Edit Part => expand design tree => extruded boss => Sketch => edit sketch
* my sketch rect is not defined. we define it now. we can select dimension to the other parts edge.. we use it to spec .25in from base edge
* our feats get the -> indications to show they are dependent on other parts
* i select middle plane top face => sketch => section cut  select extrude cut of base part => convert entities to get the rect =>extrude cut (through all)
* extrude cut feat is also linked to the other part. these are called in-context features the refs are external references
* to see the refs we can RCLICK on the incontext feat and click External refs
* we add the rod => coincident mate
* we edit rod => extrude => skech and add rel on rect lines to bas edges (equal)
* now if i mod a dim in one part others are changes together

### Lecture 42 - Assembly Features

* Assembly features are just like the normal features we are used to. like extruded cut
* Assembly feats will be applied to the assembly rather than the part
* Assembly feats are fewer and are mostly subtractive feats that involve removal of material
* we will use 'lec41-incontext-features-external-refs' assembly as base to drill to oles through multiple parts
* in Assembly tab we have Assembly Features command drop down with the available feats
* We select Extruded cut => select top face => sketch => draw circle => extruded cut => through all
* select a side plane => sketch => draw circle => extrude cut (through all)
* assy feats in design tree hang under the assembly entitie
* however parts do not get modified (WTF?
* the reason to use them is to show design process => seq . parts are manufactured => assembled => then hole is drilled

### Lecture 43 - Collision and Interference Detection

* Those two feats will enable us to find out when 2 parts in an assembly collide or interfere with each other
* we will use the assembly of lec34 as base
* we improt the cap
* soldiworks can detect collisions and interference between moving parts
* Assembly => Move Component => Collision detection
* when we choose collision detection we get options:
	* all comp 
	* these comp 
* stop at collision or not . if not we just get a sound and an indication of what collides
* we can stop at collision. => find the angle and limit movement
* to do so: exit move => layout => smart dim => select faces . it is 10.8o
* we fit the cap => evaluate tab => interference detection => 
* in the selected components we put all the asembly. we calculate and see that the cap does not fit well
* i can config collision detection

### Lecture 44 - Replacing Parts in an Assembly

* we will use the assembly from lecture 36 as base and use 2 replacement parts
* first we will replace the ring. we check its movement and its mates => RCLICK => View Mates. it has a path mate between path and the ring
* to replace apart in solidworks: RCLICK => Replace Component
* We get some properties like:
	* which part to replace (prepopulated)
	* pick a replacement part section
	* we are asked to atach existing mates
* we get prompted to config tthe mate
* solidworks will try to copy the mates from the original part to the replacement

### Lecture 45 - Sub-Assemblies

* we use as base the 'lec60-practice-assembly' from CSWA for upper assembly
* Sub-assemblies are basically assemblies within other assemblies
* we open upper and lower assemblies from the courseRepo
* we will insert lower assembly into upper assembly as sub-assembly: Inser COmponents  => we see the lower assembly in the list => Import
* assembly is added in design tree
* we deal with subassemblies like with parts
* we add width mate and concentric to bind them and parallel
* in upper assembly i can move the lever but in lower i canno tmove the  drawer although it has mates
* when we first import sub-assemblies solidworks ttreats them as rigid assemblies that we cannot move parts
* to fix this: RCLICK on subassembly => click on top menu icon (Make Assembly Flexible)
* we insert thelong post to connec them. we add mates (Concentric of side face to lever edge) => add width rel with drawer

## Section 7 - Additional Stuff

### Lecture 48 - Official CSWP Sample test
* Before taking the SOLIDWORKS certification test. Check out [SOLIDWORKS page for the CSWP certification](https://www.solidworks.com/sw/support/797_ENU_HTML.htm). There, you can read more about structure of the CSWP test

### Lecture 49 - Tips when taking the CSWP Exam

* In the case you are planning to take the Professional Certification Test (CSWP), here are few tips: 
	* Make sure to save the your work separately at the end of each question. 
	* Having two screen or a bigger screen would be helpful so you can see the question and work on SOLIDWORKS for answers at the same time. 
	* In multiple choice questions, usually if your answer is off the given ones, it means you did something wrong along the way. This makes the first tip important too. 
* The CSWP exam is not easy. It does require complex modeling and high level of SW modeling fluency. It will also require you to work fast. Even though this course teaches just about all the skills needed for the exam, speed and fluency are two aspects beyond skills that take time to acquire. 
* So, take some time to digest what you learned in this course, find lots of objects around and model for practice, or look for side freelancing projects on the side, more practice will greatly increase your chance to Pass the test. 

# Course #3: SOLIDWORKS CSWPA-DT

## Section 3 - Step2: Drawing Foundation

### Lecture 19 - Relative to Model Views

* Relative to Model Views allowus to define our own orthographic views that are different than the ones set by default
* we go the 'lec19-Green Block' part to add drawing. we were said that the hex hole face is the front view
* We open adrawing file: Filw => New => Drawing file => A ANSI size => OK
* on right menu select View Pallete. inthe drop down select the model
* Views are populated. and they are strange (tilted, not conveying useful info)
* we will use the relative to model view functionality to define our own front view
* in View Layout tab we have all options (Relative view is not included by default)
* we can use the search bar in top mnu bar to find it: SearchBar => drop down => Commands => Relative View (write it) and drag it to View Layout Menu
* another way is to go Top Menu bar => Insert => Drawing View => Relative to Model
* it asks us to select the model we want to work on. => we select the front view we added in our drawing => we get prompted to the part model view with the relative view menu bar on the left
* i want to set the front view.: First Orientation (Front View) => add my face of choice as front view
* for second view i choose bottom and select bottom face.
* we apply it and get taken back to drawing with our new front view ready to attach.
* after i attach the view to the drawing i ClICK and get Projected View option. i click it and get orthographic views relative to the new front view that i can use by dragging it.
* i delete origina views.
* in this way i can make useful designs from models with odd plane selection
* i use relative view to draw another useful view (inclined holed face)seting it as front and inserting it to drawing

### Lecture 20 - Auxilliary Views

* An auxiliary view is very similar to a projected view, but is folded to an edge of our choosing
* we use the part and the drawing from previous lecture as base
* there are 2 ways to create an auxiliary view:
	* From an existing edge
	* From a line that we sketch ourselves
* for our green block i want to show the true sizes and positions of the holes
* we will use an auxiliary view folded around the side face with the holes
* View Layout => Auxiliary View. it prompts us to select an edge
* we select an edge from an existing view in the design sheet and a view is added in the design. this view is the view if we unfold themodel at the selected edge
* this move moves only perpendicular to the selected edge. 
* the original view is tagged and an arrow is added to the auxiliary pointing to the  edge
* we will add another auxiliary view using the top vire edge. we will use the second method
* say i want an auxiliarry across an edgev pointing to the topview at an angle of 30o
* Being in the drawing we go to Sketch and add add a line
* our line must be inside the view focus area of the  view
* we dimension it to 30o => View layout => auxiliary view => select our newly created line in the drawing => we get a new view

### Lecture 21 - Model Items (for Parts)

* With model items we will be able to easily and automatically export all the dimensions we added when modeling a part into the drawing
* we use as base the previous lecture drawing
* To use it: Annotation tab => Model Items => 
* we want the dimensions to cover everything in the model: Source => Entire Model => apply. our views are fully annotated
* The locations of the dimensions might not be ideal. after applying these functions we need to adjust where dimensions are displayed to make our drawing user friendly
* The dimensions imported are the exact ones inputted when the designer designed the part. This has a very big advantage, because in that way we guarantee to capture the design intent inour drawing.
* Hidden dimesnions and other options: the design is missing overall heigh and length of the part (because they were not added inthe model or hidden)
* To confirm it: RCLICK on drawing in design tree => open part => Extrude feat => Sketch. the main dims are purple in color not black. i RIGHTCLICK and see tha the option 'Make dimension to be imported into drawing' is toggled off. u toggle it on. dimension appears in drawing ( i need to reaply model items)
* If i want to show diensions not marked for drawing without modding the part: in Model Items command meny => in Dimensions apart from marked for drawing select 'Not marked for drawing'

### Lecture 22 - Model Items (for Assemblies)

* * With model items we will be able to easily and automatically export all the dimensions we added when modeling a part into the drawing
* We will work on the assembly from CSWP lec42 'lec42-assembly-features' to:
	* find the dimensions ofr all assembly features in the assembly (extruded cuts)
	* find the dimensions of only the base
* Assembly feats are usually subtractive feats applied at an assembly level rathern than at part level
* We go to Annotation => Model Items => Source: only assembly => apply. we get only assembly feat annotatons
* model items => Source: selected component => click on the base on any of the views. we get the dimensions comfortably arranges in teh available views
* we change the dims to inches

## Section 4 - Miscellaneous Views

### Lecture 26 - Section Views

* Section views are orthogonal views. However they show a cross-section of the object along a specific cut plane
* we will create te drawing of 'lec26-Section View_2015' part
* this part has holes and tunnels in it
* we are asked to do the drawing of the model
* we import them odel to get orthogonal views. we start from top view and isometric
* we select Display style: hidden lines visible for top view
* to create a Section View we: go to View Layout tab => Section View
* we get 4 options of cutting lines:
	* vertical
	* horizontal
	* Auxilliary
	* aligned
* we choose horizontal for 1st plane (auto start section view enabled) and get section A-A
* clicking on section view we can rename it
* our secont section view will be along the tunnel path line (not straight)
* we select topview and reselect Section view => vertical (disable auto-start section view). we move the line to tunnel and get a popup with options(Arc Offset, Single Offset,Notch offset) to customize the cut plane
* we select notch offset selecting 3 points accross the tunnel to set the curve, then select single offset for straingth lines. in this way we follow the path to seth the section plane. click apply . then select and flip direction
* to create  isometric section views: select section view => RCLICK => isometric section view. 
* in this way we have the section view in an isometric orientation

### Lecture 27 - Break-Out Section Views

* In a break-Out section view , we can cut away a portion of the model to expose the inside of it.
* we will use the part of 'lec27-Break out section view' to create adrawing using this technique
* we open a drawing file from the model and insert front - top and isometric views
* we click on main view (front) and set custom scale
* for breakout: View Layout => Broken-out section => in drawing canvas cursor is now a pen.
* we need to draw the section of the dawing we want to cut to see inside the part.we workon isometric view
* the we need to enter the depth  for the break -out section (numeric val or select an entity (edge) to cut up to it)
* we set 50mm
* we do the same for front view but we use an edge on the back side
* to mod a breakout view section: click in design tree on a view to see the broken out section entity in it => RCLICK => Edit definition OR edit sketch
* i edit sketch editing the line defining. rebuild to apply change
* for isometric break-out we edit the  definition changing the depth

### Lecture 28 - Break Views

* Break views allow us to view a large part clearly in a smaller sized drawing sheet.
* we will use part 'lec28-Pipe_2015' to create a drawingout of it.
* we insert front view and side view
* in view layout we select Break View => we are asked to select a view. we select front view.
* we choose a cut direction, line style and the gap size on drawing. then we select where to place the break lines.
* we apply horizontal break in the same view
* my break in front view is not propagated to the side view. to do it we can add a break view our selves to this view. our lines are an exact match of the ones in the front view. if it is not we RCLICK on view => Properties => Enable Align Breaks with parent
* the other way is to make a projected view from the parent view (with the break)
* to correct allignemtn of a view RCLICK => Alignement => Default Alignement
* to mod a break we can drag it (chang eits size)
* To delete a break view 
	* RCLICK => unbreak view
	* Seelct break => DELETE
* dimensions in a a break view reflet the actual model (Annotation=>Model items=> Entire model)
* Break views are used in orthographic views

### Lecture 29 - Detail Views

* Detail Views allow us to enlarge a part of the drawing view to clearly show small details
* we will use them to design the views of 'lec29-Detalied View_2015' part
* we create a drawing with Top view front view and isometric view
* we add dims for the entire drawing
* the detail has cramped dimensions so i delete them
* In View Layout we select 'Detail View'. we are prompted to draw a circle around the area to zoom in
* it is scaled up. we can change it RCLICK => scale
* we add dimensions to it
* if i click on detail view i get options
* we can also create Detail Views with Isometric, Section, Exploded assembly an/ot other detail views

### Lecture 30 - Alternate Position Views

* we will use 'lec60-practice-assembly' from CSWA course to make a drawing of it with front and isometric view.
* we are asked to find the angle between the min and max positions of the Post handle utilizing configurations already set for us
* we ll use alternate position views: View Layout => alternate position view => Select a view (front view)
* we can use new configuration or existing configurations from the model
* we create new config and set 2 positions
* i use Annotations => Smart Dimensions => find the angle

## Section 5 - Bill of Materials (BOM)

### Lecture 34 - Creating a Bill of Materials (BOM)

* A Bill of Materials (BOM) is usually one part of Engineering Drawings. A BOM will include all the materials, parts amd sub-assemblies required to build a specific assembly or a product
* we have the 'lec34-Creating-a-Bill-of-Materials' turbine cap assembly to make a BM out of it
* it is masde of 6 parts and one subassembly with 3 parts
* we open assembly and make a drawign out of it. we add isometric exploded view
* To add the BOM: Anootations => Tables => BOM => select the view
* We get  a lot of options to choose. we leave all default and apply.
* click on top left corner of table to get the options on left
* BOM Type
	* Top level only: only top level parts and sub assemblies. not parts of subassemblies
	* Parts only. top level and in subassemblies
	* INdented. intendet the parts of subassemblies
* To show numbers of parts in BOM on the view: Annotate => Auth Balloon => select view

### Lecture 36 - Missing Items from a Bill of Materials (BOM)

* we ll learn:
	* how to find missing parts from BOM
	* how to add missing parts fto BOM
	* how to exclude parts from the BOM
* we will build on last lectures drawing
* One way to find missing items in BOM is to look at auto balloon. missing items dont have number but *
* The other way is to look at design tree. missing items from BOM have indication 'excluded from BOM'
* I can include them: RCLICK => include to BOM. they are added instantly
* To exclude an item from BOM. in assembly view => RCLICK => open assembly. => Click on item => RCLICK => Component Properties => enable exclude from bill of materials

### Lecture 36 - Custom Properties in a Bill of Materials 

* We ll add additional info to BOM
* we ll change title add columns
* to change title douvble click to edit text
* to add column: select column => RCLICK => Add column => select type (CUSTOM PROPS => PartNo)
* Do the same for cost column
* custom properties as well as other info like the description come from the individual parts. it is added by the creator of part. 
* to change a column => RCLICK => Column Property

### Lecture 37 - Items Numbers and Sorting with Bill of Materials

* we use previous lecture drawing
* we higlight the column we want to sort => RCLICK => Sort => Select colun to sort by. 
* we can choose if we want to affect item numbers
* in BOMN props we can select the starting num

### Lecture 38 - Adding Equations to a Bill of Materials

* Equations will allow us to do simple calculations and use simple functions. we can think of it asa very simple excel sheet
* We build of previous lecture drawing
* we want total cost for all parts (num of parts * unit price)
* we want totalsum price
* find the most expensive item
* we add a column => highlight column => Σ => 'Cost' * 'QTY.'
* we add anew row => Insert => Row below
* again with  Σ selectung SUM() and highlights the vals i get the sum like excel
* i add a row and use MAX to find the most expensive item

### Lecture 39 - Configuration Groupings in a Bill of Materials

* with configs a designer is a ble to create different versions of a part or an assembly without having to create more than one SW file
* we will create a drawing for 'lec39-Configuration-Grouping'
* the part has 2 configs and the assembly has 2 configs
* we open assembly and make a new drawing of it
* we add isometric view in 2 times one for each config. 
* we select one of them in props we select reference cofiguration (config 2)
* we add a bom for each view (2 different BOMS)
* in cofig 2 we have same part 2 tmes because they are different cofigurations of same part
* in bom props Part config grouping we can select how to present them
* to put them both in one table (in bom props i click on both cofiguratiosn)


## Section 6 - Additional Drawing Competencies

### Lecture 43 - View Focus with Drawing Views

* view focus is the special area around each drawing view that contains all additional annotation and/or sketches that are not part of the Drawing view
* we make a drawing of 'lec43-View Focus' with front right and isometric view
* we are asked to vind an angle with a horiontal line that is not in the viwe
* also an angle between views
* I cannot use smart dimension for arbitrary edges across view focuses
* in the view focus i can sketch  e.g centerline to help me find the angle
* to do he cross view angle i extencd view focus of first to include second and add a centerline. 
* doubleclick on view focus and sketch outside of it

### Lecture 44 - Shown and Hidden Components in an Assembly Drawing

* we use the 'lec44-Hide-Show-Comp' which has hidded compo to do a drawing.
Hidded parts do not show in viiews
* to hide the cover part from front view: if i know which part to hide : select it in the view => RCLICK =>  SHow/Hide component
* if i dont knwo i lookit in design tree => RCLICK => Show hide
* to show hidden  components i select them in design tree RCLICK show/hide them but i cannot. they are hidden i the model
* click in view => open assembly => unhide them

### Lecture 45 -  Linked Notes

* using linked notes, we can link displayed notes to a previously defined custom property or to a website
* we open the turbine cap assembly (lec34) and make a drawing out of it (isometric exploded)
* we are asked to make a note with the nameof designer and linked it to the drawing
* Annotations => Note => leave it on the part to name
* we get a text box and an arrow. we see the linked options (hyperlink)
* i can also link property

### Lecture 46 - Measure Tool to Evaluate Measurements in the Drawing Environment

* a Measurement tool is avaialble to measure say the area of a surface
* Evaluate tab =>  Measure 
* without selecting any option if i click ona surface iget perimenter and surface
* In measurement
	* i can change measurement units

## Section 7 - Additional Stuff

### Lecture 49 - Official CSWPA-DT Sample Test

* Before taking SOLIDWORKS Certification Test: Check out [SOLIDWORKS page for the CSWPA-DT certification](https://www.solidworks.com/sw/support/29479_ENU_HTML.htm). There, you can read more about structure of the CSWPA-DT exam. 
* Also, don't forget to take the sample test provided by SOLIDWORKS. you can find it in the link above. We are also attaching it to this lecture.

### Lecture 50 - Tips when talking the CSWPA-DT Exam 

* In the case you are planning to take the Certified SOLIDWORKS Professional Advanced Drawing Tools test (CSWPA-DT), here are few tips: 
	* Make sure to save the your work separately at the end of each question. 
	* Having two screen or a bigger screen would be helpful so you can see the question and work on SOLIDWORKS for answers at the same time. 
	* In multiple choice questions, usually if your answer is off the given ones, it means you did something wrong along the way. This makes the first tip important too. 
* The CSWPA-DT exam is not easy. It will require you to pull out many different information using SOLIDWORKS Drawing Tools. It will also require you to work fast. Even though this course teaches just about all the skills needed for the exam, speed and fluency are two aspects beyond skills that take time to acquire. 
* So, take some time to digest what you learned in this course, find lots of objects around and model for practice, or look for side freelancing projects on the side, more practice will greatly increase your chance to Pass the test. 