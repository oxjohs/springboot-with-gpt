# PR Playbook

이 문서는 springboot-with-gpt 레포의 PR을 올리기 전에 반드시 수행해야 하는
로컬 검증 절차를 표준화합니다.

## 1) Verify locally (필수)
프로젝트 루트에서 실행:

```bash
./gradlew test
./gradlew bootRun
