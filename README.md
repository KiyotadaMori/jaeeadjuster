# jaeeadjuster
A tool to adjust durations of words between Japanese-accented English & English

The following are the overall processes.

![outline_jaeeadjuster](https://github.com/KiyotadaMori/jaeeadjuster/assets/145077560/44b0d8bc-38f2-4311-b4f7-d7f6d1ae821d)

First, it conduct English speech recognition using stable-whisper for English

Second, it converte from English to Japanese katakana using a Katakana-English dictionary or a rule

Third, it conduct phoneme segmentation using Julius & transcripts from English for Japanese-accented English 

Fourth, it search similar points of words between Japanese-accented English & English

Fifth, it adjust start points of words by accelerating audio

As a result, it made audio files of Japanease-accented English which have identical durations of words, ideally  

# sample reesult
Showing onset of audio
Japanese-accented English

![2023_09_28_japanese_arctic](https://github.com/KiyotadaMori/jaeeadjuster/assets/145077560/f7e52038-8ad8-402f-b2ef-0f860139c257)

American English

![2023_09_28_matthew](https://github.com/KiyotadaMori/jaeeadjuster/assets/145077560/c3c0693b-3b8b-4b9c-bec9-4088f493ac6b)

Adjusted Japanse-accented English

![2023_09_28_takumi_adjusted](https://github.com/KiyotadaMori/jaeeadjuster/assets/145077560/d7d2d4bf-4b20-412d-9bf5-bf8e07c6df58)

# Lisence
GPLv2
