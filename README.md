# CS465_ReyesJ_HarperB_LiesendahlJ

Final Submission ReadME


Link to overleaf paper: https://www.overleaf.com/read/jcsknrjfgxvj#98b9cd

Link to Github - https://github.com/csu-hci-projects/CS465_ReyesJ_HarperB_IanniM

CS Project Final Video 1 - https://www.youtube.com/watch?v=OXR6smymH2c
Download Link - https://colostate-my.sharepoint.com/personal/georeyes_colostate_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fgeoreyes%5Fcolostate%5Fedu%2FDocuments%2FMicrosoft%20Teams%20Chat%20Files%2FFinal%5FV1%2Emp4&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E7eab0025%2D971b%2D4402%2Da531%2D06dbf66af897
CS Project Final Video 2 - https://www.youtube.com/watch?v=rPEJndQE59Q
Download Link - https://colostate-my.sharepoint.com/personal/benharpr_colostate_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fbenharpr%5Fcolostate%5Fedu%2FDocuments%2FMicrosoft%20Teams%20Chat%20Files%2FCS465Project%2Emp4&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E81ef02ec%2D192a%2D4e2f%2D8ff6%2D8b0b1dca2aeb
CS Project Final Video 3 - 

Download Link - https://colostate-my.sharepoint.com/personal/georeyes_colostate_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fgeoreyes%5Fcolostate%5Fedu%2FDocuments%2FMicrosoft%20Teams%20Chat%20Files%2FVideo3%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Effa8337b%2D552a%2D4f02%2D9da9%2Db24665a02b87&ga=1

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

Project RR Graph  - it has the relevant classes and their relationships plus what they lok like and who implemented what
