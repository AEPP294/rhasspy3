# Piper

Text to speech service for Rhasspy based on [Piper](https://github.com/rhasspy/piper).


## Installation

1. Copy the contents of this directory to `config/programs/tts/piper/`
2. Run `script/setup`
3. Download a model with `script/download.py`
    * Example: `script/download.py english`
    * Models are downloaded to `config/data/tts/piper` directory
4. Test with `bin/piper`
    * Example `echo 'Welcome to the world of speech synthesis.' | bin/piper --model /path/to/en-us-blizzard_lessac-medium.onnx --output_file welcome.wav`
