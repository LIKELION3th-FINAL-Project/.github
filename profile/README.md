# 프로젝트 주제
CloZ(옷장을 부탁해)는 사용자의 입력 프롬프트를 기반으로 사용자의 옷장 정보에서 추천 착장을 추천해주는 서비스입니다.

<br>

### 서비스 플로우
![service_architecture](../assets/서비스플로우.png)

1. User Input
비정형의 사용자 발화(e.g. "내일 홍대 갈건데 코디 추천해줘")에 대해 미리 선정해둔 정형화된 JSON 템플릿에 맞추어 모호한 발화를 더 명확하게 이해합니다.

2. 

<br>
<br>

---
---

# 기술적 및 서비스적 이슈 해결


<br>
<br>

---
---

# 프로젝트 아키텍쳐 및 기술 스택

### BE + FE 아키텍쳐


### AI 아키텍쳐


### 기술스택
<p>
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white">
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
<img src="https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logoColor=white">
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900">
</p>

<br>
<br>

---
---

# Python실행

<br>

### BE + AI 실행

1. 레포지토리 복제 & 서브모듈 업데이트
```bash
git clone <url>
git submodule update --remote --recursive
```

<br>

2. `.env`작성

`drf/.env` 작성        
`fastapi/.env` 작성      
`models/.env` 작성      

<br>

3. 도커 컨테이너 실행
```bash
docker compose exec app python manage.py migrate // 마이그레이션
docker compose down
docker compose build --no-cache // no-cache로 수행
docker compose up -d
docker compose ps
```

---

### FE 실행
```bash
npm run dev // 실행경로: cloz-fe/frontend
```
