Note that this avatar setup works everywhere, but it's intended to be used in the respect of vrchat rules and/or only in private instances, so if you use it in a public/friend+ instance, or you uses it to have features that break the rules of vrchat, do so at your own risk. I am in no way responsible if you get caught/banned for using it in those cases.

===========================================================================
INSTALLATION:

VRC fury: simply drag and drop the vrcfury prefab inside the vrc fury prefab folder in the root of your avatar and everything would be done.

avatar 3 manager: follow the 4 step shown in the screenshot in the tutorial folder

how to privatise my own asset ?: follow the how to secure screenshot in the tutorial folder

===========================================================================
EXPLANATION

What if VRChat offered a way to make certain objects or animations private on your avatar? A way to make those objects visible only to your friends who have authorized it. With this setup, this is dead easy.

If you use that tool to set up your avatar, only the people you allowed to use the avatar pose/interaction and who installed the asset will be able to see private assets on your avatar. You'll also have a button to bypass this safety and make everyone able to see your private assets.

To be able to see the private assets of your friend that have the safety, you need to install and enable the asset and you both need to activate interaction (the yellow hand icon under the nametag) beetween each other. note that the assets animations updates only within 6 meter around the player because of avatar dynamics limitations.

In this GitHub there's a full tutorial to setup your avatar with this safety, there's also a prefab asset here that provides all the stuff already premade for VRCFury and avatar 3 manager.

This works in two parts :

One part is only the "client" part, it's there to allow you to see the private asset a person authorizes you to see. If you don't have this part on your avatar, you won't be able to see the animations of the other person even if they authorize you.

The other part is the "provider" part, it is there to hide your chosen animations and wait for an authorized client to see the part. To protect your private assets from being seen unintentionally you have to modify your avatar using the tutorial provided in the unity package!

