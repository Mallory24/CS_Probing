# CS_Probing
The Official data repository for COLING 2022 paper _"Are Visual-Linguistic Models Commonsense Knowledge Bases?"_.

We release the two datasets used in the commonsense knowledge probing experiemnts: (1) **CWWV_IMG** (2) **CWWV_CLIP**.


## Datasets Construction Pipeline of CWWV_IMG
![Overview of CWWV_IMG Dataset Construction Pipeline](https://github.com/Mallory24/CS_Probing/blob/main/data_construction.png)

1. [**CWWV_IMG**] ([Download](https://drive.google.com/uc?export=download&id=1UdwadtWGBw1qPbXw0AX4Qbx8tAnvmUKT)):

    is automatically generated by following the procedures proposed by [Ma et al. (2019)](https://arxiv.org/abs/2011.03863).
    
    Additionaly, we rely on an effcient image retrieval process to compensate the missing image sources (please refer to our paper for details).

    | Dimensions    |  Counts  | 
    | ------------- | -------------:| 
    | part-whole    | 1,165         |
    | taxonomic     | 1,323         |
    | distinctness  | 828           |
    | similarity    | 644           |
    | quality       | 1,840         |
    | utility       | 2,090         |
    | creation      | 100           |
    | temporal      | 1,889         |
    | spatial       | 1,599         |
    | desire        | 1,781         |
    | **total**     | **13,259**    |

2. **CWWV_CLIP** [Download](https://drive.google.com/uc?export=download&id=10PsP7jMrQnUNU_oI_Z29clSMXW_Yh1Qo):
    is a subset of CWWV_IMG that contains higher quality of image-word pair according to [CLIPScore](https://github.com/jmhessel/clipscore).

    | Dimensions    |  Counts  | 
    | ------------- | -------------:| 
    | part-whole    | 170           |
    | taxonomic     | 85            |
    | distinctness  | 86            |
    | similarity    | 188           |
    | quality       | 143           |
    | utility       | 120           |
    | creation      | 8             |
    | temporal      | 154           |
    | spatial       | 144           |
    | desire        | 91            |
    | **total**     | **1,189**     |


## Citation
If you find this dataset useful for your research, please cite:
```bibtex
@inproceedings{,
  title={},
  author={},
  booktitle={},
  year={}
}
```
