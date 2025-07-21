# IDEs (Integrated Development Environments) tools

<img width="635" height="259" alt="image" src="https://github.com/user-attachments/assets/8cabc665-6916-4dd5-9a81-d34b5cda1b0a" />

- 위 전체 과정에서 'Data Management' 제외하고 Watson studio와 opensale을 통해 전체 개발 주기 관리 가능함
---

## Data Asset Management
- 데이터를 정리하고 관리하는 플랫폼
- **Apache Atlas**
- **Egeria and Informatica(IBM)**

---

## Data Management
- **MySQL**  
  - RDBMS로 웹 애플리케이션, 데이터 웨어하우징, 전자상거래 등에 활용

- **PostgreSQL**  
  - JSON 지원  
  - 공간 데이터에 유용

- **MongoDB**  
  - 문서 지향 NoSQL  
  - JSON으로 데이터 저장  
  - 확장성과 데이터 분산 기능으로 대량의 비구조적 데이터 처리에 적합

- **Apache CouchDB**  
  - 문서 지향 NoSQL  
  - JSON 사용

- **Apache Cassandra**  
  - 문서 지향 NoSQL  
  - 다수의 일반 서버에 걸쳐 대량의 구조화 및 비구조화 데이터 처리 가능

- **Hadoop HDFS**  
  - 파일을 블록으로 나누어 여러 데이터 노드에 분산 저장  
  - 높은 데이터 처리량 제공

- **Elasticsearch**  
  - 색인 생성을 포함하여 텍스트 데이터 저장  
  - 분산 RESTful 검색 엔진 및 분석 도구  
  - 전체 텍스트 검색 및 실시간 데이터 분석에 용이

---

## Data Integration and Transformation (ETL)
- **Apache Airflow**  
  - Airbnb에서 개발  
  - 워크플로를 프로그램적으로 작성하고 예약 및 모니터링 가능

- **Kubeflow**  
  - Kubernetes 위에서 데이터 사이언스 파이프라인 실행

- **Apache Kafka**  
  - 실시간 레코드 스트림 게시 및 처리  
  - LinkedIn에서 개발됨  
  - 확장성과 내결함성

- **Apache NiFi**  
  - 시스템 간 데이터 흐름 자동화  
  - 데이터 라우팅 및 변환

- **Apache SparkSQL**  
  - 수천 개의 노드로 구성된 클러스터로 확장 가능  
  - 다양한 데이터 소스 지원

---

## Data Visualization
- **간단한 툴**: Tableau, PowerBI  
- **PixieDust**: Jupyter 노트북에서 사용  
- **Hue**: Hadoop 시각화, SQL 쿼리로 시각화  
- **Kibana**: Elasticsearch와 함께 사용되는 웹 기반 인터페이스  
- **Apache Superset**: 현대적인 웹 기반 BI 툴

---

## Model Deployment
- 모델 배포. 다른 개발자가 사용할 수 있게 API로 전환함
- **Apache PredictionIO**  
- **Kubernetes**  
  - 컨테이너화된 애플리케이션 자동 시작, 확장, 관리  
  - 다중 호스트에서 컨테이너 오케스트레이션

- **Apache Seldon**  
  - Kubernetes에서 모델 배포 및 관리  
  - 워크플로 자동화 및 실시간 성능 모니터링

- **MLeap**  
- **TensorFlow Serving**  
  - 모바일 및 임베디드 장치에서 모델 실행

 ---
 
## Model Monitoring and Assessment
- 배포된 모델을 추적함
- **ModelDB**: 실험 추적, 모델 버전 관리 및 협업  
- **Prometheus**: 다양한 출처에서 실시간 메트릭 수집 및 저장  
- **IBM AI Fairness 360**: 모델의 편향 감지 및 완화  
- **IBM AI Explainability 360**: 모델의 행동과 결정 설명  
- **IBM Research Trusted AI**
  
---

## Code Asset Management
- **Git** 
- **GitLab**
- **GitHub**

## Code Development and execution
- **Jupyter IDE** 
- **RStudio**
- **Microsoft Visual Studio**
- **Pycharm** 
- **Spyder**
- **Anaconda Navigator**
  
