# CLI Puzzles

터미널 명령어를 퍼즐로 배우는 인터랙티브 연습 도구입니다.

## 시작하기

```bash
git clone https://github.com/isnbh0/git-cli-puzzles.git
cd git-cli-puzzles/level1/start
cat note
```

## 레벨 목록

| 폴더 | 난이도 | 배우는 명령어 |
|------|--------|---------------|
| `level1/start` | ★☆☆☆ | `ls`, `cat`, `cd`, `pwd` |
| `level2/start` | ★★☆☆ | `cd ..`, `pwd` (되돌아가기) |
| `level3/start` | ★★★☆ | `mkdir`, `cp`, `mv`, `rm` |
| `level4/start` | ★★★★ | 전체 복습 (종합 퀘스트) |

## 플레이 방법

1. `cd level1/start` 로 시작 폴더에 들어갑니다
2. `cat note` 로 안내를 읽습니다
3. 안내를 따라 명령어를 입력합니다

## 처음부터 다시 하기

파일을 바꿔 버렸더라도 걱정하지 마세요.
(첫 줄은 "이 저장소의 최상위 폴더로 이동" 이라는 뜻입니다. 그대로 복사해서 붙여넣으세요.)

레벨 1, 2, 4 는 파일을 바꾸지 않으므로 그냥 돌아가면 됩니다:
```bash
cd "$(git rev-parse --show-toplevel)"
cd level1/start
cat note
```

레벨 3 은 파일을 직접 수정하므로 복원이 필요합니다:
```bash
cd "$(git rev-parse --show-toplevel)"
git restore level3/start/    # level3 파일을 원래대로 복원합니다
cd level3/start
cat note
```

## 요구 사항

- Git
- 터미널 (PowerShell, bash, zsh 모두 지원)
