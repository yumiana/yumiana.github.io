---
layout: single
title:  "Information of AWS Certified Data Engineer Associate"
---

- Official Guide
chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://d1.awsstatic.com/training-and-certification/docs-data-engineer-associate/AWS-Certified-Data-Engineer-Associate_Exam-Guide.pdf

- 개요
  - Amazon VPC, 인터페이스 엔드포인트, 라우팅, 보안 그룹 및 AWS Transit Gateway와 같은 AWS 네트워킹 개념에 대한 이해
  - AWS IAM, Amazon EC2, AWS Lambda 및 Amazon ECS/EKS와 같은 핵심 AWS 컴퓨팅 서비스
  - 스토리지 서비스에는 Amazon EBS 및 Amazon EFS
  - 서버리스 솔루션의 적용 범위가 광범위하므로 이벤트 중심 아키텍처와 SQS, SNS, EventBridge 등의 AWS 애플리케이션 통합 서비스
  - 시험내용
    도메인 1: 데이터 수집 및 변환(점수를 매긴 콘텐츠의 34%)
    도메인 2: 데이터 저장소 관리(점수를 매긴 콘텐츠의 26%)
    도메인 3: 데이터 운영 및 지원(채점된 콘텐츠의 22%)
    도메인 4: 데이터 보안 및 거버넌스(점수 있는 콘텐츠의 18%)

- 시험에 나오는 상위 10개의 데이터 엔지니어링 관련 기술
  1. 데이터 모델링 및 데이터베이스 설계
     - 데이터 정규화, 스키마 설계 및 데이터 웨어하우징 개념을 이해
     - 다양한 사용 사례에 맞게 효율적이고 확장 가능한 데이터베이스 스키마를 설계하는 능력.
  2. SQL 숙련도
     - 쿼리, 데이터 조작 및 분석을 위한 강력한 SQL 기술.
     - 복잡한 데이터 작업을 위한 고급 SQL 기능에 대한 지식
  3. 프로그래밍 및 스크립팅
    - 데이터 엔지니어링에서 일반적으로 사용되는 Python 또는 Java와 같은 프로그래밍 언어에 능숙
    - 데이터 처리 및 ETL 작업을 위한 코드를 작성, 디버깅 및 최적화하는 능력.
  4. 데이터 처리 및 ETL 기술 :
    - ETL(추출, 변환, 로드) 프로세스 및 도구에 대한 이해
    - 분석을 위해 대규모 데이터 세트를 변환하고 준비하는 기술.
  5. 빅데이터 기술 :
    - Hadoop, Spark 및 관련 기술을 포함한 빅 데이터 생태계에 대한 지식
    - 대규모 분산 컴퓨팅 및 데이터 처리에 대한 이해
  6. 데이터 보안 및 규정 준수 :
    - 암호화, IAM 역할, 보안 그룹을 포함한 데이터 보안 모범 사례에 대한 지식
    - 데이터와 관련된 규정 준수 요구 사항(예: GDPR, HIPAA)을 인식
  7. 성능 조정 및 최적화 :
    - 성능을 위해 데이터 쿼리 및 스토리지를 최적화하는 기술.
    - 시스템 성능 문제를 해결하고 조정하는 능력.
  8. 데이터 통합 ​​및 파이프라인 오케스트레이션 :
    - 다양한 소스와 형식의 데이터 통합 ​​경험.
    - 데이터 파이프라인 조정 도구 및 기술에 대한 이해
  9. 클라우드 네트워킹 및 아키텍처 :
    - 클라우드 네트워킹 개념, VPC, 네트워크 ACL 및 라우팅 테이블에 대한 기본 지식
    - 데이터 엔지니어링을 위한 AWS 클라우드 아키텍처 모범 사례를 이해
  10. 모니터링 및 로깅 :
    - AWS 리소스 및 애플리케이션을 모니터링하는 기술.
    - AWS CloudWatch와 기타 로깅 및 모니터링 도구에 대한 지식


- 시험에 나오는 상위 10개의 AWS Service
  1. Amazon Redshift
     - 데이터 웨어하우징, 쿼리 성능 최적화 및 데이터 배포 전략에 중점을 둡니다.
     - 다른 AWS 서비스와의 원활한 통합을 위한 Redshift Data API
     - Redshift Spectrum, Redshift 쿼리 최적화 프로그램, 테이블 보기 생성, 공간 회수 및 쿼리 성능 향상을 위한 VACUUM 명령 사용.
  2. AWS Glue
     - ETL 프로세스, AWS Glue 데이터 카탈로그, 크롤러, 데이터 통합 ​​및 변환을 위한 워크플로
  3. Amazon S3
     - 데이터 저장, 수명 주기 관리, 데이터 레이크 및 분석을 위한 다른 AWS 서비스와의 통합
     - Amazon S3 Select의 사용 및 적용에 대해서도 이해
  4. Amazon Athena
     - 서버리스 쿼리 서비스, 성능 최적화, AWS Glue 및 S3와의 통합과 관련
     - Apache Parquet와 같은 특정 파일 형식을 사용하면 얻을 수 있는 이점.
  5. AWS Lambda
     - 서버리스 컴퓨팅, 이벤트 기반 데이터 처리, Amazon S3 및 Amazon Aurora와 같은 서비스와의 통합
  6. Amazon RDS
     - 관리형 관계형 데이터베이스 서비스, 성능 튜닝 및 분석을 위한 다른 AWS 서비스와의 통합과 관련됩니다.
  7. AWS Step Functions
     - 서버리스 워크플로의 조정, AWS Lambda와의 통합, ETL 작업 자동화
     - Amazon States Language(ASL) 및 워크플로 상태 정의.
  8. Amazon Aurora
  9. Amazon EMR(Elastic MapReduce)
      - 빅 데이터 처리, Apache Hadoop 생태계, Apache Spark 및 HBase와 같은 도구를 사용한 데이터 분석
  10. Amazon Kinesis
      - Kinesis Data Streams, Data Firehose 및 Data Analytics를 포함한 실시간 데이터 스트리밍, 처리 및 분석
  
