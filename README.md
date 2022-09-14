# stable-diffusion
Jupyter Notebook with a proof of concept of [Stable Diffusion image generation](https://stability.ai/blog/stable-diffusion-public-release).

Code will check for GPUs and make use of them if they can. 
### Supported GPUs:
- Nvidia (CUDA)
- Apple M1/M2 (MPS)
### Not supported:
- AMD (MPS) *MPS for AMD GPUs does not fully support Stable Diffusion functions*

## Setup

### Pre-requisites
Stable Diffusions requires an API key from Hugging Face. Sign up [here](https://huggingface.co/).

The API key needs to be set as an environmental variable from the CLI or in an .env file in the root directory.
CLI:
```bash
export HG_TOKEN=<API Key>
```
.env file:
```bash
HG_TOKEN=<API Key>
```

### Installation
```bash
python3 -m pip install -r requirements.txt
```
