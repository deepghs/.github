## Who We Are

We are a team focused on building infrastructure for anime data information, including images, text, audiovisuals, and more.

Our goal is to automate all common processes for handling anime information, including data acquisition, data filtering, training, step selection, and platform deployment, in order to save manpower and optimally balance quality and performance requirements.

Our team comprises a Ph.D. in Software Engineering, a Ph.D. candidate in Computer Vision, professionals in art and design, and several AI waifu enthusiasts.

We are a purely non-profit team, and all our work is completely open, without any form of charge.

## Our Technical Outputs

### dghs-imgutils

[![PyPI](https://img.shields.io/pypi/v/dghs-imgutils)](https://pypi.org/project/dghs-imgutils/)
[![GitHub stars](https://img.shields.io/github/stars/deepghs/imgutils)](https://github.com/deepghs/imgutils/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/deepghs/imgutils)](https://github.com/deepghs/imgutils/network)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/deepghs/imgutils)
[![GitHub issues](https://img.shields.io/github/issues/deepghs/imgutils)](https://github.com/deepghs/imgutils/issues)
[![GitHub pulls](https://img.shields.io/github/issues-pr/deepghs/imgutils)](https://github.com/deepghs/imgutils/pulls)
[![Contributors](https://img.shields.io/github/contributors/deepghs/imgutils)](https://github.com/deepghs/imgutils/graphs/contributors)
[![GitHub license](https://img.shields.io/github/license/deepghs/imgutils)](https://github.com/deepghs/imgutils/blob/master/LICENSE)

Project Link: https://github.com/deepghs/imgutils

Project Documentation: https://deepghs.github.io/imgutils/main/index.html

**This is a library for various common operations on anime images**, including but not limited to:

* Tachie (Difference) Detection and Clustering
* Contrastive Character Image Pretraining
* Object Detection
* Edge Detection / Lineart Generation
* Monochrome Image Detection
* Truncated Image Check
* Image Tagging
* Character Extraction

Check out the documentation for more features.

### Waifuc

[![PyPI](https://img.shields.io/pypi/v/waifuc)](https://pypi.org/project/waifuc/)
[![GitHub stars](https://img.shields.io/github/stars/deepghs/waifuc)](https://github.com/deepghs/waifuc/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/deepghs/waifuc)](https://github.com/deepghs/waifuc/network)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/deepghs/waifuc)
[![GitHub issues](https://img.shields.io/github/issues/deepghs/waifuc)](https://github.com/deepghs/waifuc/issues)
[![GitHub pulls](https://img.shields.io/github/issues-pr/deepghs/waifuc)](https://github.com/deepghs/waifuc/pulls)
[![Contributors](https://img.shields.io/github/contributors/deepghs/waifuc)](https://github.com/deepghs/waifuc/graphs/contributors)
[![GitHub license](https://img.shields.io/github/license/deepghs/waifuc)](https://github.com/deepghs/waifuc/blob/master/LICENSE)

Project Link: https://github.com/deepghs/waifuc

A **data pipeline framework based on dghs-imgutils**, supporting:
* Fast data retrieval (local disk, danbooru, pixiv, zerochan, etc.)
* Swift data filtering (comic exclusion, monochrome image exclusion, multi-character image exclusion, irrelevant character exclusion, etc.)
* Rapid data saving (local, cloud; with metadata, saved in stable diffusion dataset format, etc.)
* Quick building of processing pipelines (connecting multiple aforementioned stages)

*Note: This tool is currently a work in progress, although it's in use. It hasn't been released on PyPI and lacks comprehensive documentation. These aspects will be addressed soon.*

### Model Zoo

We manage our models and datasets on Huggingface: https://huggingface.co/deepghs

### Anything More?

In fact, our plans go beyond what's mentioned here. Other tools are continuously improving and will soon be released. Stay tuned!
