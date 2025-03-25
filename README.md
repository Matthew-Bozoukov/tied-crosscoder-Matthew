# Tied Crosscoder
This is an implementation of [tied crosscoders](https://github.com/ARBORproject/arborproject.github.io/discussions/23), a variation of crosscoders especially useful for understanding how specific chat behavior arises from the base model. This is based on [ckkissane's implementation](https://github.com/ckkissane/crosscoder-model-diff-replication) of crosscoders.
* For playing with an already trained crosscoder, you can go to `analyze.ipynb.` You will have to download the crosscoder from [HuggingFace](https://huggingface.co/sa7270/tied-crosscoder)
* For training a tied crosscoder, you should run `train.ipynb`
* For the visualizations inside this project, you should use this modified version of [sae-vis](https://github.com/aranguri/crosscoder-sae-vis).
* For convenience, I included 1M tokens from lmsys and 1M tokens from the pile in the datasetes folder.
