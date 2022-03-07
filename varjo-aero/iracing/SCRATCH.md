### Level of detail

These settings are key and you can't edit them this way in the iRacing menu.

```
LODMinFPSTarget=87                                  ; Reduce LODs (see LODPct* settings) when FPS is below target. 
LODPctDynoMax=400                                   ; above 100% increases FPS and decreases LOD (25 to 500)
LODPctDynoMin=100                                   ; below 100% decreases FPS and increases LOD (25 to 500)
LODPctDynoMirrorsMax=500                            ; above 100% increases FPS and decreases LOD (25 to 500)
LODPctDynoMirrorsMin=200                            ; below 100% decreases FPS and increases LOD (25 to 500)
LODPctMax=200                                       ; above 100% increases FPS and decreases LOD (25 to 500)
LODPctMin=100                                       ; below 100% decreases FPS and increases LOD (25 to 500)
LODPctMirrorsMax=500                                ; above 100% increases FPS and decreases LOD (25 to 500)
LODPctMirrorsMin=200                                ; below 100% decreases FPS and increases LOD (25 to 500)
```

Essentially iRacing has the ability to dynamically drop the level of detail below a certain frame rate, the first field LODMinFPSTarget tells iRacing to drop the level of detail when its below 87fps. I see lots of wacky settings for VR where this is left at the default 60, whats the point in waiting until you are down at that frame rate before you start easing the load on the machine.

If you are properly driving you won't notice the eye candy anyway
Likewise stuff like Two Pass trees, Swaying trees, you won't notice unless watching a replay and you can set them up for that separately.

You can help yourself a lot changing the dynamic lod FPS to 87 so if you do get any drops it will dynamically alter the level of detail drawn in a demanding situation. No point leaving it at 60 as by then you will have a stuttery mess. Looking at the settings you have I'd be surprised if in a race situation you could run LeMans at night and get 90fps with a grid of cars. Easier tracks definitely. I know my 3090 5.1Ghz solution with a similar resolution in Steam VR can't do it with night shadow maps on. This is what I built iRacerAssistant for though, you can define high, low or track specific graphics overrides that you apply to easily get the best eye candy or the best performance with a single click.

> GaryT @ Varjo Gamers Discord

### Foveated Rendering

https://github.com/fholger/vrperfkit


No visible reduction in pic quality inside inner ring. My steamVR res is now 160% with all graphic options med/high. Before I had everything on Low/Med and 104% in steamVR.

```
upscaling:
enabled: true
method: fsr
renderScale: 0.77
sharpness: 1
radius: 0.5
applyMipBias: true

fixedFoveated:
enabled: true
innerRadius: 0.4
midRadius: 0.5
outerRadius: 0.65
```

You have to turn on (Alt +F1) foveated rendering everytime when opening game.

> Hi_Speed1 @ Varjo Gamers Discord


## Nvidia settings panel

The other thing I always do is have transparency AA in the Nvidia control panel off, I've tested it repeatedly for many years and it will always cost me a tenth or so on average lap time. 

> GaryT @ Varjo Gamers Discord

Have you got the nvidia setting to prefer max performance?
I've seen nvidia card sit at idle clocks in iRacing before

## tools

### IracingAssistant
https://forums.iracing.com/discussion/4994/iracingassistant-gary-talls-application#latest

