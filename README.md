# stamp_editor

MUJIMUJI 스탬프 — 정적 HTML 두 개로 이루어진 사이트.

```
/            링크 페이지
/diary/      스탬프 다이어리 (월간 달력 + 우표 붙이기)
/maker/      우표 메이커 (도형별 PNG 스티커 만들기)
```

빌드 과정이 없습니다. Vercel 프로젝트 하나로 저장소 루트를 그대로 배포하면 위 경로가 그대로 주소가 됩니다.
(Framework Preset: Other, Build Command·Output Directory 비움)

데이터는 브라우저(IndexedDB)에만 저장되며, 백업·복원은 JSON 파일로 합니다.
