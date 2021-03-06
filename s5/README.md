Aidatatang_200zh is a free Chinese Mandarin speech corpus provided by Beijing DataTang Technology Co., Ltd under Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License. 

About the aidatatang_200zh corpus:

- The corpus contains 200 hours of acoustic data, which is mostly mobile recorded data.
- 600 speakers from different accent areas in China are invited to participate in the recording.
- Recordings are conducted in a quiet indoor environment. 
- The transcription accuracy for each sentence is larger than 98%.
- Detail information such as speech data coding and speaker information is preserved in the metadata file.
- Segmented transcripts are also provided.

The corpus can be downloaded from openslr: http://www.openslr.org/62/.

For more details, please visit [www.datatang.com/opensource](http://www.datatang.com/opensource).



To demonstrate that this corpus is a reasonable data resource for Chinese Mandarin speech recognition research, a baseline recipe is provided here for everyone to explore their own systems easily and quickly.

In this directory, each subdirectory contains the scripts for a sequence of experiments. The recipe in subdirectory "s5" is based on the hkust s5 recipe and aishell s5 recipe. It generates an integrated phonetic lexicon with CMU dictionary and cedit dictionary. This recipe follows the Mono+Triphone+SAT+fMLLR+DNN pipeline. In addition, this directory will be extended as scripts for speaker diarization and so on are created.

