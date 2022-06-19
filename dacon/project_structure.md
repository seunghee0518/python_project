# kaggle : American Express Default Prediction
├──  README.md # 개요
├─── project_structure.md # 폴더 구조 정리(.md -> 마크다운파일)
├─── dataset # 공모전 제공 데이터
│   └── sample_submission.csv # 결과물 샘플 파일
│   └── test.csv # test 데이터
│   └── train_data.csv # train 데이터
│   └── train_labels.csv # train 레이블
│
├─── docs # 문서관련 폴더
│   ├── ...
│   └── index.md
│
├─── logger # 기록관련 폴더
│   └── logger.py # 기록 관련 함수 파일
│   └── visualization.py # 시각화 관련 함수
│
├─── model # 모델관련 폴더
│   └── main.ipynb # 모델 실행 ipynb
│   └── model.py # 모델 코드
│   └── train.py # 학습 실행 코드
│   └── test.py # 테스트 실행 코드
│   └── metric.py # 평가지표 관련 함수
│   └── loss.py # loss 관련 함수
│   └── base # 공모전 베이스 모델 관련 폴더
│        < 예시임 >
│       ├── adapters
│       │   └── __init__.py
│       ├── config.py
│       ├── entrypoints
│       │   └── __init__.py
│       ├── __init__.py
│       ├── model
│       │   └── __init__.py
│       ├── py.typed
│       ├── services.py
│       └── version.py
│ 
├─── eda.ipynb # eda 진행 ipynb
│ 
└── unit # 기타
    ├── __init__.py
    └── test_services.py