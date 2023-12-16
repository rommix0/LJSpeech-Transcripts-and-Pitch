# LJ-Speech (transcripts and pitch estimations)

Basically what it says on the tin.

The transcripts archive contains both the .txt transcripts and the .TextGrid forced alignments (the phonemes are in CMU ARPABET format).

The pitch archive contains .f0.csv files, which are the pitch estimations that correspond to their respective audio.
PESTO (and CREPE for some of the audio clips) were used to perform the estimations.

Due to the upload limitations of Github, I had to split the pitch archive into parts using the split command.

Here's the command to combine the parts:
```
cat pitch.tar.gz.part00 pitch.tar.gz.part01 pitch.tar.gz.part02 > pitch.tar.gz
```