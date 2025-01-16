# YOLOv8-YOLO-NAS-PCB
> KSC 2023_YOLOv8과 YOLO-NAS를 이용한 인쇄 회로 기판(PCB) 결함 탐지 및 분류
---
#### 📖 개요
본 프로젝트는 객체 탐지 모델 YOLOv8과 YOLO-NAS를 활용하여 **인쇄 회로 기판(PCB)** 의 결함을 효율적으로 탐지하고 분류합니다. PCB 결함 탐지 및 분류는 제조 품질 개선과 생산비 절감에 중요한 역할을 합니다.

#### 📌 주요 내용
- 모델: YOLOv8, YOLO-NAS  
- 데이터셋: 약 700장의 PCB 결함 데이터셋  
- 결함 유형:  
  - Short
  - Mouse Bite
  - Missing Hole
- 성과:  
- YOLO-NAS: 작은 결함 탐지에 우수한 성능 제공  
- YOLOv8: 대규모 이미지 처리에서 높은 효율성  
#### 🛠️ 활용 사례
- 전자기기 제조 공정의 품질 검사
- 스마트팩토리에서의 결함 자동 탐지 시스템

#### ✔︎ 결과
- YOLOv8 Confusion Matrix
<img src="https://github.com/user-attachments/assets/04091e24-24e9-4982-ab50-d0ecbddd32a9" width="400" height="400">

- YOLO-NAS Confusion Matrix
<img src="https://github.com/user-attachments/assets/e1e1766f-eb6c-4001-89f4-dd0f62926bee" width="400" height="400">


- Inference image
<img src="https://github.com/user-attachments/assets/7680df73-ee24-4354-8c8c-b9f8bacfe9dd" width="300" height="500">

