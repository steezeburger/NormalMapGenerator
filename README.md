# Normal Map Generator

Normal Map Generator is a tool written in Python to generate normal maps from plain images.

## Install dependencies:

`$ python -m venv .venv`

`$ source ./venv/bin/activate`

`(.venv) $ pip install -r requirements`

## Usage

```
(.venv) $ ./normal_map_generator.py input_file output_file \
  --smooth SMOOTH_VALUE \
  --intensity INTENSITY_VALUE
```

### Required positional arguments:

* `input_file` - path to input image
* `output_file` - path to output filename

### Optional arguments:
* `-h, --help` - show help message
* `-s, --smooth` - smooth gaussian blur applied to the image
* `-it, --intensity` - intensity of normal map
