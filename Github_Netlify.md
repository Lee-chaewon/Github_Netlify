# Github&Distribution

## Netlify
  * 주소 : https://www.netlify.com
  * 배포
      1. 작성한 코드 업로드
      2. github으로 sign up 
      3. Create a new site
      4. Deploy


## Github

### Git
  * 파일의 변천사를 저장
  * 코드의 변천사를 기록
### Github
  * Git과 코드를 저장, 관리
  * 개발 포트폴리오
### Git 명령어
  * git init : git 저장소를 초기화
  * git add . : 폴더에 변경된 모든 파일을 staging area에 올리기
  * git commit -m "커밋에 대한 설명" : 유사 시 돌아갈 수 있는 저장소의 체크 포인트 생성
  * git remote add origin https://원격저장소주소.git : 원격저장소 (remote repository) 연결
  * git branch 브랜치 이름 : 새로운 브랜치를 생성
  * git checkout 브랜치 이름 : 해당 브랜치로 이동
  * git push origin 브랜치 : 원격 저장소의 특정 브랜치에 프로젝트 저장
  * git pull origin 브랜치 : 원격 저장소의 특정 브랜치에서 변경사항 pull 해오기
  * git clone https://원격저장소주소.git : 원격 저장소에 있는 파일 전체 복사
  * git status : git 저장소의 상태를 확인
    
### Github를 이용한 협업
  1. 원격 저장소 생성(Github repository 생성)
  2. 팀원을 collaborator로 추가
  3. 초기 프로젝트 push
  4. 팀원들의 로컬에 프로젝트 pull
  5. 팀원 각자의 브랜치를 생성하여 작업
  6. 브랜치에 작업한 내용을 push
  7. Master와 merge 하기 전에 pull request
  8. Pull request한 후 Master와 Merge
  
### Fork를 이용한 협업
  1. 작업하고 싶은 Repository fork해오기
  2. 자신의 로컬에서 작업
  3. 변경사항을 자신의 브랜치에 push
  4. 원본 레포지토리 소유자에게 pull request 요청
  5. 소유자가 pull request를 승인하여 merge하면 자동으로 collaborator 추가
    
