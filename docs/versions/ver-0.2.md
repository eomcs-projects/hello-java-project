# Ver-0.2 애플리케이션 메인 클래스 작성

자바 애플리케이션을 시작시키는 메인 클래스를 작성한다.

## 학습 목표

- 자바 언어로 간단한 문자열을 출력하는 코드를 작성할 수 있다.
- JDK를 사용하여 자바 언어로 작성된 코드를 컴파일하고 실행할 수 있다.
- 컴파일러와 소스 코드, 바이트코드의 관계를 설명할 수 있다. 
- JVM과 바이트코드의 관계를 설명할 수 있다.
- 컴파일러와 인터프리터의 동작 원리를 설명할 수 있다.
- main() 메서드와 entry point를 설명할 수 있다.

## 사용할 도구와 기술

### 도구

- VSCode 편집기
- JDK 21

### 자바 기본 문법

- 클래스 문법
- main() 메서드 작성법

## 작업

### 1. 자바 소스 파일 생성

프로젝트 디렉토리에 App.java 소스 파일을 생성한다.  

```
hello-java/
├── App.java
```

### 2. 자바 코드 작성

애플리케이션 이름을 출력하는 자바 코드를 작성한다.

```java
// App.java
public class App {
  public static void main(String[] args) {
    System.out.println("수업 관리 시스템");
  }
}
```

### 3. 컴파일

자바 소스 코드(.java)를 컴파일하여 바이트코드(.class)를 생성한다.

```zsh
[~/hello-java]$ javac App.java
```

```
hello-java/
├── App.java
├── App.class
```

### 4. 실행

바이트코드(.class)를 실행한다.

```zsh
[~/hello-java]$ java App
수업 관리 시스템
```