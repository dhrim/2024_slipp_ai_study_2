# Vision AI
김학건

<br>

- 발표 PPT 링크: https://docs.google.com/presentation/d/1n7NofUts5ad-fLTo_RO66DSEHbpBsu8m/edit?usp=sharing&ouid=112593965975150056872&rtpof=true&sd=true

- 목적: Vision AI를 개발자에게 개념 설명
- 방법: 개념 설명 및 코드 실행 예시 화면 공유
- 내용
    - vision AI 설명
    - 실습 : 
        1. yolo 101:
            https://colab.research.google.com/github/ultralytics/ultralytics/blob/main/examples/tutorial.ipynb
        2. Yolo 데이터셋 구경하기
            https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/train-yolov8-object-detection-on-custom-dataset.ipynb
        3. 라벨링을 도와주는 AI (SAM)
            https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/how-to-segment-images-with-sam-2.ipynb

<br>

- Q&A
    1. 데이터셋은 다양하나요 - 네, yolo, cvat, pascal voc, imagent 등 다양합니다.
    2. segmentation(픽셀 탐지)에서 라벨 크기가 크다는게 무슨 말인가요 - 좌표점이 얼마나 자세한지에 따라 다릅니다.
    3. face reconition (구글 포토의 얼굴 분류)는 뭔가요 - classification의 일종이지만, 따로 분야가 세분화되어 있습니다.
    4. 프로젝트 진행할 때 어려운 부분은 무엇이엇나요 - 상황에 적합하지 않은 모델을 현업 사용자(공장)에서 사용했습니다. classification(분류)로 불량/양품을 판정하려고 함

<br>

- 참고 링크
    - 상용 서비스
        - Vision 프레임웍 웹, Roboflow: https://roboflow.com/
    - 오픈소스
        - 가장 유명한 모델 라이브러리, Ultralytics(YOLO) : https://github.com/ultralytics/ultralytics
        - Intel에서 공개한 라벨링 오픈소스, CVAT: https://www.cvat.ai/
        - Meta에서 공개한 실시간 픽셀 탐지 오픈소스, SAM: https://ai.meta.com/sam2/