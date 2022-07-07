# Spring Boot 기반의 Todo Application

### git 커밋 메세지 템플릿 설정

- 템플릿 파일을 설정해놓으면 git commit 명령을 실행할 때 지정한 템플릿 메시지를 편집기에서 매번 사용할 수 있습니다.
- 커밋 시 템플릿 파일이 vi 편집기로 열리게 되면, 공백란에 형식을 맞춰 작성하여 `wq!`로 저장할 시 커밋이 수행됩니다.

```bash
$ git config --global commit.template <프로젝트 디렉터리>/.gitmessage.txt
```

### 백엔드 코드 실행

```bash
$ cd <프로젝트 디렉터리>/demo
$ ./gradlew bootRun
```