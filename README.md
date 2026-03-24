# 스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술
위 강의를 들으며 공부한 내용을 정리한 레포지토리입니다.

[강의 링크](https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81-%EC%9E%85%EB%AC%B8-%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8/dashboard?cid=325630)
- 공부 시작일: 2026년 3월 24일 (화)

## 공부한 내용들 (토막 상식)
- **Maven, Gradle**은 빌드 도구 + 의존성 관리 도구로, JS로 치면 npm, pnpm, yarn이랑 비슷한 것이라고 보면 된다.
- `build.gradle`은 프로젝트 정보, 의존성 등을 저장하는 파일로, JS로 치면 package.json이랑 비슷한 것이라고 보면 된다.
- Project View에서 보이는 **External Libraries**는 외부 의존성 파일 목록을 보여주는 디렉토리로, JS로 치면 node_modules와 같다고 보면 된다.
  - 그런데 실제로 프로젝트 디렉토리 내에 설치된 것은 아니고, 중앙 저장소에 다운로드 된 라이브러리들의 링크해서 보여주는 것이다. (pnpm과 비슷함)
- 빌드 및 실행 방법
  - `./gradlew build` 명령어를 통해 빌드하면, /build/libs에 jar 파일이 생성된다.
  - `java -jar ./build/libs/파일이름.jar`명령어를 통해 실행할 수 있다.