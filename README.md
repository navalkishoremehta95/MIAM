# MIAM: Multimodal Industrial Activity Monitoring

Code and preprocessing for the [MIAM](https://huggingface.co/datasets/ArvindSihag/MIAM) dataset (HRI 2025).

| | |
| --- | --- |
| **Dataset** | https://huggingface.co/datasets/ArvindSihag/MIAM |
| **Paper (ACM/IEEE)** | https://doi.org/10.1109/HRI61500.2025.10974158 |

## Overview

MIAM supports research on human-robot collaboration, activity recognition, and engagement prediction in industrial settings. Recordings cover realistic assembly and disassembly workflows with synchronized third-person RGB, top-view RGB and depth, and left/right-hand IMU streams.

- 22 sessions, 8 operators
- About 290 minutes of untrimmed video
- Labels for actions, object interaction, and engagement
- 70/30 train/test split on Hugging Face

## Repository layout

- `src/` - model and training code
- `preprocess/` - C1/C2 prep and IMU sync scripts

## Getting the data

1. Request access on Hugging Face: [ArvindSihag/MIAM](https://huggingface.co/datasets/ArvindSihag/MIAM)
2. Download session archives under `train/` and `test/`
3. Extract each `session_XX.zip` and follow the layout in the dataset card

License: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (research use only; redistribution not permitted).

## Citation

Please cite the ACM/IEEE HRI 2025 paper:

```bibtex
@inproceedings{mehta2025miam,
  author    = {Mehta, Naval Kishore and Arvind and Kumar, Himanshu
               and Banerjee, Abeer and Saurav, Sumeet and Singh, Sanjay},
  title     = {A Multimodal Dataset for Enhancing Industrial Task
               Monitoring and Engagement Prediction},
  booktitle = {Proceedings of the 20th ACM/IEEE International
               Conference on Human-Robot Interaction (HRI)},
  pages     = {1047--1051},
  year      = {2025},
  publisher = {IEEE},
  doi       = {10.1109/HRI61500.2025.10974158},
  url       = {https://doi.org/10.1109/HRI61500.2025.10974158}
}
```

## Contact

- Naval Kishore Mehta - naval.mehta95@gmail.com / naval.ceeri18a@acsir.res.in
- Sanjay Singh - sanjay@ceeri.res.in

Questions and issues: https://github.com/navalkishoremehta95/MIAM/issues
