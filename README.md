# 바로 써먹는 Git 상황들
- 글쓰는 목적: 프로그래밍할 때 git을 보다 풍부하게 사용하고자
- 글쓰는 기간: 무기한
 
## 0.1 Git의 원리 이해하기

## 0.2 Git과 GitHub는 다르다

## 0.3 Git을 배워야 하는 이유

## 1.0 프로젝트를 Git 트래킹하려면(Git 시작하기)
- 로컬PC의 경우, Git을 설치한다
  - 자신이 사용하는 console에서 `git -v`으로 설치여부를 확인할 수 있다
- GoormIDE의 경우, 프로젝트 생성과 함께 git이 자동 설치된다
- `git init`을 한다
- `.git` 폴더가 생성되며 `ls`로 확인 가능하다

## 1.0.1 git 상황별 문제대처법
- console에 `git` 명령어가 작동 안할 때,
  - 지금 경로가 맞는지 확인. 안맞으면 `cd`

## 1.1 프로젝트 변경사항 저장(Commit)하기
- `git add .`
- `git commit -m "[COMMIT명]"`

## 1.1.1 Commit의 다양한 상황들 대처하기
- 앞서 commit을 덮어씌우고 싶을 때
  - `git commit --amend --no-edit`

## 1.2 이전 Commit 시점으로 RollBack하기
  - `git reset --hard HEAD(^)`

## 3.1 GitHub에 프로젝트 올리기
- Git Respository 만들기
  - 
- 프로젝트를 Respository에 올리기
  - `git remote add origin [Repository_URL]`
- Respository에 프로젝트의 최신버전 업데이트하기
  - `git push origin master` 또는 `git push origin main`

## 3.1.1 GoormIDE에서 프로젝트를 GitHub에 올리기

## 3.1.2 상황별 문제해결법
- 원격저장소(remote origin)을 다시 설정하려면

## 3.2 GitHub에 업로드된 프로젝트 다운로드 받기
- `git clone [Repostiory_URL]`

## 4.0 GitHub로 협업하기 - (1) 프로젝트 분업하고 합치기(Branch&Merge)

## 4.1 GitHub로 협업하기 - (2) 버그 보고하고 수정하기(Issue)
