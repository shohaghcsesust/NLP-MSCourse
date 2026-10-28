Voice input methodology for the Speech Recognition (STT) practical experiment
==============================================================================

This automated environment has no live microphone or human speaker available.
To still produce a genuine, reproducible STT experiment, the voice input used
here is the same gTTS-synthesized audio already validated as clearly
intelligible in the companion TTS experiment (TTS_Experiment/, 100% round-trip
accuracy for English and Hindi). This is the most defensible standardized
voice source available in this environment: unlike a single human speaker, it
is perfectly reproducible by anyone re-running the scripts, and unlike scraped
third-party audio, it carries no licensing ambiguity.

Files:
  S1_clean.wav, S2_clean.wav, S3_clean.wav, S4_clean.wav, S5_clean.wav
      - the 5 core sentences (English/Bangla/Hindi, short/long), clean audio
  S1-slow_clean.wav
      - S1 re-synthesized at a slower speaking rate (speaking-rate variation)
  S1_noise_mild.wav   (15 dB SNR added white Gaussian noise)
  S1_noise_heavy.wav  (0 dB SNR added white Gaussian noise)
      - S1 with synthetically added background noise (noise-robustness variation)

All files are 16 kHz mono PCM WAV, converted/generated deterministically by
scripts in this project so the whole experiment can be re-run exactly.
