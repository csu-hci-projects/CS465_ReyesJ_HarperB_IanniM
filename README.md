# CS465_ReyesJ_HarperB_LiesendahlJ

Final Submission ReadME


Link to overleaf paper: https://www.overleaf.com/read/jcsknrjfgxvj#98b9cd

Link to Github - https://github.com/csu-hci-projects/CS465_ReyesJ_HarperB_IanniM

CS Project Final Video 1 - https://www.youtube.com/watch?v=OXR6smymH2c
CS Project Final Video 2 - https://www.youtube.com/watch?v=rPEJndQE59Q
CS Project Final Video 3 - 

The Final Project folder is where our source code lives. 

Download all of the files from the "Final Project" folder, create a new VR project and add the Final project folders into the Content folder of the VR project. After that add the 3 files within this PR to their corresponding directories:

VR Hands - > Content/Working_Hand_Tracking.umap
Replace existing VRPawn-> Content/VRTemplate/Blueprints/VRPawn.uasset
Global Variables -> Content/Globals/GlobalVariables/GlobalVariables.uasset
Plugins you'll need:
- Electra Player (Prevents Computer UI from freezing)

Make sure to create a first person world for the baseline experiment and a VR world for the VR experiment. 

Plugins you might need (If uassets fail importing):
- GPU Lightmass
- USD Importer
- All OpenXR Plugins off
- MetaXR enabled


*Important*
You'll need to configure the project settings slightly to get the lighting in the scene to work on VR. Within the "Rendering" section of the project settings change:

- Forward Renderer: Forward Shading = False
- Global Illumination: Dynamic Global Illumination Method = None
- VR: Instanced Stereo = False

Make sure that hand tracking is enabled in the headset settings as well. 
