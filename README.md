# The Hexagons

<img align="left" src="media/flower_favicon_full.PNG" height="100"></img>
This repository contains the data used to train and evaluate the instruction-to-execution task derived from the Hexagons dataset.
The Hexagons dataset comprises 4176 naturally-occurring visually grounded instructions rich with diverse types and levels of abstractions.
For more details about the framework of the Hexagons dataset as well as the Hexagons App and Game, 
abstraction elicitation methodology, dataset and baseline models please refer to our
[paper](https://edtechr.github.io/hexagonsDemo/#paper)
and [website](https://edtechr.github.io/hexagonsDemo/). 

## Dataset

### Download
* [Train](https://github.com/edtechr/hexagonsDemo/tree/main/data/train.jsonl.gz)
* [Dev](https://github.com/edtechr/hexagonsDemo/tree/main/data/dev.jsonl.gz)
* [Test](https://github.com/edtechr/hexagonsDemo/tree/main/data/test.jsonl.gz)


### Dataset Description

For details about the data please refer to the [dataset section](https://edtechr.github.io/hexagonsDemo/dataset/)
in our [website](https://edtechr.github.io/hexagonsDemo/) and to our [paper](https://edtechr.github.io/hexagonsDemo/#paper).

### Data Format

The dataset is split into three files of train, dev and test with with an 80/10/10 ratio of the
drawing procedures (For more details on the split rationale refer to our our [paper](https://edtechr.github.io/hexagonsDemo/#paper)). 
Each file is in a jsonl format where each entry is a dictionary of a single drawing procedure. 
A drawing procedure consists of: 

*'index': a unique identifier of a drawing procedure marked as a number between 0 and 619 such that the numbers run across train/dev/test in a random order. 
This index is synchornized with the [dataset visualization](https://edtechr.github.io/hexagonsDemo/visual/) index, in order to allow user to visualize the drawing procedure by index.

## Citation
```markdown
@article{hexagons,
  title={Draw me a Flower: {P}rocessing and Grounding Abstraction in Natural Language},
  author={Lachmy, Royi and Pyatkin, Valentina and Manevich, Avshalom and Tsarfaty, Reut},  
  year={2022},
  Eprint = {arXiv:2106.14321}  
}

```

## Terms of Use
- By downloading the data on this page the user acknowledges that their use will be restricted to research and/or academic purposes only.
- Resources on this page are licensed CC-BY 4.0, a Creative Commons license requiring Attribution (https://creativecommons.org/licenses/by/4.0/).


## Changelog
- `XX/08/2022` The Hexagons dataset was released:  TACL paper + dataset + website.
- `27/06/2021` First arXiv version of the paper was released.

 


