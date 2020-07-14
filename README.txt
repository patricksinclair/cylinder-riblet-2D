2D cylindrical riblet used for some drag coefficient testing as suggested.

Lets use lid-driven flow for now until told otherwise.

Will need to modify the blockmesh generator script if we need to go to 3D.  This might be required for the integrations, but we'll see.
///////////////////////////////////////////////////////

Some simulations will also be done here where instead of having a cylindrical riblet, there will instead be a cylinder of very viscous biofilm
placed at the same location as the riblet.

We'll use the setFields cylinderToCell method. (to see a list of all the available setFields methods, replace the default/boxToCell one with some gibberish and see what errors it produces)

Set the viscosity to 1e6 instead of the usual 1e-3
