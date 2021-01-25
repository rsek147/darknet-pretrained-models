# Darknet pretrained models

Imagenet pretrained models and cfg files for darknet.

| model                 | Top-1  | BFLOPS (416x416) | cfg                                  | AlexeyAB/darknet weights                                     | ultralytics/yolov3 weights                                   | conversion from                                 |
| --------------------- | ------ | ---------------- | ------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------------------- |
| Efficientnet B0       | 77.706 | 2.650            | [cfg](cfg/efficientnet_b0.cfg)       | [Google Drive](https://drive.google.com/file/d/1ShFKALkiSzJyxrTDzz5QOJC3fwN_79Cz/view?usp=sharing) | [Google Drive](https://drive.google.com/file/d/1uhW3abg_MKbOnJXEI1xNo1TIOGzJdISC/view?usp=sharing) | pytorch-image-models (efficientnet_b0)          |
| MobileNetV3 Large 100 | 75.774 | 1.471            | [cfg](cfg/mobilenetv3_large_100.cfg) | [Google Drive](https://drive.google.com/file/d/12lOckkRkETZ0CEnDov1ufTAhSrClDWCm/view?usp=sharing) | [Google Drive](https://drive.google.com/file/d/19CNVJjmys_GpNilax6Gqz940aA89lX7g/view?usp=sharing) | pytorch-image-models (mobilenetv3_large_100)    |
| Efficientnet lite0    | 75.502 | 2.650            | [cfg](cfg/efficientnet_lite0.cfg)    | [Google Drive](https://drive.google.com/file/d/1nr54g9FNLFFJxiEo7I7kl9Z_4Bkqtgrb/view?usp=sharing) | [Google Drive](https://drive.google.com/file/d/1UDAPia-35MgU40o9oJ73CqXa6_-uk9MP/view?usp=sharing) | pytorch-image-models (efficientnet_lite0)       |
| MobileNetV2 100       | 72.950 | 2.067            | [cfg](cfg/mobilenetv2_100.cfg)       | [Google Drive](https://drive.google.com/file/d/15oRoilePiGFEwTicKXq2f2yILDC7qpvG/view?usp=sharing) | [Google Drive](https://drive.google.com/file/d/1UxBHxZ8KL736Jbitm9OAOU7r-eSl3_xH/view?usp=sharing) | pytorch-image-models (mobilenetv2_100)          |
| RegNetX 004           | 72.394 | 2.743            | [cfg](cfg/regnetx_004.cfg)           | [Google Drive](https://drive.google.com/file/d/1jK1XhY4KAGlljLrSKhkXAKfgbRs0rbNK/view?usp=sharing) | [Google Drive](https://drive.google.com/file/d/1AwrMdiNX_1x8jaNu1y14ilc5i2jHAGek/view?usp=sharing) | pytorch-image-models (regnetx_004)              |
| RegNetX 002           | 68.754 | 1.372            | [cfg](cfg/regnetx_002.cfg)           | [Google Drive](https://drive.google.com/file/d/1te6SeOv0oVIS7VC3_ZTqsdTjD9ZxdPli/view?usp=sharing) | [Google Drive](https://drive.google.com/file/d/1wHkLEq8mzuCNP3LSpjbYf1ybeRMx4bM9/view?usp=sharing) | pytorch-image-models (regnetx_002)              |
| MobileNetV3 Small 100 | 67.922 | 0.377            | [cfg](cfg/mobilenetv3_small_100.cfg) | [Google Drive](https://drive.google.com/file/d/110JKJL0z-evXZFdBOMMr4-SiCoyFHDpT/view?usp=sharing) | [Google Drive](https://drive.google.com/file/d/1YUkajUBNKkUcYPMl-Rr3Zyhw3Vg4zR1L/view?usp=sharing) | pytorch-image-models (tf_mobilenetv3_small_100) |

## Reference

- [AlexeyAB/darknet](https://github.com/AlexeyAB/darknet)
- [ultralytics/yolov3](https://github.com/ultralytics/yolov3/releases/tag/v8)
- [rwightman/pytorch-image-models](https://github.com/rwightman/pytorch-image-models)
