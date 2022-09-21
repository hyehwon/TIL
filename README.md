# TIL

## 2022-09-21

### 오늘 한 일
- 이보라 님의 Git/GitHub 기초 강의를 들었다
    - 리눅스 기본 커맨드라인(pwd, cd, ls)을 사용해봤다.
    - vim으로 파일을 수정(i)하고 저장(esc -> :wq)했다.
    - Git Bash에서 디렉토리를 생성하고 저장소와 연결하는 것을 해봤다.  
### 오늘 느낀 것
- git을 한달 반 전에 이틀 동안 배웠었는데, 다시 해보니 여전히 어려웠다 
    - 역시 반복이 중요하다. 앞으로 TIL로 열심히 잔디를 심어볼 계획이다.

## 2022-09-22


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