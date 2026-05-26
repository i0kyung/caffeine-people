# 오늘도 과부하 ☕🐈‍⬛

카페인으로 하루를 버티는 사람들을 위한 익명 대나무숲 웹사이트입니다.  
고양이 직장인 배경 위에 포스트잇처럼 하소연을 남기고,  
카페인을 너무 많이 마신 방문자는 하단의 작은 묘로 기록됩니다.

> “오늘도 살아남았다면, 메모 하나 남기고 가세요.”

---

## 🔗 Link

- GitHub Repository: https://github.com/i0kyung/caffeine-people
- Website: https://i0kyung.github.io/caffeine-people/
- Direct Test Page: https://i0kyung.github.io/caffeine-people/loading-test.html

---

## 📌 Project Concept

**오늘도 과부하**는 직장인, 학생, 작업자들이 카페인과 업무 과부하를 가볍게 기록하는 실험형 웹사이트입니다.

이 웹은 단순한 메모장이 아니라,  
카페인 테스트 → 익명 메모 → 과카페인 묘지 → 점메추/저메추 룰렛으로 이어지는  
작은 인터랙션형 방명록입니다.

---

## ✨ Main Features

### 1. Caffeine Loading Test

처음 접속하면 오늘 마신 커피 잔 수를 입력합니다.

- 0~3잔: 정상 상태
- 4잔 이상: 과카페인 상태
- 과카페인 상태일 경우 `YOU DIED` 연출 등장
- 테스트 결과는 메인 메모장 화면과 연결됩니다.

---

### 2. Anonymous Memo Board

고양이 직장인 배경 위에 포스트잇 메모를 남길 수 있습니다.

- 익명 메모 작성
- 포스트잇 색상 선택
- 포스트잇 드래그 이동
- Supabase를 통한 실시간 공유
- 작성된 메모는 30일 후 정리

---

### 3. Overload Graveyard

카페인 테스트에서 과부하 상태가 된 사용자는  
메모장 하단 땅 영역에 작은 묘로 기록됩니다.

- 과카페인 테스트 1회 = 묘 1개
- 묘 위치는 랜덤 배치
- 개별 묘 UI는 정리 가능
- 월별 과카페인 숫자는 기록으로 보존

예시:

```txt
2026.05 / 14 people