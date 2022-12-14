# TIL

## 2022-09-21

### 오늘 한 일
- 3일 연속 아침 루틴을 해냈다
    - 모닝페이지, 러닝, SQL 1문제 풀기를 모두 끝냈다.
- 이보라 님의 Git/GitHub 기초 강의를 들었다
    - 리눅스 기본 커맨드라인(pwd, cd, ls)을 사용해봤다.
    - vim으로 파일을 수정(i)하고 저장(esc -> :wq)했다.
    - Git Bash에서 디렉토리를 생성하고 저장소와 연결하는 것을 해봤다.
- 데잇걸즈 기업 서비스 분석 소모임을 시작했다
### 오늘 느낀 것
- git을 한달 반 전에 이틀 동안 배웠었는데, 다시 해보니 여전히 어려웠다 
    - 역시 반복이 중요하다. 앞으로 TIL로 열심히 잔디를 심어볼 계획이다.
- 생각보다 바쁜 나날이다 
    - 공부와 소모임, 개인일 사이에서 중심을 잘 잡아야겠다. 컨디션 관리 잘하자.

## 2022-09-22
### 오늘 한 일
- 모닝페이지, 러닝, SQL 1문제 풀기까지 아침 루틴을 해냈다
- 스페이스 살림에서 미니 프로젝트 팀원들과 프로젝트 회고를 했다
- 줌으로 2022 데이터 이노베이션 포럼을 들었다
- 데잇걸즈 기업 분석 소모임을 위해 '서비스 역기획'에 관한 칼럼을 읽고 정리했다
### 오늘 느낀 것
- 회고를 해야 진정한 프로젝트의 마무리다
    - 똑똑한 팀원들의 회고를 들으며 또 많이 배웠다.
- 안전한 연결감을 느낄 수 있는 모임이 좋다

## 2022-09-23

### 오늘 한 일
- 모닝페이지, 러닝, SQL 1문제를 끝냈다
- 태블로 시각화 기초 강의를 들었다
    - 바, 라인, 파이 차트 그리기를 해봤다.
- 미니 프로젝트 팀원들과 만나 이력서와 포폴에 대한 아이디어를 나눴다 

### 오늘 느낀 것
- 할 일의 우선순위를 정하고 그걸 행하는 게 중요한 것 같다

## 2022-09-25

### 오늘 한 일
- 인프런 데이터리안 SQL 중급 강의 완강했다
- 티스토리를 오픈하고 글 하나를 남겼다
- 토스 기업 분석을 시작했다

### 오늘 느낀 것
- 오늘은 아니고, 요즘 느끼는 건데 가을을 타고 있는 것 같다
- 순간의 기분에 좌우되지 말아야지, 그저 묵묵히 할 일을 하자

## 2022-09-26

### 오늘 한 일
- 모닝페이지를 쓰고 러닝하고 SQL 1문제를 풀었다
- 에이블스쿨에서 태블로 시각화 기초 강의를 들었다
    - 드래그앤드롭으로 파이 차트, 산점도, 추세선 등을 그릴 수 있는 게 신기했다
- 하나 선배를 만났다
- 기업분석 소모임을 했다
    - 모은 내용을 내 언어로 바꾸고 그리는 것을 해야겠다
- 구글 정김경숙 님의 책을 읽고 있다
### 오늘 느낀 것
- 체력이 있어야 더욱 좋은 아이디어를 낼 수 있다
- 느리더라도, 변화가 더디더라도 꾸준히 하면 된다

## 2022-10-06
### 오늘 한 일
- 유재명 강사님의 통계 마지막 수업이었다
    - 텍스트 분석(유사도, 감성분석)을 공부했다
- 기업분석 소모임 마지막 날이었다

### 오늘 느낀 것
- 시간이 참 빠르다
- 그리고 통계는 재밌고도 어렵다
- 요행을 바라지 않는다, 꾸준히 천천히

## 2022-10-18

### 오늘 한 일
- 연희동에서 TeamDD 모임을 했다
    - 행복회로를 돌린 보람이 있다
- 웹사이트 I.A를 작성했다

### 오늘 느낀 것
- 인생은 타이밍
- 그렇지만 준비하는 사람만이 그 타이밍을 맞이할 수 있다

![0123](./img/0123.jpg)
---
### vim 사용법
> window에서 git을 사용할 때 default editor를 vim으로 세팅했기 때문에 git을 사용하려면 반드시 vim을 사용할 줄 알아야 함

### 명령 모드 vs. 입력모드
1. vim 에디터를 처음 켤 때는 명령 모드로 진입. 이때는 입력이 불가능 함
2. 입력하려면 입력 모드로 바꿔야 함
    - 입력 모드로 바꾸는 방법은 키보드에서 `i`키(insert) 등을 누름
4. 입력이 다 끝나고 저장 등의 명령을 컴퓨터에게 내리려면 명령 모드로 다시 돌아가야 함
    - 명령 모드로 바꾸려면 키보드에서 `esc`키를 누름
    - 명령 모드에서 `:w`를 입력하고 `enter`키를 누르 저장만 됨(write)
    - `:wq`를 입력하면 저장하고 에디터에서 빠져나올 수 있음(write and quit)
    - `:q`를 입력하면 그냥 에디터에서 빠져나올 수 있다(quit)

### commit
#### 정의
    - The "commit" command is used to save your changes to the local repository.
    - 커밋 하나는 독립적인 버전을 나타낸다
    - The git commit command captures a snapshot of the project's currently staged changes.
    - 스냅샷(사진)과 유사

#### 언제 커밋을 만드는가
    - logical한 변경이 있을 때 커밋을 하나 만든다
    - 가능하면 커밋 단위는 작을 수록 좋다