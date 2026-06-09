# Bigtablet 오픈소스 기여 가이드

[English](https://github.com/Bigtablet/.github/blob/main/CONTRIBUTING.md) | **한국어**

**Bigtablet Inc.**(이하 "회사")에서 공개하는 오픈소스에 기여해 주셔서 감사합니다. 본 문서는 기여를 시작하기 전 모든 기여자가 알아야 할 필수 사항을 정리한 것입니다. 프로젝트별 세부 규약(아키텍처, 코드 스타일 등)은 각 저장소의 자체 문서를 참고하세요.

> 본 원칙을 따르지 않아 발생하는 모든 문제의 책임은 기여자 개인에게 있습니다.

## 기여자와 관리자

- **기여자(Contributor)** — 외부 기여자. 본 `.github` 저장소의 공용 풀리퀘스트/이슈/커밋 가이드를 준수해야 합니다.
- **관리자(Maintainer)** — 회사 소속 기여자. 리뷰·승인 및 병합 권한을 가집니다.

## 기여 원칙

1. 본 `.github` 저장소에 지정된 공용 풀리퀘스트/이슈/커밋 가이드를 준수합니다.
2. **관리자 승인 없는 병합을 금합니다.** 모든 변경은 관리자의 리뷰·승인 후에만 병합됩니다.
3. 기여자가 고의 또는 실수로 악성 코드, 바이러스, 랜섬웨어 등 소프트웨어에 악영향을 줄 수 있는 사항을 병합하려 시도하거나 병합할 경우, 이에 따라 발생한 모든 피해의 책임은 해당 기여자에게 있습니다.
4. 기여자가 제시한 사항이 실제 소프트웨어에 반영되지 않을 수 있습니다.
5. 다음에 해당하는 기여는 **허용되지 않으며**, 관련 이슈·풀리퀘스트는 생성 즉시 삭제됩니다.
   - 라이브러리 또는 의존성 버전 변경
   - 팀 코드 컨벤션 원칙에 어긋나는 사항
   - 사용 기술 스택 변경
   - CI/CD 및 기타 배포 파일 변경

## 언어

- 풀리퀘스트·이슈 가이드는 원칙적으로 **한국어**로 작성합니다.
- 해외 기여자는 **영어**로 제출할 수 있습니다.
- **커밋 메시지는 항상 영어로 작성합니다** ([커밋 가이드](https://github.com/Bigtablet/.github/blob/main/COMMIT_GUIDELINE.ko.md) 참고).

## 기여 방법

1. **이슈 생성** — [이슈 템플릿](https://github.com/Bigtablet/.github/tree/main/.github/ISSUE_TEMPLATE) 중 하나로 이슈를 생성합니다(빈 이슈는 비활성화). 위 금지 기여에 해당하지 않는지 확인합니다.
2. **브랜치 생성** — `label/domain` 형식으로 브랜치를 만듭니다(예: `feat/auth`, `fix/user`, `docs/readme`). 외부 기여자는 먼저 저장소를 포크한 뒤 베이스 브랜치에서 분기합니다. `label`은 커밋 라벨과 동일한 체계를 따릅니다.
3. **변경 및 커밋** — `label: message` 형식의 영어 커밋으로 작업합니다. 라벨과 규칙은 [커밋 가이드](https://github.com/Bigtablet/.github/blob/main/COMMIT_GUIDELINE.ko.md)를 참고하세요.
4. **풀리퀘스트 생성** — [PR 템플릿](https://github.com/Bigtablet/.github/blob/main/.github/PULL_REQUEST_TEMPLATE.md)을 사용하고, 본문에 `Closes #N`으로 관련 이슈를 연결한 뒤 관리자에게 리뷰를 요청합니다.
5. **리뷰 & 병합** — 관리자가 리뷰하고 승인·CI 통과 후 병합합니다. 본인 작업을 직접 병합하지 않습니다.

## 라이선스

본 오픈소스는 [Bigtablet Inc. 오픈소스 라이선스](https://github.com/Bigtablet/.github/blob/main/BIGTABLET_LICENSE.md)에 따라 **비상업적 이용·출처 표기** 조건으로 공개됩니다. 저장소를 clone/fork/복제하는 것은 라이선스 전 조항에 동의한 것으로 간주됩니다. 기여 전 전체 조항을 확인해 주세요.

## 공용 문서

| 문서 | 링크 |
|------|------|
| 오픈소스 라이선스 | [BIGTABLET_LICENSE.md](https://github.com/Bigtablet/.github/blob/main/BIGTABLET_LICENSE.md) |
| 커밋 가이드 | [COMMIT_GUIDELINE.ko.md](https://github.com/Bigtablet/.github/blob/main/COMMIT_GUIDELINE.ko.md) |
| PR 템플릿 | [PULL_REQUEST_TEMPLATE.md](https://github.com/Bigtablet/.github/blob/main/.github/PULL_REQUEST_TEMPLATE.md) |
| 이슈 템플릿 | [ISSUE_TEMPLATE](https://github.com/Bigtablet/.github/tree/main/.github/ISSUE_TEMPLATE) |
