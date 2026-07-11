# 보안 정책 (Secure Development Strategy)

## 지원 버전
이 저장소는 실습용이며 `main` 브랜치만 유지된다.

## 취약점 신고
보안 취약점을 발견하면 Issues 대신 저장소 관리자에게 비공개로 알려주세요.

## 필수 검사
- CodeQL 코드 스캐닝: 모든 main 푸시에서 자동 실행
- Dependabot: 의존성 취약점 주간 스캔
- 시크릿 스캐닝 Push Protection: 커밋 전 시크릿 유출 차단
