# AI Playground

Spring Boot 백엔드와 향후 React 프런트엔드를 함께 관리하기 위한 모노레포입니다.

## 프로젝트 구조

- `backend/`: Java 25 및 Spring Boot 기반 백엔드 애플리케이션
- `frontend/`: React 프런트엔드 추가 예정
- `gradle/`, `gradlew`, `gradlew.bat`: 저장소 공용 Gradle Wrapper

## 백엔드 명령어

Java 25가 활성화된 환경에서 실행합니다.

```bash
./gradlew :backend:bootRun
./gradlew :backend:test
./gradlew :backend:build
```
