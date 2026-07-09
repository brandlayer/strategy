# 이뻐 일본 POC Playbook GitHub Pages 업로드 패키지

## 목적
기존 이뻐 전략 게이트 페이지의 룩앤필에 맞춰 `06 · JAPAN POC` 신규 전략 카드를 추가하고, 상세 페이지를 같은 타입의 미니멀 인덱스 페이지로 정렬했습니다.

## 포함 파일

```text
index.html
index_card_snippet.html
strategies/ippeo-japan-poc-playbook.html
UPLOAD_README.md
```

## 업로드 방식

### 1안. 전체 교체
GitHub Pages 저장소의 `/strategy` 경로에 아래 파일을 업로드합니다.

```text
index.html
strategies/ippeo-japan-poc-playbook.html
```

### 2안. 기존 index 유지
기존 `index.html`을 유지하려면 다음만 반영합니다.

1. `strategies/ippeo-japan-poc-playbook.html` 업로드
2. 기존 `index.html`의 카드 그리드 영역에 `index_card_snippet.html` 내용을 추가
3. 커밋 후 GitHub Pages 배포 확인

## 신규 상세 페이지 경로

```text
https://medihim.github.io/strategy/strategies/ippeo-japan-poc-playbook.html
```

## 스타일 정렬 내용
- 기존 스크린샷 기준의 오프화이트 배경
- 상단 얇은 네비게이션 바
- 큰 블랙 타이포그래피
- 카드형 인덱스 구조
- 블랙 라벨 배지
- 4열 전략 카드 그리드
- 상세 페이지도 동일한 섹션 헤더, 카드, 테이블 룩앤필 적용

## 보안 참고
비밀번호 7100 방식은 정적 HTML 수준의 간단한 접근 제한입니다. 민감한 환자정보, 개인정보, 계약서, 정산자료는 비공개 저장소 또는 서버 인증이 필요합니다.


## 2026-07-09 업데이트

- 게이트 페이지와 세부 LNB 페이지의 CSS `font-size` 값을 기존 대비 약 20% 확대했습니다.
- 레이아웃, 카드 구조, 경로, 링크 구조는 기존 LNB 버전과 동일하게 유지했습니다.
