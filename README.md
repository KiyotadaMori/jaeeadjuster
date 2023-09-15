# jaeeadjuster
A tool to adjust durations of words between Japanese-accented English & English

The following are the overall processes.

![outline_jaeeadjuster](https://github.com/KiyotadaMori/jaeeadjuster/assets/145077560/a24042de-bf03-486a-9f68-ed4ad0e38293)

First, it conduct English speech recognition using stable-whisper for English

Second, it converte from English to Japanese katakana using a Katakana-English dictionary or a rule

Third, it conduct phoneme segmentation using Julius & transcripts from English for Japanese-accented English 

Fourth, it search similar points of words

Fifth, it adjust start points of words by accelerating audio

# Lisence
GPLv2
