# LVERN
11/19/98	Make that tool you built read more precisely with a vernier. Designing verniers isn't exactly nuclear physics but the novice may benefit from this tool.

# MANDREL
07/03/13	If you wind your own springs, you know that sizing the mandrel for winding is generally done by guesswork. Kozo Hiraoka, writing in HSM, has produced a formula for calculating the required mandrel size that should help to get you close. I coded his formula to make it easier to use. See also SPRING.

# MIXTURE
06/16/05	You probably learned how to do mixture and dilution problems in high school algebra. If you don't remember or can't derive it quickly then you need this tool.

# MRADIUS
03/16/02	An accurate technique for measuring the radius of curvature of a part. A .jpg file illustrates the setup and the program performs the requisite mathematics.

# MTAPER
05/23/03	Redgie Joy requested a program to implement the calculations for accurately measuring the included angle of a conical part using a precision V-block and a sine bar.

# OFFKEY
01/17/03	While the program name accurately describes my singing, this has nothing to do with music. If you have a cam keyed to a shaft and wish to change its phasing relative to the shaft by a few degrees, one way to do it is to make an OFFset KEY (hence the name). This program will provide the data you need to build such a key. Thanks to Ronnie Shultz for suggesting this tool and assisting in its design.

# OGIVE
11/13/01	A typical rocket nose cone shape is described as an 'ogive'. This program, an outgrowth of PROFILE, will allow you to incrementally turn such shapes on a lathe.

# OSBORNE
11/04/99	Guy Lautard documents a quick and easy iterative method to accurately center round stock in the milling machine - the so-called "Osborne Maneuver". I wrote a short program to examine how quickly this procedure converges. This is a very useful trick - read the .TXT file for a description.

# PLUG
12/30/04	Got a hole too big for your largest plug gage? Les Saunders solves this problem by measuring the hole with three smaller plug gages. I wrote a little program to help him select which three gages to use.

# POLYCONE
07/08/03	A polycone (my terminology) is a 3D figure with regular polygon base and facet-like triangular faces that meet at a central point to form a conical shape with flat sides. Tetrahedrons and pyramids are examples. This program calculates most of the dimensions and angles associated with such a shape.

# PROFILE
08/10/01	The generalized form of BALLCUT.C, capable of incrementally cutting ANY user-specified, non-critical profile on the lathe. You specify part radius at intervals along the axis of the part and it generates a cutting schedule that approximates the part profile to whatever detail your patience will tolerate. (See also SPLINE, BALLCUT.)

# PROTRAC
02/12/01	A sinebar is the preferred way to accurately set or measure an angle. On the other hand, a protractor is a very handy tool in a number of applications. Wouldn't it be nice if we could combine the accuracy of the sinebar approach with the convenience of the protractor? This discusses an attempt to do just that.

# RATIO
02/23/05	There are so many rules these days, wouldn't you just know there's a rule for numbers? Seriously, if you need to make a graduated set of anything, the "American National Standard for Preferred Numbers" is what you need to design your set so as not to attract attention from some three letter government agency. This program will do all the hard mathematical work (yes, logarithms ARE used!) for you.

# RATTLE
11/04/99	Need to measure a bore bigger than your calipers? Guy Lautard documents an old-timers' technique that works very well. I wrote a program to examine its operation and calculate the actual bore diameter. Also, if you have trouble measuring accurately with internal calipers, you should become familiar with this procedure.

# REVOLVER
08/09/00	Calm down, all you gun confiscation nazis. Go back to designing your liberal nirvanas. This has nothing to do with firearms. Rather it's a tool to do some calculations involved in building a clever (my take, anyway) type of small tool holder that makes it easier to identify which tool you're selecting.

# ROTARY
04/16/99	Doing dividing? A hole-plate-vernier dividing head is nice, but with a (very) slight loss in accuracy, a rotary table (avoid backlash - go unidirectional) can handle ANY dividing problem. Just hope the vernier isn't calibrated in deg/min/sec (thankfully, mine isn't). If it is (or is properly divided into decimal fractions of a degree), this utility will take the headache out of calculating the settings for any desired number of divisions. (Data file to print and carry to shop.) People on the web actually sell software to do this calculation for $15 - an absurdity when one considers how trivial it is. I know they want to think they're being paid for the programming effort, but is ten minutes of programming worth $15 from every user? Clearly, I think not.

# ROUNDER
02/23/05	This is a tool to assist in rounding over workpieces in the milling machine analogous to the method of BALLCUT for the lathe.

# SINE
05/16/01	A simple and accurate way to make sine bars for machining precise angles is to use two cylinders of unequal diameter held at a fixed distance. This program provides all the machinery to make the needed computations and estimate the error in the resulting angle. A second program removes the need for making the separating link in favor of an approach that uses two butted cylinders of differing diameters.

# SINEBAR
10/08/09	Calculate stack height for a sinebar and examine error behavior thereof.

# SPROCKET
02/15/03	Calculate various parameters for roller chain sprockets.

# STICK
05/22/01	Tired of running the lathe in reverse when cutting metric threads on a lathe with an Imperial leadscrew? Peter Lott, writing in Machinist's Workshop (6/01, vol. 14, no. 3) outlined a technique for getting around this annoyance. I programmed the calculations involved in his approach. As a bonus, the program also allows the technique to be applied to any combination of metric/Imperial leadscrew/thread-to-cut, a feature not covered in Peter's article.

# SLUG
06/05/03	Redgie Joy requested a program to do the calculations for chain-drilling a circular hole in a piece of metal. Also included is a program for chain-drilling circular plates from sheet stock.

# SPACEBLK
02/08/14	A tool for selecting blocks from a set to make a spacer of given size. An ASCII data file allows easy tailoring to whatever block sizes you have available. Data file for 81 block gage block set included.

# SPEED
04/22/05	Calculate the recommended machine tool speed (rpm) given material and size of workpiece/tool. An ASCII data file allows you to adjust values to your own taste and add materials I haven't covered. See also DIAM.

# TENON
06/03/00	Calculate the depth-of-cut required to cut a regular polygonal tenon on the end of a cylindrical shaft.

# TUBEWALL
02/16/02	Don't have a ball anvil mike for measuring tube wall thickness? An ordinary outside mike and this program will get the job done for you.

# UGROOVE
09/06/06	Incremental cutting of U-shaped grooves (e.g., pipe bending dies) on the lathe.

# VERNIER
04/07/04	Two plate angular verniers will make your dividing problems easier and save you a lot of hole drilling. This program does all the mathematical design work for you and gives you a table to print for using the device once built.

# VREV
10/16/09	I wanted to make a holder for some punches of varying diameter. Picture a revolver cylinder where each chamber is bored for a different caliber cartridge. How to lay out a bolt circle of holes of various diameter such that the space between adjacent holes is constant. If the punches were all the same diameter, my REVOLVER program would do the job. With differing diameters the problem gets mathematically more complex. This tool sorts out all the nasty calculations.

# WEIGHT
08/29/05	Calculate the weight of regularly (and a few oddball) shaped objects for a variety of materials. An ASCII data file allows you to tailor the available densities to your taste.

# WIRE
11/15/98	Wiring that 12 amp motor and can't decide what wire size to use? This tool will show you the recommended AWG wire gage as well as some other useful information.
