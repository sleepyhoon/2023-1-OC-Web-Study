# love-you
## 깃허브에서의 명령어


- git add

git add - 다음 변경(commit)을 기록할 때까지 변경분 모아놓는 작업
사용예시)
  git add 파일명 
  git add . // 전체 add (점(.)은 모든 것을 의미)
  git add *.txt // 모든 txt 파일 업로드
  git add project/app/*/ //디렉토리 업로드
  git add --update // 현재 git이 추적하고 있는 파일들만 add
  
  
- git commit

git commit -m "커밋내용" - staging area에 저장되어있는 변경 사항들을 로컬저장소에 등록(변경사항 확정)
git commit --amend -m "수정된 메시지"
커밋 메시지 잘못 작성했을 경우 메시지 수정


- git push

git pust -u origin master - 원격 저장소에 commit된 파일들을 모두 업로드

* * *
