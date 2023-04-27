# Swin Transformer Code Review
Swin Transformer official implementation code에 간단한 리뷰 및 코드 분석을 주석으로 작성하였습니다. 
Swin Transformer를 공부하시는 분들께 도움이 되었으면 좋겠습니다. 


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

## Getting Started

- For **Image Classification**, please see [get_started.md](get_started.md) for detailed instructions.
- For **Object Detection and Instance Segmentation**, please see [Swin Transformer for Object Detection](https://github.com/SwinTransformer/Swin-Transformer-Object-Detection).
- For **Semantic Segmentation**, please see [Swin Transformer for Semantic Segmentation](https://github.com/SwinTransformer/Swin-Transformer-Semantic-Segmentation).
- For **Self-Supervised Learning**, please see [Transformer-SSL](https://github.com/SwinTransformer/Transformer-SSL).
- For **Video Recognition**, please see [Video Swin Transformer](https://github.com/SwinTransformer/Video-Swin-Transformer).



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



