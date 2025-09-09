# Commit Message Guidelines

## Table of Contents / 목차
- [English Version](#english-version)
  - [Format](#format)
  - [Message](#message)
  - [Label](#label)
- [한국어 버전](#한국어-버전)
  - [형식](#형식)
  - [메시지](#메시지)
  - [라벨](#라벨)

---

## English Version

### Format

```text
label: message
```

1. Place a label representing the category at the beginning, followed by the commit message describing the changes.  
2. Use all lowercase letters, and follow camelCase if necessary.  

### Message

1. All commit messages must be written in **English**.  
2. Commit messages should clearly describe **where, what, and how** the changes were made.

   - Example: Developing authentication domain such as login/signup →
     
     ```text
     feat: add auth service
     ```

### Label

| Label  | Description |
| ------ | ----------- |
| feat   | Add a new feature / new code addition |
| fix    | Modify or improve a feature/code |
| bug    | Fix a bug/error |
| merge  | Merge branches |
| deploy | Project deployment / related documentation |
| docs   | Add or update documentation |
| init   | Initial project setup / creation |
| delete | Delete code/file/document |
| note   | Add comments |
| style  | Modify code style/structure |
| config | Update configuration files, dependencies, or libraries |
| etc    | For cases not covered above |

---

## 한국어 버전

### 형식

```text
label: message
```

1. 카테고리 별로 나누어진 라벨을 앞에, 커밋 내용을 담은 메시지를 뒤에 둔다.  
2. 모두 소문자로 하며 필요할 경우 카멜케이스를 따른다.  

### 메시지

1. 커밋 메시지는 모두 **영문**으로 통일한다.  
2. 커밋 메시지는 가능한 **어디서, 무엇을, 어떻게 했는지** 알아볼 수 있도록 작성한다.

   - 예) 로그인/회원가입 같은 인증 도메인 개발 →
     
     ```text
     feat: add auth service
     ```

### 라벨

| Label  | 설명 |
| ------ | ---- |
| feat   | 추가 기능 개발 / 새로운 코드 추가 |
| fix    | 기능/코드 수정 |
| bug    | 버그/에러 수정 |
| merge  | 브랜치 병합 |
| deploy | 프로젝트 배포 / 관련 문서 작업 |
| docs   | 문서 추가/수정 |
| init   | 프로젝트 최초 생성 / 초기 세팅 |
| delete | 코드/파일/문서 삭제 |
| note   | 주석 추가 |
| style  | 코드 스타일/구조 수정 |
| config | 기초 설정 파일 / 의존성 / 라이브러리 관련 버전이나 파일 수정 |
| etc    | 기타 위에 해당하지 않는 경우 |
