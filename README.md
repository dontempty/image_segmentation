# Unsupervised Image Segmentation

참고논문
<https://kanezaki.github.io/pytorch-unsupervised-segmentation/ICASSP2018_kanezaki.pdf>
사실상 논문을 구현한 것입니다.

이미지 객체를 분류하는 작업을 합니다.

![1](https://github.com/dontempty/image_segmentation/assets/155451345/e44bd3e7-2ec6-408b-a837-7d21ab0cdff7) | ![2](https://github.com/dontempty/image_segmentation/assets/155451345/e5fe1c31-32aa-41b5-8d87-f28c81334e8c)
---|---|

기존의 지도학습과는 다르게 라벨링이 없는 데이터를 사용해서 학습하는 방법을 소개합니다.

간단하게 설명하자면 비슷한 픽셀끼리 모아서 객체를 인식하는 작업을 진행합니다.
