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

* 