# KTH DT2112-Speech Technology
A prominent problem in speech recognition is how to deal with noise, i.e. features of recorded 
audio orthogonal or detrimental to the recognition of the included speech. The goal of this 
project is to investigate a section of this problem by training an ASR system on clean and dirty 
audio. The pre-trained model Wav2Vec2 was used with appropriate adjustments to fit the needs of the project. 
Recording data was augmented by adding some noise. By comparing the performance of ASR systems trained 
with noisy and clean audio in transcriptions of noisy audio, we were able to show that the model 
fine-tuned on noisy data performed much better than the one fine-tuned on clean audios. 
Thus, the ASR system is partially robust to the added noise.

