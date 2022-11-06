# text-to-speech
A small text-to-speech (PDF or TXT) shell script utilizing `pdftotext`, `say`, and `ffmpeg`.

# Dependencies
* `pdftotext` (in case you have a PDF as input file): https://formulae.brew.sh/cask/pdftotext
* `say` (is part of MacOS)
* `ffmpeg` (to convert voice to audio, i.e. aiff > m4a): https://formulae.brew.sh/formula/ffmpeg

# Supported languages
* DE
* EN
* ***fell free to fork***

# How to use it?
```shell
./text-to-speech EN in.pdf
./text-to-speech DE in.pdf
./text-to-speech EN in.txt
```
