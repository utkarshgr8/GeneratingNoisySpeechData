## How to use `pretty_extract.py`:

- `python pretty_extract.py -i <input_file> -c <1|0> -r <1|0> -b <int> (optional, default 1) -n <int> (optional, default 1)`
- `-c is to denote if the input audio is the clean variant or not; decides whether phase info is stored or not.`
- `-r is to denote if running in reconstruction mode (from spec to audio) or not`
- `-n is to denote the number of channels in the image`
- `-b is number of byte representation for the spectrogram image; default is 1.`

## Note: 

**When going from:**

- Audio to Spectrogram: input file is an audio.
- Spectrogram to Audio: input file is an image.

