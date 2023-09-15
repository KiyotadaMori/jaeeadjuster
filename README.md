# jaeeadjuster
A tool to adjust durations of words between Japanese-accented English & English

The following are the overall processes.

![outline_jaeeadjuster](https://github.com/KiyotadaMori/jaeeadjuster/assets/145077560/44b0d8bc-38f2-4311-b4f7-d7f6d1ae821d)

First, it conduct English speech recognition using stable-whisper for English

Second, it converte from English to Japanese katakana using a Katakana-English dictionary or a rule

Third, it conduct phoneme segmentation using Julius & transcripts from English for Japanese-accented English 

Fourth, it search similar points of words between Japanese-accented English & English

Fifth, it adjust start points of words by accelerating audio

# Lisence
GPLv2
