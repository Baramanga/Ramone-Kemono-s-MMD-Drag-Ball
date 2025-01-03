# Ramone Kemono's MMD Drag Ball
The most advanced Spore MMD dance animation mod to date (06-2024)

Big thanks to Mx3 for creating the first dance mods and provided much needed assitance with getting this project started! You can check out their old dance mod here: https://davoonline.com/phpBB3/viewtopic.php?t=9826

Note: Since the particle effects and animations used in this mod is very intensive, please make sure you applied the 4GB patch before hand, or it might affect your game's performance: https://www.davoonline.com/phpBB3/viewtopic.php?t=9424

This mod add 18 new MMD dance animations to your Creature Editor Test Drive, with 7 of which having special effects designed by me to give you the full experience! All the dances have camera motion imported into the game and work by moving a camera effect attached to a very tiny horn weapon parts mounted on a long multi-segmented invisible limb. It took me quite a long time to figure out how adjust the camera animation to translate it to Spore, given Spore has quite a number of quirks when it comes to animation and camera control.

![Mod thumbnail](https://github.com/Baramanga/Ramone-Kemono-s-MMD-Drag-Ball/assets/71797097/58cde407-886f-406a-a862-7cd1f12b584d)

Check out the animation preview here:
https://youtu.be/6jpHAsS8vzg?feature=shared

And to enhance the experience, especially with dance animations without effects, you should download the MMDbg mod here: https://github.com/Baramanga/MMDbg

Overall, I'm quite happy with how this turns out after a whole year of developing this mod and its gimmicks! Shoutout to all my Beta Testers, who helped me catch any mistakes during development and provided with useful feedbacks! And get ready too because I already finished importing all the animations to my second mod and it's now also open to Beta Testers!

Credits of the motion and audio resources are in the files and is displayed in the mods. Big thanks to @I-am-thedragon for their wonderous work with all the graphical assets used the dance effects!
- CynicalNightPlan (by:Ayase/cover:ARAKI) | motion:リングイネ(Linguine) | camera:yukineko_0815 | asset:I_am_THEdragon | effect:RamoneKemono
- EXID - UP&DOWN + CupcakKe Remix(miniorite) | motion+camera:Sewelina
- G(I)_DLE Nxde + CupcakKe Remix(Ranvision) | motion+camera:ren
- K/DA - MORE + CupcakKe Remix(Ranvision) | motion+camera:ladiealien
- K/DA - POPSTAR + CupcakKe Remix(Ranvision) | motion+camera:2TIGers
- MAVE Pandora CupcakKe Remix(Ranvision) | motion+camera:Natsumi San
- A Way of Life - Deep inside my mind Remix | motion+camera:Seto
- Can't Stop the Feeling! - Justin Timberlake | motion+camera:cSEHxWAGznL0Xjo
- CH4NGE (by Giga) | motion:mobiusP | camera:TheSodaWave | asset:I_am_THEdragon | effect:RamoneKemono
- Cinderella (Giga First Night Remix) | Skeleton: sour暄 | Motion: porushi
- Hiasobi / Play With Fire (by かめりあ/Camellia) | motion:mobiusP | camera:SvaliN | Effect Inspiration:TheSodaWave | asset:I_am_THEdragon | effect:RamoneKemono
- Kimagure Mercy by HachioujiP | motion:iiCxmeron_MMD | camera+facial:seitsuki
- Otome Kaibou by DECO*27 | motion:YY | facials:SAIKI | camera:Ri2Pepper | asset:I_am_THEdragon | effect:RamoneKemono
- Primary Star (by Reno) | motion:mobiusP | camera:TheSodaWave | asset:I_am_THEdragon | effect:RamoneKemono
- Satisfaction (by kz/livetune) |  motion,camera:apr | Effect Inspiration:TheSodaWave | asset:I_am_THEdragon | effect:RamoneKemono
- NAYEON POP + CupcakKe/Shenseea Remix(Ranvision) | motion+camera:Natsumi-san
- Angel Wings (A4,cover by Ray Morris) | facial+motion:nai0202 | camera:HanaMMD+miiiiina_102 | asset:I_am_THEdragon | effect:RamoneKemono
- YOASOBI - IDOL | motion:boluodesu | camera:_1upus_/Hina | asset:I_am_THEdragon | effect:RamoneKemono

Assets used:

Annoying Stage: https://bowlroll.net/file/243036

Bone parts: https://davoonline.com/phpBB3/viewtopic.php?t=9416

Thanks to the amazing @i-am-thedragon for her tireless works with importing, adjusting and creating the textures and meshes used in this project! Follow her here for her other projects and art!

https://github.com/I-am-thedragon/

https://i-am-thedragon.tumblr.com/

And follow me on [Twitter](https://x.com/RamoneKemono666), [Tumblr](https://www.tumblr.com/blog/ramonekemono), [Youtube](https://www.youtube.com/@RamoneKemono), and [Pixiv](pixiv.net/en/users/67440349) for more art and Spore modding updates!

## Instruction: 
- To get started with the mod, you can use the creature pngs provided to use the camera motions. The mod you'll need to import it: [Replicant](https://davoonline.com/phpBB3/viewtopic.php?t=9893)

![animation tester camera (beta)](https://github.com/Baramanga/Ramone-Kemono-s-MMD-Drag-Ball/assets/71797097/f3e99438-a0dd-4f15-a5f3-f625d00723fb)
![standard mount tester camera](https://github.com/Baramanga/Ramone-Kemono-s-MMD-Drag-Ball/assets/71797097/0eb993eb-d9a1-4240-9c08-5832cf84c08c)

- To add the ability to use the camera motion on your own creature of choice, follow this instruction to add the "camera mount" on your creature: ![image](https://github.com/Baramanga/Ramone-Kemono-s-MMD-Drag-Ball/assets/71797097/2ac73dc5-5908-41cf-8d40-1597a2b10848)
  If you want a type of invisible limb that isn't from Dark Injection, use these: [Creature Leaves](http://davoonline.com/phpBB3/viewtopic.php?f=125&t=9467), [Branching Evolution](http://davoonline.com/phpBB3/viewtopic.php?t=5449). The spiral shaped branch turn invisible if you shrink it small enough.
  
  The more segments/longer limbs you have for the invisible limbs, the further the "reach" of the camera, and vice versa. Play around and see what suits you best!
  
- Without the "camera mount" construction, your creature wouldn't be able to use the camera motion, although you'll still be able to see the animation and the effects. However, the mod will assume any horn(weapon) part on the lower half of your creature at the bottom most position in the middle symmetry plane to be the camera, and will try to use it as such.


## Note of usage:
- If you want to interrupt a dance, you need to interrupt the animation first (such as by jumping), instead of interrupting by switching to Edit or Paint mode. If you do the latter, the Camera will malfunction and to fix that you need to go to Test Drive (the camera will glitch out), go to Paint mode again and then to Test Drive again.
- All of these dances, camera motions and dance effects are meant to be for when the creature hasn't moved while in the test drive mode(not even spinning around). So if you moved the creature, go to paint mode, and then Test Drive again.
- Your camera fov may change after using the dances and will return to normal when you exit Test Drive mode or the Creature Editor.
