# CNN_project
### 몇 몇 유명한 새들의 이름을 제외하고 새들의 이름을 잘 알고 있지 못하는 사람들이 대부분이다. 이름이 궁금한 새들의 사진을 찍고 새의 이름을 알아내어 정보를 주는 것을 목표로 한다.


Kaggle 새 400종류의 이미지 데이터셋을 이용하여 데이터 전처리 후 CNN 모델학습 진행

- Kaggle API 이용하여 데이터셋 다운로드 및 폴더 경로 정의
<img width="481" alt="image" src="https://user-images.githubusercontent.com/73158757/203314958-731abecd-db37-47ee-b431-bc6f499952a6.png">

- CNN 기본모델 정의하기
<img width="656" alt="image" src="https://user-images.githubusercontent.com/73158757/203315208-3cd6d1a7-2535-4fef-b31e-4ffa08c3a868.png">

- 모델 레이어층 설정
<img width="490" alt="image" src="https://user-images.githubusercontent.com/73158757/203315362-db773115-3031-4217-9ddc-d1b685152cfe.png">

- 첫 학습 결과 과적합 발생 -> 해결위해 DropOut 사용
<img width="583" alt="image" src="https://user-images.githubusercontent.com/73158757/203315771-edd0c98a-2d37-47ef-baee-a9070ebf7c29.png">

- DropOut 적용 후 재학습 진행 후 성능 평가 
<img width="242" alt="image" src="https://user-images.githubusercontent.com/73158757/203315958-db799a7f-b8e2-4fc0-b40d-ac56dd18c3ce.png">
 약 57% 결과 도출
 
 -테스트 결과
 <img width="487" alt="image" src="https://user-images.githubusercontent.com/73158757/203316113-f0f7f554-c740-4a63-ae74-af40da8e52e7.png">



