Rigid Registration
==================

This module is _NOT_ actively supported or maintained (See [#3401](http://na-mic.org/Mantis/view.php?id=3401)).
The associated code has been copied from Slicer [r23589](http://viewvc.slicer.org/viewvc.cgi/Slicer4?view=revision&revision=23589)

Note that the code is expected to compile against Slicer 4.4. That said, 
the RigidRegistration/CMakeLists.txt will have to be tweaked to ensure tests pass.

Description
-----------

Registers two images together using a rigid transform and mutual information.\n\nThis module was originally distributed as "Linear registration" but has been renamed to eliminate confusion with the "Affine registration" module.\n\nThis module is often used to align images of different subjects or images of the same subject from different modalities.\n\nThis module can smooth images prior to registration to mitigate noise and improve convergence. Many of the registration parameters require a working knowledge of the algorithm although the default parameters are sufficient for many registration tasks.\n\n

Contributors
------------

Daniel Blezek (GE)

Acknowledgements
----------------

This module was developed by Daniel Blezek while at GE Research with contributions from Jim Miller.\n\nThis work is part of the National Alliance for Medical Image Computing (NAMIC), funded by the National Institutes of Health through the NIH Roadmap for Medical Research, Grant U54 EB005149.

Licensing
---------
Materials in this repository are distributed under the following licenses:

* All software is licensed under BSD style license, with extensions to cover
contributions and other issues specific to 3D Slicer. 
See License.txt file for details.
