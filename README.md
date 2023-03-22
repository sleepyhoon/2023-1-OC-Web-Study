# love-you
## 깃허브에서의 명령어

1. git의 명령어 add,commit,push는 각각 어떤 역할을 하는지 정리하고, git pull과 fetch의 차이점을 정리하시오.
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

- git pull과 fetch의 차이점

git fetch는 로컬 Git에게 원격 저장소에서 최신 메타데이터 정보를 확인하라는 명령을 전달합니다. 단 fetch는 원격 저장소에 변경사항이 있는지 확인만 하고, 변경된 데이터를 로컬 Git에 실제로 가져오지는 않습니다. 반면 git pull은 원격 저장소에서 변경된 메타데이터 정보를 확인할 뿐만 아니라 최신 데이터를 복사하여 로컬 Git에 가져옵니다. git fetch를 사용하면 마지막 pull 이후 원격 저장소 또는 브랜치에 적용된 변경 사항을 확인할 수 있습니다. 만일 원격 저장소에 변경 사항이 존재하는 상황에서 pull을 바로 실행하면 현재 브랜치와 작업 복사본의 파일이 변경되는 동시에 새로 작업한 내용이 손실되는 일이 생길 수 있습니다. 따라서 fetch로 변경 사항을 먼저 확인한 후 pull을 실행하는 방법이 보다 안전합니다.



* * *
2. 지난 주와 이번 주 배운 내용들 정리

