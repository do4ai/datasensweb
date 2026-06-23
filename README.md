# DataSens 기업 홈페이지

데이터센스 주식회사(DataSens Co., Ltd.)의 공식 웹사이트입니다.
순수 정적 사이트(HTML/CSS/JS)로 제작되어 GitHub Pages로 바로 배포할 수 있습니다.

## 구조

```
web_datasens/
├─ index.html        # 단일 페이지 (Home / About / Solutions / Why / Contact)
├─ styles.css        # 디자인 시스템 (로고 색상 기반)
├─ script.js         # 내비게이션 · 스크롤 애니메이션
├─ CNAME             # 커스텀 도메인 (sens.ai.kr)
└─ assets/img/       # 로고 이미지
```

## 로컬 미리보기

```bash
# 아무 정적 서버나 사용 가능
python -m http.server 8000
# → http://localhost:8000
```

## 배포 (GitHub Pages)

1. GitHub에 저장소 생성 후 push
2. Settings → Pages → Source: `main` 브랜치 `/ (root)`
3. 커스텀 도메인 `sens.ai.kr` 연결 (CNAME 파일 포함됨)

자세한 절차는 대화 내 안내 참고.
