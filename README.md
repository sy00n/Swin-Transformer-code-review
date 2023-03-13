# Swin Transformer Code Review
해당 repo는 Swin Transformer official implementation code에 간단한 리뷰 및 코드 분석을 수행한 주석 제공 목적으로 작성되었습니다.       


주 설명은 swin_transformer.py에 기술하였습니다. 




official code github 주소는 아래 링크입니다. 


https://github.com/microsoft/Swin-Transformer   




Swin Transformer 논문 리뷰를 요약한 슬라이드는 아래 링크에서 다운받아 참고하실 수 있습니다.    


https://kfai.yonsei.ac.kr/seminar


# Swin Transformer

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/swin-transformer-v2-scaling-up-capacity-and/object-detection-on-coco)](https://paperswithcode.com/sota/object-detection-on-coco?p=swin-transformer-v2-scaling-up-capacity-and)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/swin-transformer-v2-scaling-up-capacity-and/instance-segmentation-on-coco)](https://paperswithcode.com/sota/instance-segmentation-on-coco?p=swin-transformer-v2-scaling-up-capacity-and)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/swin-transformer-v2-scaling-up-capacity-and/semantic-segmentation-on-ade20k)](https://paperswithcode.com/sota/semantic-segmentation-on-ade20k?p=swin-transformer-v2-scaling-up-capacity-and)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/swin-transformer-v2-scaling-up-capacity-and/action-classification-on-kinetics-400)](https://paperswithcode.com/sota/action-classification-on-kinetics-400?p=swin-transformer-v2-scaling-up-capacity-and)

This repo is the official implementation of ["Swin Transformer: Hierarchical Vision Transformer using Shifted Windows"](https://arxiv.org/pdf/2103.14030.pdf) as well as the follow-ups. It currently includes code and models for the following tasks:

> **Image Classification**: Included in this repo. See [get_started.md](get_started.md) for a quick start.

> **Object Detection and Instance Segmentation**: See [Swin Transformer for Object Detection](https://github.com/SwinTransformer/Swin-Transformer-Object-Detection).

> **Semantic Segmentation**: See [Swin Transformer for Semantic Segmentation](https://github.com/SwinTransformer/Swin-Transformer-Semantic-Segmentation).

> **Video Action Recognition**: See [Video Swin Transformer](https://github.com/SwinTransformer/Video-Swin-Transformer).

> **Semi-Supervised Object Detection**: See [Soft Teacher](https://github.com/microsoft/SoftTeacher).

> **SSL: Contrasitive Learning**: See [Transformer-SSL](https://github.com/SwinTransformer/Transformer-SSL).

> **SSL: Masked Image Modeling**: See [get_started.md#simmim-support](https://github.com/microsoft/Swin-Transformer/blob/main/get_started.md#simmim-support).

> **Mixture-of-Experts**: See [get_started](get_started.md#mixture-of-experts-support) for more instructions.

> **Feature-Distillation**: See [Feature-Distillation](https://github.com/SwinTransformer/Feature-Distillation).



## Citing Swin Transformer

```
@inproceedings{liu2021Swin,
  title={Swin Transformer: Hierarchical Vision Transformer using Shifted Windows},
  author={Liu, Ze and Lin, Yutong and Cao, Yue and Hu, Han and Wei, Yixuan and Zhang, Zheng and Lin, Stephen and Guo, Baining},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
  year={2021}
}
```
## Citing Local Relation Networks (the first full-attention visual backbone)
```
@inproceedings{hu2019local,
  title={Local Relation Networks for Image Recognition},
  author={Hu, Han and Zhang, Zheng and Xie, Zhenda and Lin, Stephen},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
  pages={3464--3473},
  year={2019}
}
```
## Citing Swin Transformer V2
```
@inproceedings{liu2021swinv2,
  title={Swin Transformer V2: Scaling Up Capacity and Resolution}, 
  author={Ze Liu and Han Hu and Yutong Lin and Zhuliang Yao and Zhenda Xie and Yixuan Wei and Jia Ning and Yue Cao and Zheng Zhang and Li Dong and Furu Wei and Baining Guo},
  booktitle={International Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2022}
}
```
## Citing SimMIM (a self-supervised approach that enables SwinV2-G)
```
@inproceedings{xie2021simmim,
  title={SimMIM: A Simple Framework for Masked Image Modeling},
  author={Xie, Zhenda and Zhang, Zheng and Cao, Yue and Lin, Yutong and Bao, Jianmin and Yao, Zhuliang and Dai, Qi and Hu, Han},
  booktitle={International Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2022}
}
```
## Citing SimMIM-data-scaling
```
@article{xie2022data,
  title={On Data Scaling in Masked Image Modeling},
  author={Xie, Zhenda and Zhang, Zheng and Cao, Yue and Lin, Yutong and Wei, Yixuan and Dai, Qi and Hu, Han},
  journal={arXiv preprint arXiv:2206.04664},
  year={2022}
}
```
## Citing Swin-MoE
```
@misc{hwang2022tutel,
      title={Tutel: Adaptive Mixture-of-Experts at Scale}, 
      author={Changho Hwang and Wei Cui and Yifan Xiong and Ziyue Yang and Ze Liu and Han Hu and Zilong Wang and Rafael Salas and Jithin Jose and Prabhat Ram and Joe Chau and Peng Cheng and Fan Yang and Mao Yang and Yongqiang Xiong},
      year={2022},
      eprint={2206.03382},
      archivePrefix={arXiv}
}
```

## Getting Started

- For **Image Classification**, please see [get_started.md](get_started.md) for detailed instructions.
- For **Object Detection and Instance Segmentation**, please see [Swin Transformer for Object Detection](https://github.com/SwinTransformer/Swin-Transformer-Object-Detection).
- For **Semantic Segmentation**, please see [Swin Transformer for Semantic Segmentation](https://github.com/SwinTransformer/Swin-Transformer-Semantic-Segmentation).
- For **Self-Supervised Learning**, please see [Transformer-SSL](https://github.com/SwinTransformer/Transformer-SSL).
- For **Video Recognition**, please see [Video Swin Transformer](https://github.com/SwinTransformer/Video-Swin-Transformer).

## Third-party Usage and Experiments

***In this pargraph, we cross link third-party repositories which use Swin and report results. You can let us know by raising an issue*** 

(`Note please report accuracy numbers and provide trained models in your new repository to facilitate others to get sense of correctness and model behavior`)

[12/29/2022] Swin Transformers (V2) inference implemented in FasterTransformer: [FasterTransformer](https://github.com/NVIDIA/FasterTransformer/blob/main/docs/swin_guide.md)

[06/30/2022] Swin Transformers (V1) inference implemented in FasterTransformer: [FasterTransformer](https://github.com/NVIDIA/FasterTransformer/blob/main/docs/swin_guide.md)

[05/12/2022] Swin Transformers (V1) implemented in TensorFlow with the pre-trained parameters ported into them. Find the implementation,
TensorFlow weights, code example here in [this repository](https://github.com/sayakpaul/swin-transformers-tf/).

[04/06/2022] Swin Transformer for Audio Classification: [Hierarchical Token Semantic Audio Transformer](https://github.com/RetroCirce/HTS-Audio-Transformer).

[12/21/2021] Swin Transformer for StyleGAN: [StyleSwin](https://github.com/microsoft/StyleSwin)

[12/13/2021] Swin Transformer for Face Recognition: [FaceX-Zoo](https://github.com/JDAI-CV/FaceX-Zoo)

[08/29/2021] Swin Transformer for Image Restoration: [SwinIR](https://github.com/JingyunLiang/SwinIR)

[08/12/2021] Swin Transformer for person reID: [https://github.com/layumi/Person_reID_baseline_pytorch](https://github.com/layumi/Person_reID_baseline_pytorch)

[06/29/2021] Swin-Transformer in PaddleClas and inference based on whl package: [https://github.com/PaddlePaddle/PaddleClas](https://github.com/PaddlePaddle/PaddleClas)

[04/14/2021] Swin for RetinaNet in Detectron: https://github.com/xiaohu2015/SwinT_detectron2.

[04/16/2021] Included in a famous model zoo: https://github.com/rwightman/pytorch-image-models.

[04/20/2021] Swin-Transformer classifier inference using TorchServe: https://github.com/kamalkraj/Swin-Transformer-Serve

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
