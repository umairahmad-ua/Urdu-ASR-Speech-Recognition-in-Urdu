# Urdu-ASR-Speech-Recognition-in-Urdu
Fine-Tune XLSR-Wav2Vec2 for low-resource ASR with 🤗 Transformers
Wav2Vec2 is a pretrained model for Automatic Speech Recognition (ASR) and was released in September 2020 by Alexei Baevski, Michael Auli, and Alex Conneau. Soon after the superior performance of Wav2Vec2 was demonstrated on the English ASR dataset LibriSpeech, Facebook AI presented XLSR-Wav2Vec2 (click here). XLSR stands for cross-lingual speech representations and refers to XLSR-Wav2Vec2's ability to learn speech representations that are useful across multiple languages.

Similar to Wav2Vec2, XLSR-Wav2Vec2 learns powerful speech representations from hundreds of thousands of hours of speech in more than 50 languages of unlabeled speech. Similar, to BERT's masked language modeling, the model learns contextualized speech representations by randomly masking feature vectors before passing them to a transformer network.

1. To Complete run this you need to upload the Audios and Transcriptions for both test and train,
2. It was written generic so make sure to mount google drive and provide the path of Audios and Transcriptions available in drive  
3. Checkpoint will be saved in your GDrive
