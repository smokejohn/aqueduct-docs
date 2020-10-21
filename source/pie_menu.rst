*********************
The Aqueduct Pie Menu
*********************

.. image:: ./_static/images/bl_gui_aqueduct_pie.png


Accessing the Pie Menu
======================


You can open the Aqueduct Pie Menu by pressing **Hotkey: Ctrl + Shift + A**

.. tip::
    if you want to rebind the hotkey for the Pie Menu you can do so by opening
    **Blenders preferences** and navigation to the **Keymap Section** and searching
    for the **Aqueduct Keybind**.
    
    **Edit >> Preferences... >> Keymap >> Search "Aqueduct"**

    If you want to add additional bindings for the Aqueduct Pie Menu you can do so by creating a new Keymap entry with the following values:

    =============== ======================
    Slot            Value
    =============== ======================
    **Identifier:** wm.call_menu_pie
    **Name:**       VIEW3D_MT_PIE_Aqueduct
    =============== ======================
 

Operators
=========


Tools
-----

Material QuickApply
    **Hotkey: Ctrl + Shift + Q**

    Material QuickApply mode changes your cursor to a color picker,waits
    for you to leftclick on a mesh in the viewport and picks up the material.
    Then you can leftclick on other meshes in the Viewport to apply the material
    to them. A normal leftclick will apply the material to the slot which faces
    you clicked while a **Shift + LMouse-click** will apply it to all material
    slots.

    ============== ==========================================================
    Hotkey         Description
    ============== ==========================================================
    LMouse         Apply the material to the slot the clicked face belongs to
    Shift + LMouse Apply the material to all material slots
    RMouse/Esc     Cancel
    ============== ==========================================================

Object Quickplace
    **Hotkey: Ctrl + Shift + W**

    Quickplace lets you move objects along the X, Y, Z world axis which you can
    toggle by pressing **Hotkey: W** once the operator is active. The mouse 
    wheel lets you adjust how much random offset is added to each individual
    object.

    ============== ==========================================================
    Hotkey         Description
    ============== ==========================================================
    LMouse         Apply the previewed transform to all objects
    W              Toggle transform axis (World X, Y, Z)
    MWheel-Up/Down Adjust the amount of random offset
    RMouse/Esc     Cancel the transform
    ============== ==========================================================

Object QuickRotate
    **Hotkey: Ctrl + Shift + E**
    
    QuickRotate lets you rotate objects along the X, Y, Z local axis of each
    object, you can toggle the axis by pressing **Hotkey: E**. The mosue wheel
    lets you adjust how much random rotation offset is added to each individual
    object.

    ============== ==========================================================
    Hotkey         Description
    ============== ==========================================================
    LMouse         Apply the previewed rotation to all objects
    E              Toggle rotation axis (World X, Y, Z)
    MWheel-Up/Down Adjust the amount of random offset
    RMouse/Esc     Cancel the transform
    ============== ==========================================================

Export
------

Save Material

Save Object

Save Collection


Other
-----

Open Aqueduct settings
