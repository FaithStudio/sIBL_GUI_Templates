3dsMax MR Standard - Template
=============================

Manual - Help File
==================

Table Of Content
----------------

-  `Introduction`_
-  `Options`_

   -  `Common Attributes`_
   -  `Additional Attributes`_

-  `Changes`_
-  `About`_

Introduction
------------

3dsMax MR Standard is a sIBL_GUI Template for 3dsMax and Mental Ray. It provides a bridge between 3dsMax, Mental Ray and Smart IBL.
There is an Helper Script with everything you need to use sIBL_GUI smoothly with 3dsMax here: `sIBL_GUI For 3dsMax - Helper Script <http://www.hdrlabs.com/cgi-bin/forum/YaBB.pl?num=1223936394/2#2>`_

Options
-------

Common Attributes
-----------------

-  **Scene Setup Prefix**: Defines the prefix used by the Scene Setup.
-  **Create Background**: Creates the Background Environment Branch of the Raytype Shader ( Using the High Resolution LDR file of the current IBL Set ).
-  **Create Reflection**: Creates the Reflection Environment Branch of the Raytype Shader ( Using the Reflection HDR file of the current IBL Set ).
-  **Create Lighting**: Creates the Lighting Environment Branch of the Raytype Shader ( Using the Lighting HDR file of the current IBL Set ).
-  **Create Sun**: Creates the light used as Sun.
-  **Create Dynamic Lights**: Creates the sIBL Dynamics Lights.

Additional Attributes
---------------------

-  **Display Feedback**: Displays a viewport Visual Feedback with the current IBL LDR Background image.
-  **Sun Light Type**: Creates the Sun as one of these lights type: "mrSun", "Direct", "Spot", "Omni", "Photometric", "mrAreaSpot", "mrAreaOmni".
-  **Dynamic Lights Type**: Creates the Dynamics Lights as one of these lights type: "Direct", "Spot", "Omni", "Photometric", "mrSun", "mrAreaSpot", "mrAreaOmni".
-  **Hide Lights**: Hides all current Scene lights.
-  **Create Ground**: A Plane is added to the Scene.
-  **Ground Shadow Catcher**: A Matte_Shadow_Reflection__mi Shader is assigned to the Ground.
-  **Activate Linear Workflow**: Connect a Utility_Gamma___Gain__mi Shader to the current Render Settings Lens Shader slot.

Changes
----------

`sIBL_GUI_Templates - Changes <http://kelsolaar.hdrlabs.com/sIBL_GUI/Repository/Templates/Changes/Changes.html>`_

About
-----

| **sIBL_GUI** by Thomas Mansencal - 2008 - 2014
| Copyright © 2008 - 2014 - Thomas Mansencal - `thomas.mansencal@gmail.com <mailto:thomas.mansencal@gmail.com>`_
| This software is released under terms of GNU GPL V3 license: http://www.gnu.org/licenses/
| http://www.thomasmansencal.com/