# Linux Shell

### Linux vi Editor
* Linux, Unix 환경에 가장 널리 사용되는 Text Editor
* 최초실행을 하면 명령어 입력상태가 된다.
* i, o : 내용을 추가, 수정, 삭제를 하려면 편집상태로 변환해야한다.
* ESC : 저장, 끝내기 등을 수행하려면 명령어 입력상태가 되어야 한다

* :w(콜론w) : 명령어 입력상태, 편집한 내용을 저장하기
* :q(콜론q) : 명령어 입력상태, 현재 편집기를 종료하기
* :wq(콜론wq) : 명령어 입력상태, 편집한 내용을 저장하고 종료 동시
* :q!(콜론q!) : 편집하는 도중에 문서내용이 얽키게 되어 내용 많이 망가질 경우 현재 편집된 내용을 포기하고, 최초에 파일을 열었던 상태로 유지하고 싶을때가 있다. 편집포기, 편집된 내용을 저장하지 않고 끝내기

## shell 명령어
#### cd( chdir ) : 현재 작업 디렉토리(폴더)를 변경하는 명령어
* cd 명령만 입력 : 사용자의 home 디렉토리로 이동하는 명령(/home/callor)
* cd 디렉토리이름 : 특정한 디렉토리로 이동하기
* cd /(슬래시) : root 디렉토리로 이동하기, 최상의 디렉토리로 이동하기
* .(점1개), ..(점2개) : 디렉토리 개념에 매우 중요한 개념
* .(점1개) : 현재디렉토리, ..(점2) : 나의 부모디렉토리
* cd aaa : 현재디렉토리에 가지가 붙어있는 aaa 디렉토리로 이동하라
* cd ../aaa : 현재디렉토리에서 부모디렉토리로 이동한 후 가지가 붙어있는 aaa디렉토리로 이동하라
* cd /c/biz/work/java : 일단 root로 이동하고 거에서 부터 순서대로 biz디렉토리로 이동하고 work로 이동하고 java 디렉토리로 이동하라

#### mkdir : 디렉토리를 만들기
#### ls : 현재 리렉토리에 저장되어 있는 파일, 디렉토리를 보여달라
* 윈도우 CMD : dir
* ls -al : 현재 디렉토리에 저장되어 있는 파일, 디렉토리를 모두 자세히 보여달라. 숨긴파일도 보여준다.
* linux에서 .으로 시작되는 파일은 숨김파일이다. ls 명령으로는 파일을 볼수 없고, ls -al 명령으로만 확인 된다.

#### cat : text 파일의 내용을 확인
* text 파일의 내용을 editor를 사용하지 않고 확인하기
* 윈도우 CMD : type




