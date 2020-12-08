# Transferbility_of_AEs
This is the github page for **Section VIII.B** (Audio Tranferability Experiments) of the paper "SoK: A Modularized Approach to Study the Security of Automatic Speech Recognition Systems", we put our audio adversarial examples introduced in the paper.

## Experiment 1: Transferability of the AEs based on end-to-end ASR model

In folder `Transferbility_of_AEs_based_DeepSpeech_v0.1.0_command_01/02/03/04/05)` contains adversarial samples generated based on DeepSpeech v0.1.0 with its' decoding results. Specifically, `*.mp4` is the decoding demo on [Microsoft STT Webpage](https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/), `*.txt` is the decoding text on [Deepspeech/V0.2.0](https://github.com/mozilla/DeepSpeech/releases/tag/v0.2.0) and [Deepspeech/V0.3.0](https://github.com/mozilla/DeepSpeech/releases/tag/v0.3.0), `*.json` is the decoding json result on [Microsoft STT API](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/speech-to-text).

    The commands injected in adversarial examples (AEs) are as follows.
    
    jzy-adv.wav - open the website
    msn-adv.wav - turn off the light
    wye-adv.wav - where is my car
    zdc-adv.wav - how is the weather
    zet-adv.wav - open the front door

## Experiment 2: Transferability of the AEs based on classical ASR model

In folder `Transferbility_of_AEs_based_Kaldi_ASpIRE_Chain_Model_command_01/02)` contains adversarial samples with its' decoding results on [Microsoft STT API](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/speech-to-text) and [Google STT API](https://cloud.google.com/speech-to-text).
    
    The commands injected in adversarial examples (AEs) are as follows.
    
    WAA-google-ASPIRE-Sample-0-64.wav - navigate to my home
    WAA-google-ASPIRE-Sample-0-76.wav - open youtube

## Experiment Code

Thanks to the excellent works of [Yakura et al](https://arxiv.org/abs/1810.11793) ( [Github Link](https://github.com/hiromu/robust_audio_ae) ) and [Chen et al](https://www.usenix.org/conference/usenixsecurity20/presentation/chen-yuxuan) ( [Github Link](https://github.com/RiskySignal/Devil-Whisper-Attack) ), our work had been greatly facilitated.
