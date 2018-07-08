# Git 최신상태로 유지하기

### 복습

git config -- list : git config 리스트가 어떻게 설정이 됐는지 볼 수 있음 (유저 정보가 제대로 연결됐는지)

vi 언어 

:w ->저장

:wq ->저장하고 닫기

:q  -> 닫기

git push -u : -u 는 upstream 

git push -u origin master : 

commit 은 로컬에서 계속하다가 push는 완성 페이지 한번만 한꺼번에 해도 됨. 

mkdir : 폴더 만들기 

git commit -m '내용' : 커밋 내용 써주는 것

typora에서 작성하고 터미널에서 add- commit- push

## git branch

히스토리 관리 / 협업을 용이하게 하기 위해서 

-스타트업이나 IT업계는 많이 사용함. 대기업은 기업만의 형상 소스를 갖춰서 씀.

-네이버웍스 : 네이버 플랫폼 내에서 작업할 수 있는 폼을 개발하는 부문

-git checkou - b 2018 



### Git 최신상태로 유지하기

upstream : ?? origin 이랑 무슨차이지?  origin은 저장할 저장소 upstream 은 콘텐츠를 받아올 저장소?

git pull --rebase 하게 되면 add와 commit 할 필요없이 push만 해주면 됨

#### - upstream 설정하기

1. git clone 깃헙 리퍼지토리 클론 주소 복사
2. cd (복사해온 리퍼지토리명)
3. git remote -v : origin 설정이 잘 됐는지 확인
4. git remote add upatream (포크해온 진짜 계정의 clone 주소): upstream 등록한 다음에 
5. git pull --rebase upstream master
6. git push -u origin master  



$ cd c://dataitgirls  : c드라이버의 dataitgirls로 가기 

git push -f origin master : 강제로 push하기 

- update해야할때, pull ~ push 단계를 거치면 되지만 안되는 경우 

다음의 경우 따름. 

1. git add . :  untracked 파일이 tracked파일로... unstage 가 stage 상태로

2. git commit -m 'addfiles'

   (만약에 오류나면)

3. git pull --rebase --autostash upstream master

   한 이후, 

### 시빅해킹

공공문제를 해결하는 프로그램을 만들거나



사건은 여러장소에서 동시다발적으로 발생 

EXIF : 사진이나 영상 파일에 들어있는 메타정보

사진은 사건을 담는다는 가정을하고! 

EXiF파일로부터 데이터 뽑어냄 : 시간정보랑 GPS정보 있음. 

www.vvitness.kr

-> 베이루트에서 테러가 일어났다는 사실에 대해 알고 있는가?

내가 알지못하는 사건들이 굉장히 많이 발생하고 있으나 우리는 

그를 발견할 수 있는 채널이 없으면 알 수 없다. 

트위터 데이터를 디텍팅하면 실시간으로 알 수 있음. 

: 내가 세상에 대해서 아는게 정말 없었구나...

국회 데이터 파싱하기 어려움 --> 열려라 국회 라는 사이트에서 회의록들을 손으로 작성해서 업로드해주는 사람들이 있음. 

MCMC ID IRT

정보공개 청구 포털 / 정보공개센터(정보공개 청구를 통해 이슈같은 것들을 해석하는 시민단체) 



open data day : 전세계 행사 

공공데이터를 바탕으로 프로젝트하는 (*jonmat : 국회맛집지도)



### 바르지 못한 데이터 분석의 더 무서운 결과

데이터 분석은 언제나 완벽한 분야가 아니며 잘못될 수 있다는 자세를 가지고 겸손하게 해야함. ex : 성격유형검사의 경우 100%완벽한 모형이라고 할 수 없기 때문에 그를 바탕으로 판단 오류를 범하면 안됨

실제로 성격유형검사가 있는 곳이 오히려 그런식으로 성격이 분류되는 경향이 크고 그런 검사가 없으면 

뉴스타파 / 깃헙있음 / sl@dotface.kr 김슬

- 널채움 (null채움)
- pyjog 

R은 프로그래밍 언어를 만든 사람이 만든게 아님. 그럼에도 불구하고 통계학 커뮤니티 자체가 R을 기반으로 만들어져서 알고리즘이 풍부하고 많음. 

Python 은 아직 알고리즘이 풍부하지는 않음 

growth 쪽으로 
