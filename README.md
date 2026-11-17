# kbo-media

KBO 노트 스레드(Threads) 게시물에 첨부하는 이미지 호스팅용 저장소입니다.

## 용도
- 스레드 게시물 첨부 이미지(png/gif)를 공개 URL로 제공하기 위한 저장소입니다.

## 파일 규칙
```
threads/YYYYMMDD/<글id>-<n>.(png|gif)
```
- `YYYYMMDD`: 게시일, `<글id>`: 게시물 식별자, `<n>`: 같은 글 안의 이미지 순번(1부터)

## 출처 표기
- 각 파일의 출처는 [`sources.csv`](sources.csv)에 기록합니다.
  - 열: `file,source,video_id,t,posted_at`
- 방송 화면 캡처는 방송사 로고를 유지하며, 편집하지 않습니다.

## 삭제 요청
권리자의 삭제 요청이 있으면 즉시 삭제합니다. 이 저장소의 Issue로 요청해 주세요.
