# newsletter-assets

잡스포이즈 주간 뉴스레터에서 사용하는 이미지 자산.

## 사용

이메일 HTML에서 절대 URL로 참조:

```
https://raw.githubusercontent.com/dmus-ai/newsletter-assets/main/<파일명>
```

## 자산 목록

| 파일 | 용도 | 크기 |
|---|---|---|
| `logo.png` | 잡스포이즈 BI (상단·하단·채용카드 fallback) | 28KB |
| `banner-top.jpg` | 상단 히어로 배너 (호랑이+젤리 캐릭터) | 37KB |
| `banner-bottom.jpg` | 하단 배너 | 30KB |
| `thumb-insight.png` | 잡스포이즈 소식 Featured 썸네일 | 18KB |
| `thumb-internship.png` | 인턴십 관련 Compact 썸네일 (정적 프레임) | 59KB |
| `sns-instagram.png` | 인스타그램 아이콘 | 35KB |
| `sns-facebook.png` | 페이스북 아이콘 | 10KB |
| `sns-threads.png` | 스레드 아이콘 | 13KB |
| `sns-kakao.png` | 카카오채널 아이콘 | 25KB |
| `sns-naver.png` | 네이버 아이콘 (예비) | 2KB |
| `jobspois-ico.png` | 잡스포이즈 SNS 아이콘 | 4KB |

## 3개월 교체

배경 톤·테마 교체 시 기존 파일을 새 버전으로 replace 하고 commit. 메일 내 URL은 동일하므로 향후 발송엔 자동 반영. 이미 발송된 메일은 Gmail·Naver 등 수신함의 이미지 캐시 정책에 따름.

## 채용공고 로고 규칙

- 사용할 수 있는 기업 로고는 해당 기업의 공식 사이트에서 다시 확인한 원본을 우선 사용한다.
- 모든 기업 로고는 원본 종횡비를 유지하고, 정사각 투명 캔버스 안에 사방 여백을 둔 뒤 가로·세로 중앙에 배치한다.
- 공식 기업 로고를 구하지 못해 `JOBSPOIS` 로고를 대신 쓰는 경우에도 원본을 위아래 또는 좌우로 늘리지 않는다. 다른 기업 로고와 동일하게 여백을 둔 정사각 투명 캔버스에 중앙 배치한다.
- 주간 자산을 올리기 전에 각 로고의 찌그러짐, 잘림, 중앙 정렬, 여백을 PC·모바일 렌더에서 확인한다.

## 레포 정책

- Public (raw.githubusercontent.com URL이 인증 없이 로드되어야 함)
- 민감 정보 없음 (브랜드 자산만)
