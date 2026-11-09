# 밥피엔스 (Babpiens)

미각을 깨우는 맞춤형 음식 메뉴 추천 서비스입니다. 위치 기반 추천과 오프라인 접근성을 지원하는 PWA로 만들었습니다.

- 배포: https://babpiens2024.vercel.app
- 기간: 2024.08 ~ 2024.10
- 현황: 사업팀 예산 부족으로 상용화는 진행하지 못했습니다. 서비스 종료 후 Vercel에서 화면만 유지하고 있습니다.
- 역할: 프론트엔드 구현, 클라우드 인프라 구축, 검색엔진 최적화 (팀 프로젝트)

## 주요 기능
- 맞춤형 메뉴 추천
- Kakao Map API 기반 위치 연동
- PWA: 설치 가능, 오프라인 접근성 지원
- 검색엔진 최적화: Google·Naver 검색 등록

## 인프라
- AWS EC2, CloudFront, Route53으로 배포 구성
- 구글·네이버 검색엔진 등록과 SEO 설정

## 기술 스택
React · TypeScript · Tailwind CSS · Firebase · Kakao Map API · PWA · AWS EC2 · CloudFront · Route53

## 로컬 실행
```bash
npm install
npm run dev        # 개발 서버
npm run build      # 타입 체크 + 프로덕션 빌드
```

Firebase 설정 값은 `VITE_FIREBASE_*` 환경 변수로 읽습니다. 실제 값은 리포지토리에 포함하지 않습니다.
