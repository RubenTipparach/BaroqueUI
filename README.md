BaroqueUI_Bridge
=========

This repo is to update baroque to newer versions of unity, and make it compatible with a wider range of toolsets out there,
like VRTK, newer versions of Steam VR, etc. This is a UI tool that I very much like for its more tactile approach to interacting with UI
in VR, vs the traditional point click methods of standard raycasting UI systems.

Setup:
	- Attach SteamVRBaroqueInterface to [CameraRig] where SteamVR_ControllerManager lives
	- Make sure you have SteamVRBaroqueInterface script to run before the default settings
		- Set [Project Settings] -> [Script Execution Order] to -1 or earlier