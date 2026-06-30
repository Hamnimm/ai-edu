# ai-edu — Claude Code 스킬 모음

유튜브 채널 운영에 필요한 Claude Code 커스텀 스킬을 모아두는 저장소입니다.

---

## 스킬 목록

### 📋 youtube-comment-picker

유튜브 댓글 이벤트 당첨자를 자동으로 선정하는 스킬.

**주요 기능**
- YouTube URL만 입력하면 댓글 자동 수집
- AI가 작성한 댓글, 복붙·도배, 성의 없는 댓글 자동 필터링
- 개인 경험·진정성·영상 연결·문장 완성도 4가지 기준으로 점수 채점
- 탈락 사유 + 선정 이유 투명하게 공개

**사용법**
```
댓글 이벤트 당첨자 5명 뽑아줘
https://www.youtube.com/watch?v=영상ID
```

**필요 도구**
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — 댓글 자동 수집에 사용
  ```bash
  pip3 install yt-dlp
  ```

---

## 설치 방법

스킬 파일을 Claude Code 스킬 디렉토리에 복사합니다.

```bash
cp -r youtube-comment-picker ~/.claude/skills/
```

이후 Claude Code를 재시작하면 스킬이 자동으로 인식됩니다.
