kicad 3D MCAD models in DIR .3dshapes

Author: Maurice https://launchpad.net/~easyw
Authors: will be detailed in correspondant DIR

Licence of 3D models
GNU General Public License (http://www.gnu.org/licenses/gpl.html), version 3 or later
or 
Creative Commons Attribution License (http://creativecommons.org/licenses/by/3.0/), version 3.0 or later

Notes:
The 3D models are:
- parametric models coming from technical datasheet
- FreeCAD 1:1 model (optional)
- STEP 1:1 model
- STEP 1:1 model with with text on it (optional)
- VRML 1/2.54 model (to fit perfectly kicad 3d-viewer with scale 1,1,1)
- footprint file with right orientation, scale and 3D model associated
  to the official kicad distribution
- STEP model fused in single object

most of 3D models will come from the 3D parametric lib that me and hyOzd have done, 
and many other from contributors...
Contributors name will be added to 3D model file description

Thanks to @Joan_Sparky for helping me in building up the libs! :)
Anyone interested in contribute will be very welcome!

P.S.:
Only original artwork will be accepted and NO model coming from on-line libs will be included
A list of models will refer also to model's Author credits
If fonts will be present on the model, they has to be licensed free as the word
Only models with free or GPL licence can be added to the lib

HowTo:
just copy the .3Dshapes DIRECTORY in your 3D prefix folder
(e.g. in windows C:\kicad\packages3d_MCAD or in Linux/OSX ~/packages3d_MCAD )
resulting in:
    windows
    C:\kicad\packages3d_MCAD\Capacitors_Tantalum_SMD.3dshapes
    linux/osx
    ~/packages3d_MCAD/Capacitors_Tantalum_SMD.3dshapes
    with all *.wrl and *.step files inside
    
set your KISYS3DMOD var to e.g. C:\kicad\packages3d_MCAD
It is also possible to just override kicad standard 3D modules, 
but consider that an update or a new installation of kicad
will overrite all MCAD models

to set KISYS3DMOD variable in windows open a command prompt in Administrator mode
and digit 
    SETX KISYS3DMOD C:\kicad\packages3d_MCAD

in ubuntu open a shell bash and digit
    export KISYS3DMOD ~\packages3d_MCAD
    
to export your Kicad board with components to 3D MCAD environment
just use kicad StepUp exporter and kicad StepUp tools at
http://sourceforge.net/projects/kicadstepup/

Risk disclaimer
---------------

*USE 3D CAD DATA AT YOUR OWN RISK +
DO NOT RELY UPON ANY INFORMATION FOUND HERE WITHOUT INDEPENDENT VERIFICATION.*


3D kicad libraries List
-----------------------
Resistors_SMD.3dshapes
Capacitors_SMD.3dshapes
Capacitors_Tantalum_SMD.3dshapes
Housing_SOIC.3dshapes
Housings_QFP.3dshapes