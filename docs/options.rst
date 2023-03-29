#####################################
Options
#####################################

When the *Mesh Mat* object is created, it has a modifier attached to it which controls all the settings for the add-on.


=====================
Source Object
=====================

The object that will be deformed and wrapped around the :ref:`Target Object`'s :ref:`UV Map<Target Object UV Map>`.

=======================
Target Object
=======================

The object that the :ref:`Source Object` will wrap around.

=======================
Target Object UV Map
=======================

The name of the UV Map on the Target Object used to project the Source Object.

==============================================
Target Object Vertex Group
==============================================

If specified, the Source Object will only be wrapped to faces with vertices assigned to this Vertex Group defined on the Target Object.

=======================
Height
=======================

Because a UV Map does not really have height information, this parameter controls the height of the :ref:`Source Object` when it is projected onto the :ref:`Target Object` surface.

=======================
Use Face Normals
=======================

By default, the Add-On will use the vertex normals of the :ref:`Target Object` to determine how the :ref:`Source Object` is projected.  On lower poly meshes, it can sometimes produce more accurate results if the :ref:`Target Object`'s' Face Normals are used instead.

=======================
Offset Position
=======================

=======================
Offset Angle
=======================

=======================
Offset Scale
=======================

=======================
Preview UVs
=======================

=======================
Preview Position
=======================

The following controls the parameters of how the source object is projected onto the Target Object:

Direction
--------------------

