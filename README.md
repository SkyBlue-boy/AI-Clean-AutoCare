# AI-Clean-AutoCare

## IT응용수학 Team Project
## AI를 이용한 맞춤 노터치 자동세차 서비스

- Transfer learning을 위한 coco weights download 하는 법(250MB라서 github에 직접 업로드 불가능)
  
  ---->

- source code에 나와 있는 방법으로 coco weights(mask_rcnn_coco.h5) download 

  ---->
  
$ python3 custom.py --dataset='dataset' --weights=coco # it will download coco weights if you don't have them


- logs 폴더에 생성되는 학습된 모델들도 용량이 커서 github에 직접 업로드 불가능 -> 직접 코드 돌려서 학습된 모델을 logs 폴더에 저장하기

- source code(damage data 학습한 모델)

  ex) mask_rcnn_damage_0001.h5
  
- My code(bird poop, dead bug data 학습한 모델)
  
  ex) mask_rcnn_birdpoop_0010.h5
