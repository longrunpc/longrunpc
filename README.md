# 👋 안녕하세요, 상황에 맞는 최적의 솔루션을 고민하는 개발자 박찬입니다.

> **"단순한 구현을 넘어, 근거 있는 기술 선택으로 서비스의 가용성과 유지보수성을 높이는 데 집중합니다."**

### 🧠 Introduction
* **최적의 아키텍처 고민**: 새로운 기술을 빠르게 습득하여 AI 기술을 실제 서비스에 접목하고, 제한된 비용 내에서 알맞은 인프라 환경을 구축하며 최적의 시스템 아키텍처를 설계한 경험이 있습니다.
* **시스템 안정성 및 일관성**: '맘찬픽'의 레거시 코드를 유지보수하며, 서로 다른 두 앱을 통합하는 과정에서 구조적 일관성과 환경 분리를 통해 시스템 안정성을 확보했습니다.
* **데이터 기반의 성능 최적화**: 위치 기반 가게 리스트 구현 시 PostgreSQL 공간 인덱스(Spatial Index)를 도입하여 성능을 극대화하고, 기존 Polling 방식을 커스텀하여 gRPC로 전환해 네트워크 오버헤드와 지연 시간을 최소화했습니다.
* **지속 가능한 개발 환경**: 클린 코드와 테스트 코드 작성을 원칙으로 삼으며, Swagger와 Postman을 통한 철저한 문서화로 동료들이 이해하기 쉬운 협업 환경을 만드는 데 기여합니다.
* **장애 대응 및 가용성**: k6 부하 테스트를 통한 병목 지점 개선과 실시간 모니터링을 통해 서비스 가용성을 강화합니다.
---

## 🎓 Education  
**University of Seoul** — Computer Science and Engineering  
📅 Mar 2019 – Aug 2025 (Graduated)

---

## 🧠 Skills  

![chan's GitHub stats](https://github-readme-stats.vercel.app/api?username=longrunpc&include_orgs=true&show_icons=true&theme=radical)  
[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=longrunpc)](https://solved.ac/longrunpc/)

---

### 💻 Platforms & Languages  
![Java](https://img.shields.io/badge/Java-007396.svg?&style=for-the-badge&logo=Java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB.svg?&style=for-the-badge&logo=Python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?&style=for-the-badge&logo=MySQL&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1.svg?&style=for-the-badge&logo=PostgreSQL&logoColor=white)
![AWS](https://img.shields.io/badge/amazon%20aws-%23232F3E.svg?&style=for-the-badge&logo=amazon%20aws&logoColor=white)

---

### 🧱 Frameworks & Libraries  
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F.svg?&style=for-the-badge&logo=Spring%20Boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F.svg?&style=for-the-badge&logo=Spring%20Security&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C.svg?&style=for-the-badge&logo=Hibernate&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4.svg?&style=for-the-badge&logo=google&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?&style=for-the-badge&logo=Docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D.svg?&style=for-the-badge&logo=Redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20.svg?&style=for-the-badge&logo=Apache%20Kafka&logoColor=white)

---

### ⚙️ DevOps & Monitoring  
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF.svg?&style=for-the-badge&logo=GitHub%20Actions&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED.svg?&style=for-the-badge&logo=Docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C.svg?&style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800.svg?&style=for-the-badge&logo=Grafana&logoColor=white)

---

## Projects  

### Castle Coder  > **AI 기반 보안 코드 리팩토링 VS Code 플러그인** | *2025.03 ~ 2025.06*

- **개요:** AI 채팅을 활용하여 실시간으로 보안 코드를 제안하고 코드의 취약 구간을 안전하게 리팩토링하는 VS Code 플러그인입니다.
- **역할: 팀장 및 백엔드 개발자**
  - **Spring Boot 서비스 아키텍처** 설계 및 **gRPC/SSE 스트리밍 API** 구현.
  - 서버리스 GPU 배포를 위해 **RunPod vLLM gRPC 통신** 커스터마이징.
  - **OWASP Top 10** 기반의 자동화 보안 벤치마크 도구인 **OWASPCodeEval** 구축.
  - **k6 부하 테스트** 및 **Prometheus/Grafana** 모니터링 수행.
- **성과**:
  - gRPC 스트리밍 도입으로 응답 지연 시간(Latency) **50% 단축**.
  - 정량적 평가 지표를 갖춘 종합적인 AI 기반 보안 코딩 시스템을 구축했습니다
- **Tech Stack:**  
  Spring Boot · gRPC · PostgreSQL · Redis · Docker · AWS · RunPod · TypeScript · React  

- **Links:**  
  [GitHub](https://github.com/castle-coder) | [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=YUCHANOH.castle-coder)

---
### MomChanPick  
> **O2O 기반 반찬 예약 및 픽업 플랫폼** | *2025.01 ~ 2025.12*

- **개요:** 지역 반찬가게 예약 주문 및 오프라인 픽업 서비스입니다. 백엔드 아키텍처 개선 및 성능 최적화에 주력했습니다.
- **역할: 백엔드 개발자**
  - 유지보수성 향상을 위해 **도메인 모델 및 ERD 재설계**.
  - **공간 인덱스(Geospatial Indexing)** 및 커서 기반 페이지네이션을 통한 성능 최적화.
  - **GitHub Actions(CI/CD)** 및 AWS 인프라를 통한 배포 자동화.
- **성과**: 공간 인덱스 도입으로 쿼리 성능 **약 40% 향상** 및 월 8만 원 이하의 비용으로 안정적 운영 달성.
- **Tech Stack:**  
  Spring Boot · JPA · MySQL · Redis · Docker · AWS · Prometheus · Grafana · k6 · React Native  

- **Links:**  
  [Google Play](https://play.google.com/store/apps/details?id=com.ummgoban.momchanpick) · [App Store](https://apps.apple.com/kr/app/%EB%A7%98%EC%B0%AC%ED%94%BD/id6738623251) · [GitHub](https://github.com/ummgoban)

---

### QooTalk
> **실시간 메시지 전송과 읽음 처리를 지원하는 사내 커뮤니케이션용 채팅 서버**

- **개요:** : 대규모 트래픽 환경에서도 안정적인 실시간 메시징을 보장하기 위해 설계된 사내 커뮤니케이션 서버입니다. 
- **작업내용**
  - **멀티 모듈 아키텍처 설계**: Domain, Application, Infrastructure, Presentation 계층으로 분리한 멀티 모듈 구조를 설계하여 코드 간 결합도를 낮추고 유지보수성 향상.
  - **고성능 메시징 시스템 구축**: **Kafka**를 통해 메시지 전송 및 읽음 이벤트를 비동기 처리하고, **Redis Pub/Sub** 기반의 fan-out 구조를 구현하여 멀티 인스턴스 환경에서의 실시간 브로드캐스팅 보장.
  - **실시간 상태 관리 및 스트리밍**: **SSE(Server-Sent Events)** 기반의 실시간 구독 기능과 **Redis Presence**를 활용한 사용자 온라인 상태 실시간 동기화 구현.
  - **시스템 최적화 및 정합성 확보**: 유니크 키 적용을 통한 데이터 정합성 강화 및 인덱스 성능 최적화. 요청 처리와 이벤트 전파 로직을 분리하여 응답 지연 시간(Latency) 단축.
  - **통합 테스트 환경 구축**: **Testcontainers**를 도입하여 PostgreSQL, Redis, Kafka, LocalStack(S3) 등 실제 인프라와 동일한 환경에서 동작하는 신뢰성 높은 테스트 코드 작성.
- **Tech Stack**: Java 21 · Spring Boot · PostgreSQL · Redis · Kafka · SSE · Docker · AWS S3 · LocalStack
- **Links:**
  · [GitHub](https://github.com/longrunpc/qootalk)
---
