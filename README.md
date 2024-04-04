![asset safety cover](https://github.com/Olskor/AssetSafety/assets/105324070/297905d1-a8b8-40a6-848b-f4ba1c5f020b)
Note that this avatar setup works everywhere, but it's intended to be used in the respect of vrchat rules and/or only in private instances, so if you use it in a public/friend+ instance, or you uses it to have features that break the rules of vrchat, do so at your own risk. I am in no way responsible if you get caught/banned for using it in those cases.

===========================================================================
INSTALLATION:

VRC fury: simply drag and drop the vrcfury prefab inside the vrc fury prefab folder in the root of your avatar and everything would be done.

how to privatise my own asset ?: follow the pdf

===========================================================================
EXPLANATION

You probably now that VRChat provides a way to hide avatar that have suggestive/gore/excessive stuffs from the people that don’t want to see it, called Content Gating. But the big issue is that now, your avatar is completely hidden from those people making them unable to fully enjoy your avatar.

What if VRChat changed the way Content Gating works to only make marked objects or animations hidden on your avatar? A way to make those objects visible only to the people who have allowed it.

With Asset Safety, this is dead easy.

If you use that Asset to set up your avatar, only the people you allowed to use the avatar pose/interaction and who have installed the asset will be able to see marked assets on your avatar. You'll also have a button to bypass this safety and make everyone able to see your private assets and a button to make you unable to see your and other’s marked assets.

This Asset provide a prefab to make you able to see marked stuff of others and a full tutorial to setup your avatar to mark the assets you want to secure.

(I’m currently searching a way to automate the “Secure” part, because modifying a custom asset is neither safe nor easy. I already have an idea for toggle type assets (using Boolean) but I’m still struggling to find way to automate Securing for Float and Int. Don’t hesitate to send me a message if you have any idea that could help me automate that part.)

![activated](https://github.com/Olskor/AssetSafety/assets/105324070/b7f2b96c-2b49-42d9-bc24-b7fc47259ee4)
![deactivated](https://github.com/Olskor/AssetSafety/assets/105324070/b016c45c-dbf3-46a2-9a02-1e8cb4a0c3f4)

This works in two parts :

One part is only the "client" part, it's there to allow you to see the private asset a person authorizes you to see. If you don't have this part on your avatar, you won't be able to see the animations of the other person even if they authorize you.

The other part is the "provider" part, it is there to hide your chosen animations and wait for an authorized client to see the part. To protect your private assets from being seen unintentionally you have to modify your avatar using the tutorial provided in the unity package!

