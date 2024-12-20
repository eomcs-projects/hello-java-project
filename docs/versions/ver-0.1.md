# Ver-0.1 프로젝트 디렉토리 생성

자바 프로젝트 관련 파일을 놓아 둘 디렉토리를 준비한다.

## 학습 목표

- CLI(Command Line Interface) 환경에서 간단히 디렉토리를 다룰 수 있다.

## 사용할 도구와 기술

### 도구

- 윈도우: 명령창
- macOS/리눅스: 터미널

### 리눅스 명령

mkdir - 새 디렉토리 생성. *make directory*
```zsh
mkdir [옵션] [생성할 디렉토리 이름]
```

ls - 지정한 디렉토리에 있는 파일과 하위 디렉토리 확인. *list*
```zsh
ls [옵션] [확인할 디렉토리 경로]
```

cd - 현재의 작업 디렉토리를 변경. *change directory*
```zsh
cd [이동할 디렉토리 경로]
```

## 작업

### 1. 디렉토리 생성

사용자 홈 디렉토리에서 ***hello-java*** 디렉토리를 생성한다.  

```zsh
[~]$ mkdir hello-java
```

### 2. 디렉토리 확인

생성된 디렉토리를 확인한다.

```
[~]$ ls -l
...
drwxr-xr-x    2 eomjinyoung  staff    64 12 19 10:05 hello-java
...
```

### 3. 작업 디렉토리 변경

현재 작업 디렉토리를 새로 생성한 디렉토리로 변경한다.

```
[~]$ cd hello-java
[~/hello-java]$
```

