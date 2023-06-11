
# AGIQA-3K Database

The AGIQA-3K is a fine-grained AI-Generated Image (AGI) subjective quality assessment database. Please refer to our paper (AGIQA-3K: An Open Database for AI-Generated Image Quality Assessment) [here](https://arxiv.org/abs/2306.04717) for more details.

## 1. Introduction

With the rapid advancements of the text-to-image generative model, AI-generated images (AGIs) have been widely applied to entertainment, education, social media, etc. However, considering the large quality variance among different AGIs, there is an urgent need for quality models that are consistent with human subjective ratings. 

To address this issue, we extensively consider various popular AGI models, generated AGI through different prompts and model parameters, and collected subjective scores at the perceptual quality and text-to-image alignment, thus building the most comprehensive AGI subjective quality database AGIQA-3K so far. 

We believe that the fine-grained subjective scores in AGIQA-3K will inspire subsequent AGI quality models to fit human subjective perception mechanisms at both perception and alignment levels and to optimize the generation result of future AGI models.

## 2. Database Description

The **AGIQA-3K** database contains 2 types of files:

A. file.zip (AI-Generated Images)

The panbaidu downloadlink can be accessed [here](https://pan.baidu.com/s/1_Cz9-aSzUDP-aEl3siIj6g). Extraction code: AIGC
The googledrive downloadlink is [here](https://drive.google.com/file/d/1ObuOZ6YZqZuxe4oRlaf3kdOBlTRg2GE4/view?usp=sharing).

B. AIGC_MOS_Zscore.xlsx (Prompt, perception, alignemnt)

Column1: Image name

Column2: Input prompt for the generative model

Column3-4: The two adj in the prompt. (10 adj in total)

Column5: The style in the prompt. (5 style in total)

Column6-7: Normalized MOS and STD for perception subjective score.

Column8-9: Normalized MOS and STD for alignment subjective score.


## 3. Citation

If you find our work useful, please cite our paper as:
```
@misc{li2023agiqa3k,
      title={AGIQA-3K: An Open Database for AI-Generated Image Quality Assessment}, 
      author={Chunyi Li and Zicheng Zhang and Haoning Wu and Wei Sun and Xiongkuo Min and Xiaohong Liu and Guangtao Zhai and Weisi Lin},
      year={2023},
      eprint={2306.04717},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

## 4. License

The database is distributed under the MIT license.
```

## Contact
Chunyi Li, lcysyzxdxc@sjtu.edu.cn
