## qc_comfyui_bizyair

ComfyUI + BizyAir with package management by poetry

## pre
* python3.11
* pip install poetry 
* get api key from [siliconflow](https://account.siliconflow.cn/)
* add api_key = xxx at custom_nodes/BizyAir/api_key.ini, if no the script of api_key.ini, you can create one

```
PS: api_Key.init.example 

[auth]
api_key = xxx

```

## run

1. poetry shell            # Open virtual environment
2. poetry install          # install packages
3. poetry run python main.py
   
## GUI
open http://127.0.0.1:8188, laughter

## appreciate 
[ComfyUI](https://github.com/comfyanonymous/ComfyUI)
[BizyAir](https://github.com/siliconflow/BizyAir)

## api request
TODO