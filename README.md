# speech-to-speech

```
conda create --name <env_name> python=3.7
conda activate <env_name>
```

## Install speech-to-speech dependencies

```
git clone https://github.com/Open-Speech-EkStep/speech-to-speech.git
cd speech-to-speech
bash s2s_installs.sh
pip install -r requirements.txt

```

## ASR models
```
Update ASR model paths in: infer.sh
```

## TTS models
```
Update vakyansh-TTS model paths in: tts_inference.py
```

# Run 

To run a Gradio interface for Speech to Speech conversion from English to Hindi, simply run:
```
bash infer.sh
```
