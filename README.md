# CLI Puzzles

터미널 명령어를 퍼즐로 배우는 인터랙티브 연습 도구입니다.

## 시작하기

```bash
git clone https://github.com/isnbh0/git-cli-puzzles.git
cd git-cli-puzzles
git checkout world-level1
cd start
cat note
```

## 레벨 목록

각 레벨은 별도의 Git 브랜치입니다. `git checkout` 으로 전환하세요.

| 브랜치 | 난이도 | 배우는 명령어 |
|--------|--------|---------------|
| `world-level1` | ★☆☆☆ | `ls`, `cat`, `cd`, `pwd` |
| `world-level2` | ★★☆☆ | `cd ..`, `pwd` (되돌아가기) |
| `world-level3` | ★★★☆ | `mkdir`, `cp`, `mv`, `rm` |
| `world-level4` | ★★★★ | 전체 복습 (종합 퀘스트) |

## 플레이 방법

1. 레벨 브랜치로 전환합니다: `git checkout world-level1`
2. `cd start` 로 시작 폴더에 들어갑니다
3. `cat note` 로 안내를 읽습니다
4. 안내를 따라 명령어를 입력합니다

## 처음부터 다시 하기

파일을 바꿔 버렸더라도 걱정하지 마세요:

```bash
cd ~
git checkout world-level1
cd start
cat note
```

## 요구 사항

- Git
- 터미널 (PowerShell, bash, zsh 모두 지원)
