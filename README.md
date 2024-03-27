This is a complete Unity Project.  You can download it and open it as a project in Unity.  I believe you will need to install XR Interaction Toolkit, 
the XR Interaction Toolkit Starter Assets Sample and XR Plugin Management.  You will also need to do the XR Plugin Management setup in Edit -> Project
Settings, as normally done.

The project is just a green plane with a couple of cubes, a sphere, a capsule and a cylinder.  The entire green plane is teleportable.  Push the right 
controller joystick full forward and hold to cast a ray in front of you.  The ray is green indicating that a teleport will be successful.  Release the 
joystick to jump to the end point of the ray.  Most of the objects on the plane are grabbable and can be grabbed using the controller ray.  The 
interactable ray is blue and will extend and bend toward an object that can be grabbed.  Grab it with the ray using the grab button.  With the object
held using the ray, you can twirl it by moving the joystick left or tight.  You can move it closer or further away by pushing the joystict Aft or 
Forward respectively.

There is a direction indicating reticle at the end of the green ray that indicates the orientation you will have when you teleport.  The 
directable reticle is controlled by moving the right controller joystick left and right, while still holding it full forward.  You can turn the 
reticle 180 degrees left and 180 degrees right.  Imagine that we are successful getting the destination view to appear in a portal window just in
front of the player.  This left/right reticle control is what I imagine could be used to scan the destination view in the portal window left and right.

Setting this project up to have Raycast Teleport, remote grab, locomotion by flying, rotation using right or left controller joystick, Fore and Aft 
movement on the left controller and Raycast/180 rotate on the right controller, and gaze (head directed) steering took about an hour.  All of that
functionality is in a pre-packaged object in the XR Interaction Toolkit Samles set, that can be drug to the Hierarchy panel.  After that you make a couple 
of changes/additions to customize the functions as desired and it all just works.  I generally followed Ryan Murray's video, "Setup Teleporting in Unity
XR Interaction Toolkit".
