<div align="center">

<img width="280" alt="TalleMalle Logo" src="https://github.com/user-attachments/assets/3ae14639-49a6-415c-8407-bf0cb62fd85c" />

# 🚕 TalleMalle DevOps

</div>

<br>

> ### 🔗 Project Links
> 🌐 **Web Service** : [TalleMalle 공식 서비스 접속하기](https://www.tallemalle.kro.kr)  
> 🌐 **Web Driver Service** : [TalleMalle 공식 드라이버 서비스 접속하기](https://driver.tallemalle.kro.kr)  
> 📘 **API Docs** : [Swagger API 명세서](https://api.tallemalle.kro.kr/swagger-ui/index.html)  
> 📏 **Convention** : [팀 코딩 컨벤션 및 규칙 (Notion)](https://www.notion.so/2dfa4b6b459480e693d3f1e81cf9134a?source=copy_link)  
> 📋 **요구사항 정의서** : [요구사항 정의서](https://docs.google.com/spreadsheets/d/1_wSnuyYpkMXw1geaeSqGHfUOZfL644nFQrEA4qVqgvc/edit?usp=sharing)

<br>

## 👥 Team TalleMalle

<table align="center" width="100%">
  <tr>
    <td align="center" width="20%">
      <a href="https://github.com/shinukang">
        <img src="https://github.com/shinukang.png" width="90" style="border-radius: 50%;"><br/>
        <strong>강신우</strong>
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/saralove20">
        <img src="https://github.com/saralove20.png" width="90" style="border-radius: 50%;"><br/>
        <strong>김사라</strong>
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/pbgodsoo">
        <img src="https://github.com/pbgodsoo.png" width="90" style="border-radius: 50%;"><br/>
        <strong>박범수</strong>
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/hijaehyuk">
        <img src="https://github.com/hijaehyuk.png" width="90" style="border-radius: 50%;"><br/>
        <strong>이재혁</strong>
      </a>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/DongHyunj">
        <img src="https://github.com/DongHyunj.png" width="90" style="border-radius: 50%;"><br/>
        <strong>정동현</strong>
      </a>
    </td>
  </tr>
</table>

---

## 🎯 프로젝트 개요

**'TalleMalle 탈래말래'는 같은 경로로 이동하는 사람들을 실시간으로 연결해  
혼자 타기엔 부담스러운 택시 요금을, 같은 목적지의 사람들과 함께 나누는 위치 기반 택시 공유 플랫폼 서비스입니다.**

### 🧩 기획 배경
- 혼자 타기엔 부담되는 택시 비용
- 같은 방향으로 가는 사람이 있어도 함께 탈 방법이 없음
- 같은 목적지·동선 사용자 간 자발적이고 투명한 매칭 필요

### ✨ 핵심 기능

| 기능 | 설명 |
| --- | --- |
| 🔐 사용자 인증 | Spring Security 기반 로그인/회원가입 및 인증·인가 |
| 📝 동승 모집글 작성 | 출발/도착 위치, 시간, 인원 설정 |
| 🗺 실시간 지도 매칭 | 지도 이동 기준 주변 모집글 실시간 조회 |
| 🤝 참여 요청 & 승인 | 모집 상태에 따른 버튼/권한 분기 |
| 💬 실시간 채팅 | WebSocket 기반 참여자 전용 채팅 |
| 👤 마이페이지 | 참여 이력, 결제 수단/내역 관리, 프로필 관리 |
| 🚕 기사님 페이지 | 드라이버 페이지 분리 및 WebSocket 기반 실시간 콜 매칭 |

---

## 🛠 Tech Stack

### 🔹 Frontend
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Pinia](https://img.shields.io/badge/Pinia-FFD500?style=for-the-badge&logo=pinia&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38bdf8?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-Realtime-00B894?style=for-the-badge)

### 🔹 Backend
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/SpringSecurity-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA_Hibernate-59666C?style=flat-square)
![JWT](https://img.shields.io/badge/JWT_Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-4285F4?style=flat-square&logo=oauth&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket_STOMP-00B894?style=flat-square)

### 🔹 DBMS & Storage
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-FF9900?style=flat-square&logo=amazons3&logoColor=white)

### 🔹 Infra & Deployment
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

### 🔹 CI/CD
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

### 🔹 Collaboration
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

---

## 🏗 시스템 아키텍처 (System Architecture)

![TalleMalle 시스템 아키텍처](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/images/system-architecture.png)

> 📌 이미지가 보이지 않을 경우 → [Wiki에서 확인하기](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/3.-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-(System-Architecture)-%EB%B0%8F-SW-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-(Software-Architecture))

### ⚙️ CI/CD 파이프라인

개발자가 GitHub에 코드를 Push하면 Webhook이 트리거되어 **Kubernetes 클러스터 내부의 Jenkins**가 파이프라인을 자동 실행합니다.
- **프론트엔드**: `npm build` → Docker 이미지 빌드 → Docker Hub Push → K8s 배포
- **백엔드**: `gradle build` → Docker 이미지 빌드 → Docker Hub Push → K8s 배포

Jenkins를 클러스터 내부에서 운영하면 빌드마다 **Pod를 동적으로 생성**해 환경을 격리하고, 작업 종료 후 자동 삭제해 리소스를 효율적으로 관리할 수 있습니다.

### 🌐 Kubernetes 네트워크 구성

외부 트래픽은 **Ingress**를 통해 경로별로 분기됩니다.

| 경로 | 대상 | 비고 |
| --- | --- | --- |
| `/` | 프론트엔드 (Nginx) | 정적 자산 서빙 |
| `/api` | 백엔드 REST API | Spring Boot |
| `/ws` | WebSocket | 장시간 연결 유지, 별도 타임아웃 설정 |

> WebSocket(`/ws`)을 REST API(`/api`)와 분리한 이유: WebSocket은 연결 유지 시간이 길어 Ingress의 프록시 타임아웃 및 라우팅 규칙을 별도로 관리해야 운영·장애 대응에 유리하기 때문입니다.

### 🗄️ 데이터 & 스토리지

- **MariaDB**: Kubernetes 클러스터 **외부**에 배치하여 클러스터 재구성·장애 시에도 영속 데이터를 보호합니다. Master-Slave 복제 구성으로 가용성과 읽기 분산을 확보합니다.
- **AWS S3**: Presigned URL 방식으로 정적 파일·미디어를 저장·연동합니다. 클라이언트가 서버를 거치지 않고 S3에 직접 업로드·다운로드하여 서버 부하를 줄입니다.

### 📊 모니터링

- **Prometheus**: 각 Pod의 메트릭을 수집합니다.
- **Grafana**: 수집된 메트릭을 대시보드로 시각화해 실시간 서비스 상태를 모니터링합니다.

---

## 🚀 무중단 배포 — 블루 그린 배포 (Blue-Green Deployment)

새 버전을 비활성 슬롯(Green)에 먼저 배포하고, 준비 완료 후 **Kubernetes Service selector 전환**으로 트래픽을 넘겨 서비스 중단 없이 배포합니다. 프론트엔드(Nginx)와 백엔드(Spring Boot) 모두 동일한 전략을 적용합니다.

| 장점 | 설명 |
| --- | --- |
| ⚡ Zero Downtime | 서버를 끄고 켜는 시간 없이 즉시 전환, 사용자 입장에서 끊김 없는 서비스 |
| 🔄 즉각 롤백 | 새 버전에 치명적 버그 발견 시 selector를 이전 버전(Blue)으로 되돌려 1초 내 복구 |
| 🔒 환경 일관성 | 실제 운영과 동일한 환경에서 배포 직전 최종 테스트 후 전환 |
| 🌡️ JVM 웜업 확보 | Spring Boot는 초기 클래스 로딩으로 응답이 느릴 수 있어, Green 환경에서 웜업을 끝낸 뒤 트래픽을 전환해 성능 저하 없이 서비스 시작 |
| 🔀 리소스 불일치 방지 | 배포 중 구버전 HTML이 신버전 JS를 요청하는 404 오류·화면 깨짐을 원천 차단 |

### 📹 블루그린 배포 테스트 영상

> GitHub의 private 영상은 로그인 후 Wiki에서 확인하실 수 있습니다.

| 구분 | 화면 영상 | nGrinder 부하 테스트 |
| :---: | :---: | :---: |
| **프론트엔드** | [▶ Front.mp4 보기](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/8.-%EB%AC%B4%EC%A4%91%EB%8B%A8-%EB%B0%B0%ED%8F%AC-%E2%80%90-%EB%B8%94%EB%A3%A8-%EA%B7%B8%EB%A6%B0-%EB%B0%B0%ED%8F%AC-%ED%85%8C%EC%8A%A4%ED%8A%B8-%EC%98%81%EC%83%81#블루그린-무중단-배포-테스트-영상) | [▶ Front.ngrinder.mp4 보기](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/8.-%EB%AC%B4%EC%A4%91%EB%8B%A8-%EB%B0%B0%ED%8F%AC-%E2%80%90-%EB%B8%94%EB%A3%A8-%EA%B7%B8%EB%A6%B0-%EB%B0%B0%ED%8F%AC-%ED%85%8C%EC%8A%A4%ED%8A%B8-%EC%98%81%EC%83%81#블루그린-무중단-배포-테스트-영상) |
| **백엔드** | [▶ Back.mp4 보기](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/8.-%EB%AC%B4%EC%A4%91%EB%8B%A8-%EB%B0%B0%ED%8F%AC-%E2%80%90-%EB%B8%94%EB%A3%A8-%EA%B7%B8%EB%A6%B0-%EB%B0%B0%ED%8F%AC-%ED%85%8C%EC%8A%A4%ED%8A%B8-%EC%98%81%EC%83%81#블루그린-무중단-배포-테스트-영상-1) | [▶ Back.ngrinder.mp4 보기](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/8.-%EB%AC%B4%EC%A4%91%EB%8B%A8-%EB%B0%B0%ED%8F%AC-%E2%80%90-%EB%B8%94%EB%A3%A8-%EA%B7%B8%EB%A6%B0-%EB%B0%B0%ED%8F%AC-%ED%85%8C%EC%8A%A4%ED%8A%B8-%EC%98%81%EC%83%81#블루그린-무중단-배포-테스트-영상-1) |

---

## 📚 Documents & Wiki

> **프로젝트의 상세한 내용은 아래 Wiki 링크에서 확인하실 수 있습니다.**

* 🎯 [**프로젝트 개요 (Project Overview)**](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/1.-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EA%B0%9C%EC%9A%94-(Project-Overview))
* 🧩 [**기술 선정 이유 (Tech Stack & Rationale)**](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/2.-%ED%95%B5%EC%8B%AC-%EA%B8%B0%EB%8A%A5-%EC%84%A4%EA%B3%84-%EB%B0%B0%EA%B2%BD%EA%B3%BC-%EA%B8%B0%EC%88%A0-%EB%8F%84%EC%9E%85-%EC%9D%B4%EC%9C%A0)
* 🏗 [**시스템 아키텍처 (System Architecture)**](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/3.-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-(System-Architecture)-%EB%B0%8F-SW-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-(Software-Architecture))
* ✨ [**코딩 컨벤션 (Coding Convention)**](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/4.-%EC%BD%94%EB%94%A9-%EC%BB%A8%EB%B2%A4%EC%85%98)
* 🗂 [**ERD**](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/5.-ERD)
* 🧪 [**프론트엔드 기능 테스트 (Frontend Feature Test)**](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/6.-%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C-%EA%B8%B0%EB%8A%A5-%ED%85%8C%EC%8A%A4%ED%8A%B8)
* 🚀 [**성능 개선 (Performance Improvement)**](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/7.-%EC%84%B1%EB%8A%A5-%EA%B0%9C%EC%84%A0-(Performance-Improvement)-%F0%9F%9A%80)
* 📹 [**무중단 배포 테스트 영상 (Blue-Green Deployment)**](https://github.com/beyond-sw-camp/be24-4th-saraITne-TalleMalle/wiki/8.-%EB%AC%B4%EC%A4%91%EB%8B%A8-%EB%B0%B0%ED%8F%AC-%E2%80%90-%EB%B8%94%EB%A3%A8-%EA%B7%B8%EB%A6%B0-%EB%B0%B0%ED%8F%AC-%ED%85%8C%EC%8A%A4%ED%8A%B8-%EC%98%81%EC%83%81)

---

<div align="center">
  <br>
  <b>🚕 Backend powered by TalleMalle</b>
</div>
