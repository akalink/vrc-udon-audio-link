# Using the AudioLink nodes within Amplify

## Templates
The following is a list of templates
### AudioLink/Lit
![AudioLink/Lit](/Materials/Template-AudioLink-Lit.PNG)
### AudioLink/Unlit
![AudioLink/Unlit](/Materials/Template-AudioLink-unlit.PNG)
  
## Functions
- 4BandAmplitude
- 4BandAmplitudyFiltered
- 4BandAmplitudeLerp
- 4BandChronotensity
- AudioLinkInfo
- AudioLinkTime
- AutoCorrelator
- AutoCorrelatorUncorrelated
- BandPulse
- BlendOverlay
- ColorChordLights
- ColorChordStrip
- DrawLine
- IsAudioLink
    - Emits white when AudioLink is present.
- Quantize
- RotateUVFill
- TranslateUV
- VU
- VUFiltered
- Waveform

## Shaders
### AudioLink/Amplify/AudioLinkAmplify_4Band
- Scoll Effect.
- Unlit.
- Band 0-4 Color Represent audio frequency from low to high respectively. 
- Smooth History smoothes scrolling effect. [verify]
- History determines scrolling speed.
### AudioLink/Amplify/AudioLinkAmplify_4BandFiltered
- Unlit
- Ignites white based on singular frequency 0-3.
- Filter Level determines speed of fade between black and white, 0 being lowest and 1 being highest
- Filter Amount determines how much Filter Level is present.
### AudioLink/Amplify/AudioLinkAmplify_AudioCorrelator
- Unlit.
### AudioLink/Amplify/AudioLinkAmplify_BasicVU
- Unlit.
### AudioLink/Amplify/AudioLinkAmplify_Chronotensity
- Unlit.
### AudioLink/Amplify/AudioLinkAmplify_ColorChordLights
- Unlit.
### AudioLink/Amplify/AudioLinkAmplify_ColorChordStrip
- Unlit.
### AudioLink/Amplify/AudioLinkAmplify_FilteredVU
- Unlit
### AudioLink/Amplify/AudioLinkAmplify_FilteredVUFlat
- Unlit
### AudioLink/Amplify/AudioLinkAmplify_Waveform
- Unlit

