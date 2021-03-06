Softimage Arnold Standard - Template
====================================

Manual - Help File
==================

Table Of Content
----------------

-  `Introduction`_
-  `Options`_

   -  `Common Attributes`_
   -  `Additional Attributes`_
   -  `Scene Components`_

-  `Changes`_
-  `About`_

Introduction
------------

Softimage Arnold Standard is a sIBL_GUI Template for Softimage and Arnold starting from Softimage 2011 version. It provides a bridge between Softimage, Arnold and Smart IBL.
There is a Softimage Addon with everything needed to use sIBL_GUI smoothly with Softimage here: `sIBL_GUI For Softimage - Helper Script <http://www.hdrlabs.com/cgi-bin/forum/YaBB.pl?num=1221392511>`_

Options
-------

Common Attributes
-----------------

-  **Scene Setup Prefix**: Defines the prefix used by the Scene Setup.
-  **Create Background**: Creates the Background Environment Branch of the Sky Shader ( Using the High Resolution LDR file of the current IBL Set ).
-  **Create Reflection**: Creates the Reflection Environment Branch of the Sky Shader ( Using the Reflection HDR file of the current IBL Set ).
-  **Create Lighting**: Creates the Lighting Environment Branch of the Sky Shader ( Using the Lighting HDR file of the current IBL Set ).
-  **Create Sun**: Creates the light used as Sun.
-  **Create Dynamic Lights**: Creates the sIBL Dynamics Lights.

Additional Attributes
---------------------

-  **Passes Selection Dialog**: A Pass(es) selection dialog appears to choose which Pass(es) will be affected by the IBL.
-  **Display Feedback**: Displays a viewport Visual Feedback with the current IBL LDR Background image.
-  **Sun Light Type**: Create the Sun as one of these lights type: "Distant", "Quad", "Spot", "Point".
-  **Dynamic Lights Type**: Create the Dynamics Lights as one of these lights type: "Distant", "Quad", "Spot", "Point".
-  **Hide Lights**: Hides all current Scene lights.
-  **Create Ground**: A Grid is added to the Scene.
-  **Ground Shadow Catcher**: A Shadow Shader is assigned to the Ground.
-  **Use Lighting Image For Glossy**: Lighting Image branch is connected to the sIBL_Sky Glossy slot.
-  **Activate Linear Workflow**: Activates Linear Workflow.
-  **Use Arnold Gamma Correction**: Uses Arnold Gamma Correction instead of Softimage Native Color Management ( Preferences > Display > Color Management ).

Scene Components
----------------

sIBL_Controls / [ Smart IBL Controls ]
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

+-----------------------------------------------------------+
| ..  image:: resources/pictures/Smart_IBL_Controls.jpg     |
+-----------------------------------------------------------+

There are several Controls Attributes on the sIBL_Controls Annotation available in the Channel Box.

Render Togglers:

-  Activate / Deactivate the different Smart IBL Components.
-  [* CC]: Gamma / Gain Controls of the different Smart IBL Components.

Changes
----------

`sIBL_GUI_Templates - Changes <http://kelsolaar.hdrlabs.com/sIBL_GUI/Repository/Templates/Changes/Changes.html>`_

About
-----

| **sIBL_GUI** by Thomas Mansencal - 2008 - 2013
| Copyright© 2008 - 2013 - Thomas Mansencal - `thomas.mansencal@gmail.com <mailto:thomas.mansencal@gmail.com>`_
| This software is released under terms of GNU GPL V3 license: http://www.gnu.org/licenses/
| http://www.thomasmansencal.com/