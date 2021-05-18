# Audacity2Transcript
Using python script converts the Audacity labels into a usable dataset text for custom TTS model training

Depending on the Style of transcribed labels use the approprate script.

Style A: "Hello"
audacity label: 0.938727	1.512511	Hello

Style B: "HH_MM_SS_Character_Emotion_Noise Level_Hello"
audacity label: 0.938727	1.512511	HH_MM_SS_Character_Emotion_Noise Level_Hello


The output for those files will be:

Style A: wavs/Hello.wav|Hello;

Style B: wavs/HH_MM_SS_Character_Emotion_Noise Level_Hello.wav|Hello;
