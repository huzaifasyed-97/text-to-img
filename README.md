## Text To Coherent Image Generation 
1. Consistent self-attention for character-consistent image generation over long-range sequences. For the current implementation, the user needs to provide at least 3 text prompts for the consistent self-attention module. We recommend at least 5 - 6 text prompts for better layout arrangement.


# 🔧 Dependencies and Installation

- Python >= 3.8 (Recommend to use [Anaconda](https://www.anaconda.com/download/#linux) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html))
- [PyTorch >= 2.0.0](https://pytorch.org/)
```bash
conda create --name storydiffusion python=3.10
conda activate storydiffusion
pip install -U pip

# Install requirements
pip install -r requirements.txt
```
# How to use
## Use the jupyter notebook
You can open the `Comic_Generation.ipynb` and run the code.

## Start a local gradio demo
Run the following command:
**(Recommend)** We provide a low GPU Memory cost version, it was tested on a machine with 24GB GPU-memory(Tesla A10) and 30GB RAM, and expected to work well with >20 G GPU-memory.

### Command
python3 gradio_app_sdxl_specific_id_low_vram.py


```BibTeX
@article{zhou2024storydiffusion,
  title={StoryDiffusion: Consistent Self-Attention for Long-Range Image and Video Generation},
  author={Zhou, Yupeng and Zhou, Daquan and Cheng, Ming-Ming and Feng, Jiashi and Hou, Qibin},
  journal={arXiv preprint arXiv:2405.01434},
  year={2024}
}
