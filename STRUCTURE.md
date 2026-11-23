# STRUCTURE · pilatesqueen-sample (v0.1.0 · 흰 바탕 + 로고 하늘색 · 공간 사진 중심 · 모서리 2px · 배포 예정 pilatesqueen-sample.lgt3232.workers.dev)

```
pilatesqueen-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = pilatesqueen-sample
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ pq-cinzel.woff2            영문 워드마크 · 라벨 · 체험가 숫자 (Cinzel 400–600, 영문만)
├─ pq-pretendard.woff2        본문 · 한글 (Pretendard 300–700)
├─ pq-emblem.webp             하늘색 원형 로고 360px (원 밖 투명)
├─ pq-hero.webp · pq-hero-m.webp  히어로 PC 1280×720 · 모바일 810×1080
├─ pq-g01 ~ pq-g09.webp       SPACE 9장 (600×750 · 모바일은 8장)
├─ favicon.png · og-pq.jpg
├─ img/                       다올 제공 원본 + _원문.md (배포 제외 · 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로(하늘색 그라데이션 + 넓은 사진) → `#program` → `#trial`(하늘) → `#why` → `#space`(하늘) → `#visit` → 푸터(#1B3446) + 모바일 `.quick`.

## 버튼 · 링크
- 네이버 예약 `m.place.naver.com/place/1279003738/home`(메인): 헤더(900 이상) · 히어로 · TRIAL · VISIT · 푸터 · 하단 바
- 전화 `tel:01077698815`: 히어로 · VISIT · 푸터 · 하단 바
- 그룹레슨 시간표 `blog.naver.com/pilatesqueen8/224206524904`: 히어로 · 하단 바
- 네이버 지도 `map.naver.com/p/entry/place/1279003738` · 인스타 · 블로그

## 모션 (강제 재생 · 다올 방침)
- 히어로 `.intro` 등장 · 섹션 `.reveal`(setInterval) · 앵커 rAF 스크롤(R-25). reduced-motion 분기 없음.

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 Pretendard만, Cinzel은 영문만. Pretendard 원본 = `fonts/Pretendard-1.3.9/public/variable/PretendardVariable.ttf`(300–700 인스턴스 후 서브셋).
