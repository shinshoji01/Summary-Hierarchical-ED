# Paper Summary of Hierarchical ED Studies
This repository summarizes our studies related to Hierarchical Emotion Distribution (ED)

Paper Title                                                                                 | Conference/Journal                             | Demo  | Code                                        
------------------                                                                          | :----------------------------------:|:----------------------------------------------:|:----------------------------------------------:
[1] [Hierarchical emotion prediction and control in text-to-speech synthesis](https://arxiv.org/abs/2405.09171)                   | IEEE ICASSP 2024                    | [✔︎](https://shinshoji01.github.io/Text-Sequential-ED-Demo/)        | |
[2] [Fine-Grained Quantitative Emotion Editing for Speech Generation](https://arxiv.org/abs/2403.02002)                           | APSIPA ASC 2024                     | [✔︎](https://shinshoji01.github.io/Hierarchical-ED-Demo/)        | |
[3] [Hierarchical Control of Emotion Rendering in Speech Synthesis](https://arxiv.org/abs/2412.12498)                             | Submitted to IEEE Transactions      | [✔︎](https://shinshoji01.github.io/HED-Demo/)                   | |
[4] [Prediction and Control of Hierarchical Emotion Distribution in Text-to-Speech Synthesis]() | Submitted to Transactions       | [✔︎](https://shinshoji01.github.io/multi-step-prediction-HED/)    | |


- [1] We first proposed Hierarchical ED and incorporated it into the FastSpeech2 framework.
- [2] We then expanded the application of hierarchical ED to a general non-autoregressive TTS framework.
    - And, we conducted additional experiments to assess the emotion controllability and compared it to another study on fine-grained emotion intensity control.
- [3] We extend [1] to address some limitations, such as the trade-off between controllability and speech naturalness. 
    - We develop a more effective framework and feature setting for hierarchical ED.
- [4] We further explored the text-based prediction of Hierarchical ED.

# Citation
Please cite those papers if effective to your study.

[1] [Hierarchical emotion prediction and control in text-to-speech synthesis](https://arxiv.org/abs/2405.09171)
```
@INPROCEEDINGS{10445996,
  author={Inoue, Sho and Zhou, Kun and Wang, Shuai and Li, Haizhou},
  booktitle={ICASSP 2024 - 2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={Hierarchical Emotion Prediction and Control in Text-to-Speech Synthesis}, 
  year={2024},
  volume={},
  number={},
  pages={10601-10605},
  keywords={Training;Adaptation models;Linguistics;Signal processing;Predictive models;Rendering (computer graphics);Acoustics;Emotional text-to-speech;emotion prediction;emotion control},
  doi={10.1109/ICASSP48485.2024.10445996}}
```
[2] [Fine-Grained Quantitative Emotion Editing for Speech Generation](https://arxiv.org/abs/2403.02002)
```
@INPROCEEDINGS{10848721,
  author={Inoue, Sho and Zhou, Kun and Wang, Shuai and Li, Haizhou},
  booktitle={2024 Asia Pacific Signal and Information Processing Association Annual Summit and Conference (APSIPA ASC)}, 
  title={Fine-Grained Quantitative Emotion Editing for Speech Generation}, 
  year={2024},
  volume={},
  number={},
  pages={1-6},
  keywords={Asia;Information processing;Rendering (computer graphics);Text to speech;Speech processing},
  doi={10.1109/APSIPAASC63619.2025.10848721}}
```

[3] [Hierarchical Control of Emotion Rendering in Speech Synthesis](https://arxiv.org/abs/2412.12498)
```
@misc{inoue2025hierarchicalcontrolemotionrendering,
      title={Hierarchical Control of Emotion Rendering in Speech Synthesis}, 
      author={Sho Inoue and Kun Zhou and Shuai Wang and Haizhou Li},
      year={2025},
      eprint={2412.12498},
      archivePrefix={arXiv},
      primaryClass={cs.SD},
      url={https://arxiv.org/abs/2412.12498}, 
}
```
[4] [Prediction and Control of Hierarchical Emotion Distribution in Text-to-Speech Synthesis]()
```
NA
```
