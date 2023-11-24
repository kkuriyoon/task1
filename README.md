# task1

<https://github.com/matterport/Mask_RCNN> 들어가기
-> 레포지토리 복사

아나콘다 프롬포트에

    git clone https://github.com/matterport/Mask_RCNN
    cd 11223344
    cd Mask_RCNN
    pip3 install -r requirements.txt
    python setup.py install

2.0 에서 coco.h5 다운
2.1에서 balloon_dataset.zip, mask_rcnn_balloon.h5 다운
balloon_dataset.zip 압출 풀고 파일명 datasets로 수정
datasets 파일 바로 아래에 train과 val이 있도록 수정 

code . 입력하면 vscode 나옴

"C:/Users/kkuri/11223344/task1/Mask_RCNN" 파일 경로 수정

    python "C:/Users/kkuri/11223344/open_task1/Mask_RCNN/samples/balloon/balloon.py" train --dataset="C:/Users/kkuri/11223344/open_task1/Mask_RCNN/samples/balloon/datasets" --weights=coco

  
![KakaoTalk_20231123_211307173](https://github.com/kkuriyoon/task1/assets/128067444/25c0923d-6d98-44b1-9e8f-0b9ade24f330)



    python "C:/Users/kkuri/11223344/task1/Mask_RCNN/samples/balloon/balloon.py" splash --weights="C:/Users/kkuri/11223344/task1/Mask_RCNN/mask_rcnn_balloon.h5" --image="C:/Users/kkuri/11223344/task1/Mask_RCNN/balloon1.jpeg"

![balloon1](https://github.com/kkuriyoon/task1/assets/128067444/e47aa13f-1867-47d3-a9f8-bd44b63e2968)
![splash_20231123T213030](https://github.com/kkuriyoon/task1/assets/128067444/e95ad0e1-d652-4971-9991-269b6ee431e6)
