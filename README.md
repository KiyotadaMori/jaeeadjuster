# jaeeadjuster
A tool to adjust durations of words between Japanese-accented English & English

The following are the overall processes.

![outline_jaeeadjuster](images/outline_jaeeadjuster.png)

First, it conduct English speech recognition using stable-whisper for English

Second, it converte from English to Japanese katakana using a Katakana-English dictionary or a rule

Third, it conduct phoneme segmentation using Julius & transcripts from English for Japanese-accented English 

Fourth, it search similar points of words between Japanese-accented English & English

Fifth, it adjust start points of words by accelerating audio

As a result, it made audio files of Japanease-accented English which have identical durations of words, ideally  

# sample reesult
Showing onset of audio
Japanese-accented English

![2023_09_28_japanese_arctic](images/2023_09_28_japanese_arctic.png)

American English

![2023_09_28_matthew](images/2023_09_28_matthew.png)

Adjusted Japanse-accented English

![2023_09_28_takumi_adjusted](images/2023_09_28_takumi_adjusted.png)

# Lisence
GPLv2
