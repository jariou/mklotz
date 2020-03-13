# GEARATIO
08/14/03	If you have a set of gears (e.g., change gears from a lathe), you may want to use them to establish a ratio for some other application. This program automates the process of deciding which gears to use to obtain a desired ratio. See also GEARFIND.

Lots of people manage to acquire or scrounge a set of gears - many have them by
virtue of the change gears for threading on their lathes.

Wouldn't it be nice to have a program to figure out which of these gears to use
to obtain some step-up/down ratio for a project?  That's what this program does
for you.

The calculation is closely related to that used in CHANGE and its variants -
which, no surprise, compute required gear sets for various threading ratios on
a lathe.  I adopted the code used there for this stand-alone program.

You enter the available gears in the data file and then specify as input:

- the required ratio
-	how accurately you want that ratio matched
-	how many gear pairs to examine

and it does its job.  The more pairs you choose to examine, the longer it
takes (a bailout option is supplied if you become impatient).  Start by
examining one pair.  If you don't get your desired ratio within the specified
accuracy, increment the number of pairs to be examined in steps of one.
