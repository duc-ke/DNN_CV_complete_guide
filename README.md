# DNN_CV_complete_guide
* **모두의 연구소(모두연) 풀잎스쿨 19기 `딥러닝 컴퓨터비전 완벽가이드`** 에서 다루는 **object detection과 segmentation** 실습
* 권철민 강사님의 '딥러닝 컴퓨터비전 완벽가이드' 강좌와 github 'DLCV_New'의 코드를 리뷰하고 재구성 하였음
  
## 모두연 풀잎스쿨 19기 - 딥러닝 컴퓨터비전 완벽 가이드 소개
* Object Detection과 Segmentation에 대한 깊이있는 이론 설명과 현업에서 바로 사용될 수 있는 많은 실습 예제들을 사전 학습한 후 스터디
* 11주간(22/04/16 - 22/06/22) 권철민 강사님의 '딥러닝 컴퓨터비전 완벽가이드' 강좌를 듣고 주 1회(토요일 오후 1:30 - 3:30) 발표
<p align="center">
<img src="https://github.com/duc-ke/DNN_CV_complete_guide/blob/main/imgs/modu_img.png" width="400" align="center">
</p>
  
## repository 구성(스터디 스케쥴)
* st01 : Object Detection & Segmentation의 이해
  * 이론(추후 정리 link 업로드 예정)
    * obj detection, segmentation 개요
    * region proposal, metrics(mAP, IOU), NMS이해
    * 데이터셋트 - Pascal VOC, MS-COCO
  * Selective search와 IoU 계산 및 bnd box 그리기 실습
  * Pascal VOC dataset 로딩 및 bnd box 그리기 실습
* st02 : RCNN 계열 Object Detecter
  * 이론(추후 link 업로드 예정)
    * RCNN(2013) 이해
    * Fast-RCNN(2015) 이해
    * Faster-RCNN(2015) 이해
  * OpenCV DNN을 이용한 Faster-RCNN object detection 실습(이미지, Video)
  * RCNN pytorch 구현하기 : [RCNN_torch github](https://github.com/duc-ke/RCNN_torch)
* st03 : tiny kitty 데이터로 MMDetection Train 실습
  * 이론(추후 link 업로드 예정)
    * MMDetection 프레임 워크 이해 - Dataset, config 구조
  * MMDetection 프레임워크 - pretrained model을 이용한 FasterRCNN inference 실습(이미지, Video)
  * MMDetection 프레임워크 - Kitti 데이터셋을 이용, 학습부터 inference까지(이미지, Video)
* st04 : Oxford Pet 데이터로 MMDetectionTrain 실습
  * 이론(추후 link 업로드 예정)
    * MMDetection 프레임 워크 이해 - config 전체 구성, Data Pipeline
  * MMDetection 프레임워크 - Oxford Pet 데이터셋을 이용, Meta file 생성, CustomDataset생성, 학습부터 inference까지(이미지)
  * MMDetection 프레임워크 - BCCD 데이터셋을 이용, COCO형태 변환, CocoDataset생성, 학습부터 inference, test-set evaluation까지(이미지)
* st05 : SSD, YOLO
* st06 : Ultralytics Yolo 실습
* st07 : RetinaNet, EfficientDet
* st08 : AutoML EfficientDet 실습, Mask RCNN
* st09 : Mask RCNN 실습(OpenCV DNN, MM Detection)
* st10 : Mask RCNN 실습(Pascal VOC, Balloon), Kaggle Nucleus Segmentation

 
## 링크
* [모두연19기-딥컵완소개페이지](https://modulabs.co.kr/product/flip18th-7042-2022-03-23-100228/)
* [inflearn-딥컴완강좌](https://www.inflearn.com/course/%EB%94%A5%EB%9F%AC%EB%8B%9D-%EC%BB%B4%ED%93%A8%ED%84%B0%EB%B9%84%EC%A0%84-%EC%99%84%EB%B2%BD%EA%B0%80%EC%9D%B4%EB%93%9C/)
* [권철민강사님 딥컴완 github](https://github.com/chulminkw/DLCV_New)
