^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package eus_assimp
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.1 (2014-05-01)
------------------
* (eus_assimp) update files for using assimp_devel in jsk_common (`#20 <https://github.com/jsk-ros-pkg/jsk_model_tools/issues/20>`_)
* fix eus_assimp
* change store-glvertices to save-mesh-file
* add code for dumping textures
* fix default direction
* change: arguments pass to store-glvevrtices
* add check for recalc normal
* change post process methods
* add dump-to-meshfile to eus_assimp
* using assimp-read-image-file when c-assimp-load-image being defined
* change for preventing defun of unexisting function
* update for ignoring up_direction, refere to https://github.com/assimp/assimp/pull/60
* add function update-to-original-mesh for using original meshfile as visual
* fix make-cube-from-bounding-box
* add make-cube-from-bounding-box
* add make-glvertices-from-faces
* implement scale option of store-glvertices
* add assimp-read-image-file
* add :direction keyword to load-mesh-file
* add code for treating texture
* add parameter for convex_decomposition
* fix compiling with convex decomposition
* update convex decomposition code for eus_assimp
* temporary add CMakeLists.convexdecmop.txt
* add eus_assimp for eusing assimp library on EusLisp
* Contributors: YoheiKakiuchi