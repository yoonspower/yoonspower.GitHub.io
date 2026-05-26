# yoonspower.github.io

iOS 개발자 yoonspower 의 GitHub Pages 사이트. https://yoonspower.github.io

## 목적

1. **AdMob 인증** — `app-ads.txt` 로 광고 공급자 인증 (IAB Tech Lab 스펙).
2. **앱 랜딩** — App Store 출시 앱 목록.

## 파일

- `app-ads.txt` — AdMob publisher 인증 (`pub-7518008413051461`)
- `index.html` — 최소 랜딩 페이지
- `CNAME` — 추후 커스텀 도메인 사용 시 추가

## 배포

GitHub Pages 자동 빌드. `main` 브랜치 push → 1-2분 후 https://yoonspower.github.io 반영.

## AdMob 인증 확인

```bash
curl https://yoonspower.github.io/app-ads.txt
# 출력: google.com, pub-7518008413051461, DIRECT, f08c47fec0942fa0
```

AdMob 콘솔에서 재검증 트리거 → 24-48h 후 인증 완료.
