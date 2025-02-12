# An Empirical Analysis of Uncertainty in Large Language Model Evaluations
<div align="center">
    <a>Qiujie Xie<sup>1</sup></a>&emsp;
    <a>Qingqiu Li<sup>2</sup></a>&emsp; 
    <a>Zhuohao Yu<sup>3</sup></a>&emsp; 
    <br>
    <a>Yuejie Zhang<sup>2</sup></a>&emsp;
    <a>Linyi Yang<sup>4†</sup></a>&emsp;
    <a>Yue Zhang<sup>1</sup></a>&emsp;
    <p> 
    <sup>1</sup> School of Engineering, Westlake University, 
    <sup>2</sup> School of Computer Science, Shanghai Key Laboratory of Intelligent Information Processing, Fudan University, 
    <sup>3</sup> Peking University, 
    <sup>4</sup> Department of Statistics and Data Science, Southern University of Science and Technology
    </p>
</div>


If you have any questions or concerns about this work, please feel free to contact us. We appreciate your interest and are eager to assist😊.

## Overview
As LLM-as-a-Judge emerges as a new paradigm for assessing large language models (LLMs), concerns have been raised regarding the alignment, bias, and stability of LLM evaluators. While substantial work has focused on alignment and bias, little research has concentrated on the stability of LLM evaluators. In this paper, we conduct extensive experiments involving 9 widely used LLM evaluators across 2 different evaluation settings to investigate the uncertainty in model-based LLM evaluations. We pinpoint that LLM evaluators exhibit varying uncertainty based on model families and sizes. With careful comparative analyses, we find that employing special prompting strategies, whether during inference or post-training, can alleviate evaluation uncertainty to some extent. By utilizing uncertainty to enhance LLM's reliability and detection capability in Out-Of-Distribution (OOD) data, we further fine-tune an uncertainty-aware LLM evaluator named ConfiLM using a human-annotated fine-tuning set and assess ConfiLM's OOD evaluation ability on a manually designed test set sourced from the 2024 Olympics. Experimental results demonstrate that incorporating uncertainty as additional information during the fine-tuning phase can largely improve the model's evaluation performance in OOD scenarios. We hope this work can draw broader research attention to the stability of LLM evaluators.

## Dataset
The Olympic 2024 dataset is available at https://huggingface.co/datasets/XieQJ123/Olympic-2024

## Contributing
Contributions to enhance the usability and quality of this dataset are always welcomed. If you're interested in contributing, feel free to fork this repository, make your changes, and then submit a pull request. For significant changes, please first open an issue to discuss the proposed alterations.

## Citation
If you find our work useful, please cite our paper😊:
```bibtex
@inproceedings{
xie2025an,
title={An Empirical Analysis of Uncertainty in Large Language Model Evaluations},
author={Qiujie Xie and Qingqiu Li and Zhuohao Yu and Yuejie Zhang and Linyi Yang and Yue Zhang},
booktitle={The Thirteenth International Conference on Learning Representations},
year={2025},
url={https://openreview.net/forum?id=J4xLuCt2kg}
}
```
