# Mask generator

A python script that generates printable, cutout masks from face images. This script makes use of code from Alyssa Quek's [Face Morpher library](https://github.com/alyssaq/face_morpher).

## Installation

Clone this repo:

```
git clone https://github.com/antiboredom/mask-generator
```

Install the python requirements:

```
pip install -r requirements.txt
```

Install [imagemagick](https://www.imagemagick.org/script/index.php):

```
# for mac, it's easiest with homebrew:
brew install imagemagick
```

## Use

```
python make_mask.py [FILENAME]
```

The script will attempt to locate a face in the image you provide, cut out the face, remove the eyes, and put it on a background.

