# CLAUDE.md

이 저장소는 유튜브 채널 운영을 위한 Claude Code 커스텀 스킬 모음입니다.

## 저장소 구조

```
ai-edu/
└── youtube-comment-picker/
    └── SKILL.md        # 댓글 이벤트 당첨자 선정 스킬
```

## 스킬 설치

```bash
cp -r youtube-comment-picker ~/.claude/skills/
```

## 스킬 사용

스킬 설치 후 Claude Code에서 아래와 같이 호출합니다.

| 트리거 예시 | 실행 스킬 |
|------------|-----------|
| "댓글 이벤트 당첨자 뽑아줘" | youtube-comment-picker |
| "정성 댓글 골라줘" | youtube-comment-picker |
| "AI 댓글 걸러줘" | youtube-comment-picker |

## 사전 요구사항

댓글 자동 수집을 위해 yt-dlp가 설치되어 있어야 합니다.

```bash
pip3 install yt-dlp
```
