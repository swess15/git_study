## 제외목록 설정
- [.gitignore 파일](https://git-scm.com/docs/gitignore#_pattern_format)
- [추천 사이트](https://www.gitignore.io/)

## 원격 저장소
- 목록보기 : git remote -v 
- 추가하기 : git remote add [별칭] [주소]
- 삭제하기 : git remote rm [별칭]
- 별칭수정 : git remote rename [기존별칭] [새 별칭]
- 주소수정 : git remote set-url [별칭] [변경할주소]

## 브랜치
- 목록보기 : git branch
- 생성하기 : git branch [새 브랜치명] 또는 git branch [복사할 브랜치명] [새 브랜치명]
- 삭제하기 : git branch -d [브랜치명] 
- 이름변경(이동) : git branch -m [기존 브랜치명] [새 브랜치명]
- 전환하기 : git checkout [브랜치명]