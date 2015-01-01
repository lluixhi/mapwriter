mapwriter
=========

MapWriter: A minimap mod for Minecraft


Instructions for development:

1) Run "gradle setupDevWorkspace" in the mapwriter folder.

2) You should now be able to modify the code. Run "gradle build" to build the project.

Reobfuscation and Packaging:

1) Edit the version numbers in mapwriter.forge.MwForge and build.gradle.
   The version numbers in mcmod.info should automatically be set to the same
   versions as set in the build.gradle file.

2) Run "gradle reobf".

3) The reobfuscated jar should be output to the mapwriter/build/libs folder.

Acknowledgements:

* Chrixian for the code to get death markers working.
* ProfMobius for the overlay API.
* taelnia for extrautils compatibility patch.
* LoneStar144 for minimap border and arrow textures.
* jk-5 for updating the mod to be compatible with Minecraft 1.7.
* daveyliam for creating the mod, and maintaining it until this point.
