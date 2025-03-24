# DisClo 
[신한투자증권 프로디지털아카데미 5기 중간프로젝트 우수상(1등) 수상🥇]

---

![제목 없음](https://github.com/user-attachments/assets/0c135541-5ca3-41d8-8b6a-d64b466e74b8)


# 프로젝트 계획서

## 프로젝트 제목

- **서비스명**: DisClo
- **팀명**: 4조팔자
- **팀원**: 
<img width="1183" alt="Image" src="https://github.com/user-attachments/assets/01e86ae5-f410-4338-aebb-91fe87d77589" />


## 프로젝트 개요

- **목적 및 필요성**: 주식 투자자들이 상장 주식 공시를 쉽게 이해하고, 이를 통해 보다 나은 투자 결정을 내릴 수 있도록 돕는 서비스입니다.

## 기획 배경

- **공시는 중요한 투자 정보**이지만
    - 이해하기 어렵고 가독성이 낮습니다.
    - 방대한 공시 자료로 인해 신속한 분석과 이해가 어렵습니다.
    - 원하는 공시만 찾아보기 어려운 문제가 있습니다.
    - 공시에 대한 의견을 나눌 커뮤니티가 부재합니다.
    - 공시와 주가의 흐름을 연결해 분석하기 어렵습니다.
- 현재 일평균 공시가 120개가 있으며, 기존 공시 제공 서비스는 가독성이 낮고 복잡하여 이해하기 어렵고 시간이 오래 걸립니다.
- 우리의 해결책
    - 공시를 **ChatGPT API**로 분석 및 요약하여 사용자들이 의견을 댓글과 투표 기능을 통해 공유하고 소통할 수 있는 서비스입니다.

## 대상

- **초보 투자자**: 공시를 빠르게 이해하고 학습할 수 있어야 합니다.
- **전문 투자자**: 현재 이슈 되고 있는 중요한 공시를 빠르게 파악할 수 있어야 합니다.

## 기대 효과

- **공시 정보 접근성 향상**: 사용자들이 공시 정보를 더 쉽게 접근하고 사용할 수 있습니다.
- **공시 커뮤니티 활성화**: 투자자들 간의 의견 교환과 소통이 촉진됩니다.
- **공시와 주가의 상관관계 파악**: 공시 데이터를 요약 및 분석하여 투자자들이 복잡한 내용을 쉽게 이해하고, 신속한 의사 결정을 지원합니다.
- **투자자 간 소통 활성화**: 호재·악재 투표와 댓글 기능을 통해 공동으로 인사이트를 도출합니다.
- **상관관계 시각화 제공**: 주가와 공시를 함께 차트로 보여줌으로써 둘의 상관관계를 명확히 이해할 수 있게 합니다.

## 서비스 주요 기능

1. **공시 요약 및 평가 서비스**:
    - Dart API로 공시 데이터를 수집한 후 ChatGPT로 요약합니다
    - 호재/악재 구분 및 투자 의견을 제공합니다
2. **사용자 참여 및 소통 기능**
    - 호재와 악재에 대한 투표 기능.
    - 댓글을 통한 토론 기능.
    - 사용자 간의 투자 의견 교류
3. **공시 시점과 주가를 연결하여 시각화**
    - 종목별 공시 목록 제공 및 주가 차트에 공시 시점을 연결하여 제공

## 기술 스택

- 사용 기술
    - `React, Spring + JPA, MySQL, Redis, Python, Docker, Jenkins, GitHub`
- API 및 라이브러리 통합:
    - Dart API와 ChatGPT API를 활용하여 공시 요약 기능 및 데이터 수집 수행
    - 다음 증권, 한국투자증권 API를 활용하여 주식 종목에 대한 데이터 수집 수행

## 개발 로드맵

1. **증권사 API 연동**
    - 한투 API를 통해 주식 잔고와 매매 내역 가져오기
    - 공시 정보 API 연동 (Dart) 및 기업 공시 정보 수집
2. **공시 정보 요약 기능**
    - ChatGPT를 사용하여 공시 정보를 자동 요약
3. **프론트엔드, 백엔드 API 개발 및 연결**
4. **차트 라이브러리 사용**
    - ApexChart 라이브러리로 마커 및 주석 기능 통합
5. **사용자 관리**
    - 관심 종목 추가 및 제거 기능 제공
6. **UI/UX 디자인**
    - 사용자 친화적인 인터페이스 설계

## 커뮤니케이션 계획

- **팀 내부 및 외부 소통 방법**
    - 정기 회의 및 노션, 슬랙 등의 플랫폼을 통한 지속적인 소통 유지
    - Jira를 통한 일정 관리


### 아키텍처
![image](https://github.com/user-attachments/assets/036dd326-f4a6-4733-8846-36500c1b9faa)

## [Figma 보러가기](https://www.figma.com/design/CjC3tmHb7bpRPcxBdtWlMi/istp4%EC%A1%B0?node-id=0-1&node-type=canvas&t=UnAJZLBps6uv4wKp-0)
![image](https://github.com/user-attachments/assets/e3ca58ef-d4f7-40f4-8f93-e23d104a528f)

### ERD
![아키텍처](https://github.com/user-attachments/assets/7eb3340e-3182-4ddb-9e2c-c332ab1cf140)

### 주요 페이지 
![Image](https://github.com/user-attachments/assets/0d4cebf8-505c-4d9b-ad24-d9e1cceb9731)

![Image](https://github.com/user-attachments/assets/cc1b89c2-59f4-4cd7-8ebd-bbaae49a6c6d)

![Image](https://github.com/user-attachments/assets/74e561fb-bef2-4336-80d5-b19d2171bd40)

![Image](https://github.com/user-attachments/assets/20377d99-fb82-4f24-b0e4-cd9a145ac68c)

![Image](https://github.com/user-attachments/assets/17c46b8b-d035-4346-9e4e-ce7d53398571)