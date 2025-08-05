---
{"dg-publish":true,"permalink":"/extra-sources-wip/","created":"2025-08-05T12:13:13.943+02:00"}
---

[[Lens to Film Distance Chart - Essential Guide for Different Lenses, Sensors, and Film Formats\|Lens to Film Distance Chart - Essential Guide for Different Lenses, Sensors, and Film Formats]]

Recources:
https://bw-film-scanning.oguse.fr/en/index.html

https://forums.negativelabpro.com/t/integrating-sphere-as-a-uniform-backlight/6302/66

https://www.brianpritchard.com/why_colour_negative_is_orange.htm

https://www.arnogodeke.com/Blog/Trichromatic-light


https://grain2pixel.com/guide/


![Pasted image 20250121004943.png](/img/user/Assets/Pasted%20image%2020250121004943.png)


led lights order: https://www.mouser.ch/ProductDetail/416-XQEEPR650SB01

https://medium.com/@alexi.maschas/color-negative-film-color-spaces-786e1d9903a4
https://jackw01.github.io/scanlight/

blue light filter: https://www.cameranu.be/nl/p1049205/cokin-filter-p707-cyan-cc-cc40c

https://heritage-digitaltransitions.com/film-scanning-knowledge-center/
https://heritage-digitaltransitions.com/film-scanning-knowledge-center/
[https://youtu.be/LtKd1b138i0](https://youtu.be/LtKd1b138i0)
https://michael-wilmes.format.com/digitization-cn
https://www.stuweir.photography/blog/forget-negative-lab-pro-all-you-need-is-capture-one-pro-23?fbclid=PAAabI8RI4atyLAjxd1I0eZ405fsfuM5bwR0fdznMqNIlPwGjPVqYs9ONygYU_aem_AV3IQGCaV_smDgXwji8x9i57Otd3gPjBbnKY5sUNMAFXJu6d2ZJLtZITEJcrLJLZJ8U


I've been using C1 for inversion for a while now, your method is spot on. I really prefer it over the more automated options like NLP since I get full control rather than whatever a "frontier" supposedly would spit out. Some pointers I've learned over time:

- In preferences/settings makes sure to set "channel mode" to "red, green, blue channels" when you auto set the levels. I've found this much better when inverting color film. Also make sure the film rebate/light source/holder/etc are cropped out before auto leveling since they throw off the auto detection.
    
- For correcting white balance (ex shot indoors under tungsten with daylight film), you can use the levels to adjust the overall color balance. I'll drop a color readout on a neutral part of the scene (neutral gray), and then adjust the midpoints of the red and blue levels so the readout matches the green.
    
- For black and white I use the curve tool to set final contrast and tonality.
    
- For black and white I set saturation to 0 since some film bases will have a color tint. I have two styles saved, one for color and one for B&W, the only difference being the saturation.
    
- For recovering under/over images, in the level tool pushing the black/white points in towards the center can help recover the image (within reason).
    
- C1's sharpening preset "Sharpening for Soft Image 1" is a good starting point in my experience.

Hi all,

An update from my side: My custom RBG light (above) that was under development is up and running, including an overhaul of my rig:

I purchased a simple metal box that has a 55x55 mm^2 opening in it’s lid to mount the light:  

[![20230929-185054](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/a/a415317cb5e770eae5103dd50895de582f20e8e8_2_1009x999.jpeg)

20230929-1850541920×1902 338 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/a/a415317cb5e770eae5103dd50895de582f20e8e8.jpeg "20230929-185054")

The opening will allow for 35mm and MF scanning. A metal box, since the RGB matrix will get hot in use, and internal reflections will help getting the output up and homogeneous.

Mounting process and tests plus adding an opal glass diffuser (pics speak for themselves):  

[![20231001-132039](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/3/3bb6230a0fe61b2bf87d100ec9c5ac2fcbd68e2a_2_779x999.jpeg)

20231001-1320391920×2462 462 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/3/3bb6230a0fe61b2bf87d100ec9c5ac2fcbd68e2a.jpeg "20231001-132039")

  

[![20231001-144703](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/d/dcd24bb03cc6239fea3e252fc96056f0c2c3a46b_2_922x1000.jpeg)

20231001-1447031920×2082 399 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/d/dcd24bb03cc6239fea3e252fc96056f0c2c3a46b.jpeg "20231001-144703")

  

[![20231001-144718](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/d/d58c91cc75eaa40e56d8636a2e020a9ec978aa0a_2_957x1000.jpeg)

20231001-1447181920×2006 236 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/d/d58c91cc75eaa40e56d8636a2e020a9ec978aa0a.jpeg "20231001-144718")

  

[![20231001-144733](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/5/59b687caa86555666e8475a45fea354d18929901.jpeg)

20231001-1447331920×1818 130 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/5/59b687caa86555666e8475a45fea354d18929901.jpeg "20231001-144733")

Ready and final test:  

[![20231001-151901](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/c/c0dff2299e5bc2a55a7d87761e1031317890ab4a_2_903x1000.jpeg)

20231001-1519011920×2126 283 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/c/c0dff2299e5bc2a55a7d87761e1031317890ab4a.jpeg "20231001-151901")

  

[![20231001-145918](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/5/597cefdaaf984d4bcd15b80b201c0a23d90b348a_2_798x1000.jpeg)

20231001-1459181635×2047 134 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/5/597cefdaaf984d4bcd15b80b201c0a23d90b348a.jpeg "20231001-145918")

Mounted in upgraded rig:  

[![20231014-171701](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/2/269077b8a18789d2586839e532262eb6d82360f3.jpeg)

20231014-1717011920×1206 112 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/2/269077b8a18789d2586839e532262eb6d82360f3.jpeg "20231014-171701")

  

[![20231014-171722](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/0/0fa6526fc58b2c1eab090ad7a730b51a735399a6.jpeg)

20231014-1717221920×1209 115 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/0/0fa6526fc58b2c1eab090ad7a730b51a735399a6.jpeg "20231014-171722")

  

[![20231014-175225](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/d/d728884c41859f16d39f41c260f89a308a2c3a1d_2_468x1000.jpeg)

20231014-1752251384×2954 372 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/d/d728884c41859f16d39f41c260f89a308a2c3a1d.jpeg "20231014-175225")

Rig can be on a tripod, but simply on my desk is more compact and convenient.  
Rig uses Nikon Df with 105 2.8 macro with AF calibrated at 1-1.1 magnification which enables AF on each shot. The 105/2.8 lens has two threads: An aluminum hood mounts on the 62 mm outer thread, which is static, while internally the inner tube of the lens with 52mm thread can move in and out freely to focus. The hood has a front thread of 67 mm, on which a reducer 67-52mm is mounted, followed by a stack of lightweight 52 mm rings (from Nikon macro extension tubes from the 1960-1970 era). This stack is ended with an old 52mm filter from which the glass was removed, which then adapts to the bellows of a Nikon PS6 slide copy adapter. The camera can be moved up/down and sideways to align. The custom RGB light is mounted at the end, and can slide back and forth to adjust the distance. A custom “duster” is created from two record player antistatic carbon fiber brushes.

Tests showed that indeed the light provides a homogeneous intensity across the 35mm frame. R, G, and B, and overall intensity of the light are individually adjustable, and are adjusted (after the light has warmed up and is stable) to create identical R, G, and B peak position and amplitudes in LRC when the light is shining through a blank part of a color negative and imported into LRC using a custom linear profile for the camera, which was created using Adobe’s DNG profile editor. I also looked with RAW digger at the RAW data, and also there the peaks are at the same position and intensity. The bandwidth of the R, G, and B LEDs are “quite narrow”. Camera white balance is either set at 5560K (daylight) or a custom WB on the light shining through a blank part of the color negative (this doesn’t seem to matter much). The imported scans are then cropped to remove non-picture areas, “auto” tone is hit in LRC while the picture is still not inverted to balance exposure levels, but “vibrance” and “saturation” adjustments from hitting “auto” are nulled to keep everything linear (i.e., only exposure is adjusted, while color balance is retained). The picture is then **manually** inverted by inverting the tone curves for the R, G, and B channels, while throwing away regions without pixels. **A white balance is not required this way, nor is NLP (sorry)**. This is fast, and no further color interpretation is made since everything is kept linear (**NLP wants us to set a white balance on the film border and makes non-linear inversions in the R, G, and B tone curves, which shifts color balance non-linear as far as I can see**). [@Nate](https://forums.negativelabpro.com/u/nate): Please correct if my impression is wrong here).

My intent was to do everything as objective as possible (i.e. without making colors “look better” by changing the balance in a non-linear fashion), and therefore keep everything linear after I negate the orange mask in hardware with my custom RGB light, in order to let the specific tones of a used film stock come through. So far I tested on Portra 160, Portra 400, and Ektar 100 film, and indeed, the specific tones that Portra is known for seem to come out, as well as the specific bold colors that Ektar is known for. I was struggling with NLP and alternative inversion software because of the many different color interpretations of the same picture that were possible, which all might look okay or good, but I had a hard time deciding which looked best. I am well aware of statements that there is no “correct” way with color negative film, and that the color balance is a personal interpretation, but by keeping everything linear in the inversion process, and using the custom light to balance out the orange mask, I do see brilliant colors now that seem to represent what a specific film stock is known for. Whether this method is entirely correct or still an “interpretation” I don’t know.

To my surprise, I do not need/want any inversion software any longer. Manual inversion is (for me) faster since I do not have to decided between the many possible options for interpretation, and since I believe it is more accurate to extract the specific tones that a given film stock is known for (but I might be wrong). I still use NLP for B&W since it creates beautiful tones for that, but for color film, I now stay away from inversion software because of color interpretations that are outside of my control, and possibly more subjective than I can do manually while keeping everything linear. The only subjective part in my current approach is the exact position of the ends of the curves in the tone curve editor to remove a slight color cast in the shadows or highlights if I see that visually, but the curves remain linear.

Thoughts and comments welcomed…



Hi all,

A short update here. Folks have asked me whether I could show pictures of the negative and the inversion to see how manual conversion works out, so here goes. First pic is as scanned photo with my custom linear camera profile as per above post, second picture is the result of manual inversion while keeping the tone curves linear as per procedure described above, third pic is the inversion from NLP V3, settings: Basic, NLP standard, and Lab standard, keeping everything default and pressing okay (not doing roll analyses here).

Kodak Ektar 100:  

[![Screen Shot 2023-11-01 at 23.07.26](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/8/8a7a048a0ab0ddc27ff8f0f7eed2523037e2471f.jpeg)

Screen Shot 2023-11-01 at 23.07.261920×960 202 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/8/8a7a048a0ab0ddc27ff8f0f7eed2523037e2471f.jpeg "Screen Shot 2023-11-01 at 23.07.26")

  

[![Screen Shot 2023-11-01 at 23.08.12](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/5/560d47b7d7585544e549becf57391e3228328c3a.jpeg)

Screen Shot 2023-11-01 at 23.08.121920×960 237 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/5/560d47b7d7585544e549becf57391e3228328c3a.jpeg "Screen Shot 2023-11-01 at 23.08.12")

  

[![Screen Shot 2023-11-01 at 23.08.37](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/d/d9f7ecf9f15cf98bf2049e3faba07f61a0ce54f5.jpeg)

Screen Shot 2023-11-01 at 23.08.371920×960 224 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/d/d9f7ecf9f15cf98bf2049e3faba07f61a0ce54f5.jpeg "Screen Shot 2023-11-01 at 23.08.37")

Kodak Portra 160:  

[![Screen Shot 2023-11-01 at 23.11.03](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/4/485ef737557b664be8cbdd1cba0c0ecbc625fdd1.jpeg)

Screen Shot 2023-11-01 at 23.11.031920×1218 230 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/4/485ef737557b664be8cbdd1cba0c0ecbc625fdd1.jpeg "Screen Shot 2023-11-01 at 23.11.03")

  

[![Screen Shot 2023-11-01 at 23.12.31](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/f/f14cbe67140fbe90d6558f36e7a94647ac28dd88.jpeg)

Screen Shot 2023-11-01 at 23.12.311920×1218 218 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/f/f14cbe67140fbe90d6558f36e7a94647ac28dd88.jpeg "Screen Shot 2023-11-01 at 23.12.31")

The manual pictures are a bit “flatter” but that is easily improved with the brightness sliders in LRC taking care only to affect brightness, contrast, highlights etc, without distorting the color balances. NLP seems rather “off” with overly red boosted tones and cyan skies. Let’s have a look at some tone curves then. Manual first, NLP second, blue channel shown but R and G are similar:

[![Screen Shot 2023-11-01 at 21.22.43](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/a/aad4b2e29add5ba302007b20d212f9685ce9a186_2_1380x295.jpeg)

Screen Shot 2023-11-01 at 21.22.431665×356 52.8 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/a/aad4b2e29add5ba302007b20d212f9685ce9a186.jpeg "Screen Shot 2023-11-01 at 21.22.43")

  

[![Screen Shot 2023-11-01 at 21.22.56](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/5/5a7db77325f5d25077bf2397503caa6c890264fc_2_1380x295.jpeg)

Screen Shot 2023-11-01 at 21.22.561665×356 53.5 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/5/5a7db77325f5d25077bf2397503caa6c890264fc.jpeg "Screen Shot 2023-11-01 at 21.22.56")

  

[![Screen Shot 2023-11-01 at 21.27.01](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/d/dbfabdaa0be69ec732c5c37025da670bc60851fd_2_1380x295.jpeg)

Screen Shot 2023-11-01 at 21.27.011665×356 73.3 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/d/dbfabdaa0be69ec732c5c37025da670bc60851fd.jpeg "Screen Shot 2023-11-01 at 21.27.01")

  

[![Screen Shot 2023-11-01 at 21.26.51](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/e/e546882c1bafdee1e260d4eb1017d9cd8e930b5a_2_1380x295.jpeg)

Screen Shot 2023-11-01 at 21.26.511665×356 78.1 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/e/e546882c1bafdee1e260d4eb1017d9cd8e930b5a.jpeg "Screen Shot 2023-11-01 at 21.26.51")

  

[![Screen Shot 2023-11-01 at 21.33.30](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/5/566e62e68b9e845a5e52e01bfa6da387578e6890.jpeg)

Screen Shot 2023-11-01 at 21.33.301665×356 108 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/5/566e62e68b9e845a5e52e01bfa6da387578e6890.jpeg "Screen Shot 2023-11-01 at 21.33.30")

  

[![Screen Shot 2023-11-01 at 21.33.21](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/3/38301bd50234a0e72772e040c6715da349f12f5a_2_1380x295.jpeg)

Screen Shot 2023-11-01 at 21.33.211665×356 114 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/3/38301bd50234a0e72772e040c6715da349f12f5a.jpeg "Screen Shot 2023-11-01 at 21.33.21")

  

[![Screen Shot 2023-11-01 at 21.37.08](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/1/1a63e73ab0127db6d8e81cd3700ea434d6f1aeec_2_1380x295.jpeg)

Screen Shot 2023-11-01 at 21.37.081665×356 78.7 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/1/1a63e73ab0127db6d8e81cd3700ea434d6f1aeec.jpeg "Screen Shot 2023-11-01 at 21.37.08")

  

[![Screen Shot 2023-11-01 at 21.36.58](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/0/0397b88cd4e225b9ee75225b04aaac15c08c159a_2_1380x295.jpeg)

Screen Shot 2023-11-01 at 21.36.581665×356 83.8 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/0/0397b88cd4e225b9ee75225b04aaac15c08c159a.jpeg "Screen Shot 2023-11-01 at 21.36.58")

Note that these are quick edits without further ado to make the pictures look “nicer”. Just objective linear manual conversions versus what NLP creates with some default settings. Can both methods do better? Sure, perhaps the street shot manual inverted is a tad too pinkish, perhaps these are typical “Portra-look” tones, but I do not know what settings to use in NLP to get better results, while in manual I have full control and know what happens.

Perhaps NLP doesn’t like small bandwidth R, G, and B scanning and is optimized for high CRI continuous light scanning, Perhaps this manual method only works for me and my custom RGB light. I don’t really know. Perhaps Nate can chime in here. For now, however, I found something that works very well (for me) and achieves my goal of being as objective as possible in the inversion, and I do like the colors that come out of it a lot. For me it’s also (much) quicker than any inversion software since I don’t have to choose between many, many options and color balances that depend on which buttons I press, since I can never choose the one I like best, since there could always be a “better” looking option by using different buttons.

I still use NLP for B&W since I love the tones that it automatically creates with Linear Gamma on a well exposed negative, and I even considered purchasing X-Chrome for when I start from digital color files, but NLP for color negatives? Nah…maybe not anymore…










Hey all, just wanted to make a note here that I am the author the Tricolor scanning article on Medium, and while I still think tricolor scanning is the way to go I now think some of my reasoning in that article is incorrect. I believe that the explanation in this document (not authored by me) is more accurate: [Color Separation for Color Negatives using Digital Cameras - Google Docs](https://docs.google.com/document/d/1OrmYLJbnluGod663s_0ZrWyX9wF_R-uxLu4libq2c2U)

Also, I want to reiterate a point I made above about how to properly assess the results of a tricolor scan of a color negative vs a scan made with high CRI white light. The problem that we encounter with white light scans is that in order to avoid color casts in the shadows and highlights, we need to apply a per channel gamma correction. This is in effect what NLP does, calculate what per-channel gamma correction is required to correctly invert the negative. In Photoshop or Lightroom terms, this means that each channel would need an individual curves adjustments. The way color negative film is _supposed_ to work, is that you should be able to make a simple, linear intensity change to the green and blue channels. In essence, if you white balance on medium grey, the color channels should all align, and there should be no color casts in the shadows or highlights. The way you will know if the process is working is correct is by scanning a color negative image of a greyscale step progession and white-balancing on any neutral patch. Now color negative films tend to not be 100% linear in the shadows and highlights, and this is in fact a lot of what defines the characteristic “look” of a given emulsion, so this will never be perfect, but it should be close. Here’s an example of what I’m talking about:

Here is a neutral step progression scanned with high CRI white light:

[![](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/0/0d75349afb85eb315780b40bdfb7387e89e048ca_2_1380x252.jpeg)

2194×402 45.4 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/0/0d75349afb85eb315780b40bdfb7387e89e048ca.jpeg)

  
I did the following steps in Photoshop:

1. Add an invert layer.
2. Add a levels layer.
3. White balance in the levels layer on the third square from the left.
4. Add a curves layer with the adjustment mode set to luminosity to up the contrast.

Here’s what you get:

[![](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/7/75830aa7c6f3fbb649f762ca4fc9dfa3e3f6a38b_2_1380x251.jpeg)

2196×400 93.9 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/7/75830aa7c6f3fbb649f762ca4fc9dfa3e3f6a38b.jpeg)

  
I used the eyedropper with a 51x51 sample (to average out the noise), and sampled the darkest and lightest square. Keep in mind I white balance on the third from the left. The values are:

Darkest Square: R34 G27 B7  
Lightest Square: R171 G173 B182

To correct this, you would need add a curve to blue channel to add blue to the shadows and remove it from the highlights. There’s no linear adjustment that can correct this. Based in the emulsion, you might have to do this for the blue channel, or the blue and green channels.

Here’s an example with tricolor light:

[![](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/3/32dc45f079f8743dfc97bc295ce8e5b87870b4bc_2_1380x243.jpeg)

2166×382 42.4 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/3/32dc45f079f8743dfc97bc295ce8e5b87870b4bc.jpeg)

  

[![](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/c/c8814826affe74da6e1ceed03e7ba681d5a088a2.jpeg)

2160×378 74.5 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/c/c8814826affe74da6e1ceed03e7ba681d5a088a2.jpeg)

  
And the RGB sample values:

Darkest Square: R13 G16 B10  
Lightest Square: R181 G183 B186

As you can see, while the white light introduces a variation of 10-20, the tricolor variation is < 10, which is well within the range that is native to the emulsion. When you’re testing out your tricolor lights, I recommend using this as an assessment for how well your setup works. If you can invert a greyscale step progression like this by just inverting and white balancing in the middle, you’ll know you’ve got it right. I would also note that if you get this working properly, you won’t need NLP at all. You can simply invert the colors on all of your negatives, and apply a global white balance from a reference negative (assuming you did all of your scans with the same white balance).

Over the past few years, since I wrote that article, I have been working on my own custom RGB light that emits narrow-band wavelengths that align with the Status-M densitometry standard (the one developed specifically for color negative film) which I used to conduct the test above. I designed an LED grid and found a company in China that would sell me 5050 3-channel LED emitters at the custom wavelengths I needed. Then after a lot of trial and error, I used a reference design from Texas Instruments using the LM3409 driver to build a board that can drive a 3 channel LED grid at high frequency (30khz) and high resolution (10bit, for values from 0-1024) PWM.

For anyone going down this path I will warn you up-front, PCB design for use-cases with high frequency signals is not trivial. High resolution PWM in the tens of kilohertz range can involve signal transition times in the single nanoseconds. Combine a rapidly pulsing signal with a power output of a few hundred mW and you can accidentally build yourself a neat little radio jammer for certain frequencies. If you’re want to do something similar, I recommend using the analog dimming function that many LED drivers offer. I also went the route of having all of the LED channels in my grid share a cathode which simplified the layout and reduced the number of connections between the driver and emitter boards (a single ground connection vs one ground per channel). If you go this route, you’ll find that most drivers utilize a feedback mechanism that precludes a shared cathode.

Here’s the current state of my light, two recent revisions of my board, the LED grid and my partially assembled 3D printed enclosure. I’m using 3 rotary encoders to control the brightness of the individual channels, and ESP32 for all of the control logic, and a little OLED screen to display the brightness values. There’s also an interface to analog control of the brightness, and pins that provide an interface to disable and enable each channel independent of the controller for future automation.

[![](https://i.imgur.com/loQ6IfI.jpg)](https://i.imgur.com/loQ6IfI.jpg)

One major issue I have run into, and one I am still struggling with, is that it is incredibly difficult to get an even field with an LED array. With my original grid, the LED emitters were all oriented the same way, which led to the layout of the emitters getting projected onto the diffuers of the light. This resulted in a backlight that was actually a diffuse representation of the layout of the emitter, basically a faint gradient from magenta to green which stuck around no matter how much diffusion I used. You can see an example of this here:

[![](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/d/d77f90182853807daea689728e52955d7a298e2d_2_1328x1000.jpeg)

4080×3072 943 KB


](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/d/d77f90182853807daea689728e52955d7a298e2d.jpeg)

  

[![](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/b/b1c6acb00c800b789fe301e6a63da9f22a29b907_2_1328x1000.jpeg)

4080×3072 1.45 MB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/b/b1c6acb00c800b789fe301e6a63da9f22a29b907.jpeg)

My current model rotates every other emitter 180 degrees, but for some reason I now have color shifts in the corners of the fame, which persists through any level of diffusion an remains constant regardless of how I position the light (which indicates its not related to the diffusion). I’m currently in the process of figuring out if this problem is lens related, or some property of the grid that I don’t understand. I have a sneaking suspicious that the lenses on top of the LED emitters cause a lot of these problems.

[![](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/optimized/2X/4/4191beb4cab0e4bbdec07190cb2b92b18c49d6b2_2_1380x727.jpeg)

4258×2246 183 KB

](https://canada1.discourse-cdn.com/flex029/uploads/negativelabpro/original/2X/4/4191beb4cab0e4bbdec07190cb2b92b18c49d6b2.jpeg)

  
The other issue I have encountered, which also seem evidence in the tricolor scans others have posted above, is that the red channel ends up oversaturated. I’m not sure why this happens, though the easiest solution I’ve found is to reduce the intensity of the red channel relative to green and blue. If I had to hazard a guess, I’d say it has something to with the fact that the red channel in the positive is captured by the green channel in the negative, and there are two green photo sides to every one of the red and blue sites in most bayer sensors. Though that doesn’t answer why reducing the intensity of red light channel addresses the issue.

Still a lot to figure out here, but it’s great to see how many people are working on this, and I’m confident we can find solutions for the problems. I’m also doing some testing with integrating spheres at the suggestion of mightimatti, but I haven’t spend nearly as much time on that as I have on the LED array. If anyone has any question about the design process for the LED light or my tricolor scanning tests I’d be happy to answer them.