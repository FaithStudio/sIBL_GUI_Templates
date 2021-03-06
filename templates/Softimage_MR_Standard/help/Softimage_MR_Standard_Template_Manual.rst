Softimage MR Standard - Template
================================

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

Softimage MR Standard is a sIBL_GUI Template for Softimage and Mental Ray starting from Softimage 2011 version. It provides a bridge between Softimage, Mental Ray and Smart IBL.
There is a Softimage Addon with everything needed to use sIBL_GUI smoothly with Softimage here: `sIBL_GUI For Softimage - Helper Script <http://www.hdrlabs.com/cgi-bin/forum/YaBB.pl?num=1221392511>`_

Options
-------

Common Attributes
-----------------

-  **Scene Setup Prefix**: Defines the prefix used by the Scene Setup.
-  **Create / Update Background**: Creates / Updates the Background Environment Branch of the Raytype Shader ( Using the High Resolution LDR file of the current IBL Set ).
-  **Create / Update Reflection**: Creates / Updates the Reflection Environment Branch of the Raytype Shader ( Using the Reflection HDR file of the current IBL Set ).
-  **Create / Update Lighting**: Creates / Updates the Lighting Environment Branch of the Raytype Shader ( Using the Lighting HDR file of the current IBL Set ).
-  **Create / Update Sun**: Creates / Updates the light used as Sun.
-  **Create / Update Lights**: Creates / Updates the sIBL Dynamics Lights.

Additional Attributes
---------------------

-  **Passes Selection Dialog**: A Pass(es) selection dialog appears to choose which Pass(es) will be affected by the IBL.
-  **Override User Tweaks**: User tweaks on the Scene IBL Setup will be be overriden when updating the Scene.
-  **Update Scene**: Updates the Scene IBL Setup with the new provided informations, this option works with the "Override User Tweaks" one, there is a lot of possibilities available, it's possible to mix different IBL with those 2 options.
-  **Display Feedback**: Displays a viewport Visual Feedback with the current IBL LDR Background image.
-  **Sun Light Type**: Creates the Sun as one of these lights type: "Infinite", "Light Box", "Spot", "Point".
-  **Dynamic Lights Type**: Creates the Dynamics Lights as one of these lights type: "Infinite", "Light Box", "Spot", "Point".
-  **Hide Lights**: Hides all current Scene lights.
-  **Create Ground**: A Grid is added to the Scene.
-  **Ground Shadow Catcher**: A mip_Matte_Shadow Shader is assigned to the Ground ( Unlike Maya, in Softimage, the Background is made Transparent so it's possible to see behind the Ground Plane, object crossing through will be visible ).
-  **Physical Sun**: The Sun is created with a mia_Physical_Sun shader instead of the default soft_light one.
-  **Activate Final Gather**: Ambiant Lighting ( Ambience ) of the scene is desactivated and Final Gathering is set for the current / selected Pass(es).
-  **Activate Color Management**: Activates Softimage Color Management ( Preferences > Display > Color Management ).

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

| **sIBL_GUI** by Thomas Mansencal - 2008 - 2014
| Copyright © 2008 - 2014 - Thomas Mansencal - `thomas.mansencal@gmail.com <mailto:thomas.mansencal@gmail.com>`_
| This software is released under terms of GNU GPL V3 license: http://www.gnu.org/licenses/
| http://www.thomasmansencal.com/