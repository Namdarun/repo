### remote ropository 연결하기

### remote repo 생성하기

1. 기본 브렌치 이름 master로 변경하기
2. new Repo  생성 버튼 눌러서 

        1. 이름 설정
        1. 만들기!

### Local

0. 새로운 디렉토리 생성 : 
   1. mkdir(make directory)
   2. cd (경로)
   3. git init 
   4. git remote add origin (원격 repository 주소-url)
   5. git remote origin 이름으로 remote 추가된 것 확인 
   6. touch Readme.md
      1.  내용 수정 (optional)



1. 버전 남기기(repository로 push 하기 전에 반드시 commit이 있어야 한다.)
   1. git add (파일명 확장자 파일명 확장자 파일명 확장자...)
   2. git add . (현재 위치한 모든 수정사항)
   3. git commit -m "first commit"
2. git push origin master
2. git push -u origin master

 이후엔 git push만 해줘도 해당 repository로 간다 