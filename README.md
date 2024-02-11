# MergeKit, a tools for merging pretrained LLM and create Mixture of Experts (MoE) from open-source models.
[![Python](https://img.shields.io/pypi/pyversions/tensorflow.svg)](https://badge.fury.io/py/tensorflow) [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) ![Maintainer](https://img.shields.io/badge/maintainer-@louisbrulenaudet-blue)

Mergekit uses an out-of-core approach to perform unreasonably elaborate merges in resource-constrained situations. Merges can be run entirely on CPU or accelerated with as little as 8 GB of VRAM. Many merging algorithms are supported, with more coming as they catch my attention.

When you have a merged model you're happy with, you may want to share it on the Hugging Face Hub. mergekit generates a README.md for your merge with some basic information for a model card. You can edit it to include more details about your merge, like giving it a good name or explaining what it's good at; rewrite it entirely ; or use the generated README.md as-is. It is also possible to edit your README.md online once it has been uploaded to the Hub.

## Citing this project
If you use this code in your research, please use the following BibTeX entry.

```BibTeX
@misc{louisbrulenaudet2023,
	author = {Louis Brulé Naudet},
	title = {MergeKit, a tools for merging pretrained Large Language Models and create Mixture of Experts (MoE) from open-source models},
	howpublished = {\url{https://github.com/louisbrulenaudet/mergeKit}},
	year = {2024}
}

```
## Feedback
If you have any feedback, please reach out at [louisbrulenaudet@icloud.com](mailto:louisbrulenaudet@icloud.com).