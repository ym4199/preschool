# Git Test

## The Basic Term

### *Command Line*
	
### Repository
프로젝트가 있는 디렉토리나 저장 공간.

### Version Control
여러 버전으로 나누어 저장. ex)수정_1, 수정_완료 등

### Commit 
깃에 파워를 주는 명령. 커밋하면 저장소의 스냅샷을 찍어, 프로젝트를 이전 상태로 재평가 또는 복원하는 체크포인트를 갖는다.
	
### Branch
하나의 프로젝트에서 다수의 사용자가 자신의 수정을 할 수 있도록 만든다.
	
## Instruction

### git init
깃 저장소 초기화. 저장소나 디렉토리 안에서 해당 명령을 실행 전까지 일반 폴더에 지나지 않는다. 해당 명령 입력 후에 추가적인 깃 명령 가능
	
### git config
설정 내용 확인하고 변경 가능. $git config --list 통해 설정을 확인 할 수 있다.	
	
### git status
저장소 상태 확인. 파일의 여부 확인과 커밋의 필요 변경사항 등
> git status -s  : 상태 파악
> 
> git status -a  : 모든 파일 상태 파악
	
### git add
새 파일을 추가하는 것이 아니고 새 파일이 생성되면 깃의 저장소 스냅샷에 포함.
> git add *  : 모든 파일을 인덱스 추가
> 
> git add 파일이름  : 해당 파일 인덱스 추가  
	
### git commit
**_가장 중요!!!_** 	
HEAD 에 반영하기 위한 과정(BUT github에 아직 반영되지 않음)
> git commit -m "상태를 설명"

### git push
컴퓨터의 커밋을 github에 반영하도록 한다.
> git push origin master

### git pull
github로 부터 변경사항을 받아온다.
> git pull 