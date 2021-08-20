# Github
> 깃 관련 자료, 설정

## Index
- [Commit](#commit)
- [Readme](#readme)

## Commit
> [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/, "commit msg link")
1. Template
  ```
  $ git config --global commit.template ~/.gitmessage.txt
  ```
2. 메시지 구조
  ```
  type: Subject

  body

  footer
  ```
3. 메시지 타입
  ```
  feat    : 기능 (새로운 기능)
  fix     : 버그 (버그 수정)
  refactor: 코드 리팩토링
  style   : 스타일 (코드 형식, 세미콜론 추가: 비즈니스 로직에 변경 없음)
  docs    : 문서 (문서 추가, 수정, 삭제)
  test    : 테스트 (테스트 코드 추가, 수정, 삭제: 비즈니스 로직에 변경 없음)
  chore   : 기타 변경사항 (빌드 스크립트 수정 등)
  delete  : 삭제
  rename  : 이름 변경
  move    : 코드, 파일 이동
  delete  : 삭제
  ```
4. 메시지 rule
- 제목
  - 첫 글자 대문자, 최대길이 50, 마침표x
  - 과거시제x 명령문o
  - 본문과 한 줄 띄워 분리
- 본문 (선택사항)
  - "어떻게"보다 무엇을, 왜에 맞춰 작성
  - 한줄 최대 72
- Footer (선택사항)
  - 이슈를 자동 종료하고, 필요한 경우 관련 이슈, 참고 이슈 작성
  - close : 일반 개발 이슈
  - fix : 버그 픽스나 핫픽스 이슈
  - resolve : 문의나 요청사항에 대응한 이슈
## Readme
- [markdown](https://gist.github.com/ihoneymon/652be052a0727ad59601, "github link")
- [template](https://github.com/sujinleeme/readme-template/tree/master/korean, "readme template link") 
