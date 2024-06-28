# android-contacts
**카카오 테크 캠퍼스 STEP2 Android 1주차 1단계 미션 - 연락처 추가**
## 기능 요구사항
### 1단계 기능
- 연락처를 추가한다.
- 이름과 전화번호는 필수 값이다.
  - 입력하지 않으면 토스트 메시지를 보여준다.
- 전화번호 입력은 숫자만 가능하다.
- 더보기를 눌러 입력 폼을 확장할 수 있다.
  - 생일, 성별, 메모 입력 폼이 등장한다.
  - 성별을 둘 중 하나를 선택할 수 있다.
- 저장 버튼을 누르면 '저장이 완료되었습니다' 라는 토스트 메시지를 보여준다.
- 취소 버튼을 누르면 '취소 되었습니다' 라는 토스트 메시지를 보여준다.
### 2단계 기능
- 연락처 등록 화면을 구현한다.
- 연락처를 저장하면 목록에 추가된다.
- 저장된 연락처가 많을 경우 목록은 스크롤 되어야 한다.
- 추가된 연락처를 선택하여 상세 화면을 볼 수 있다.
- 연락처 작성 중 뒤로가기 버튼을 누르면 확인 팝업이 나타난다.
- 추가된 연락처는 앱을 다시 실행하면 유지되지 않는다.

## 구현할 기능 목록
### 1단계 기능
- [x] 이름, 전화번호 입력 폼 구현
- [x] 전화번호 입력 폼 숫자 키보드로 전환
- [x] 더보기를 눌러 입력 폼 확장 기능 구현
- [x] 키보드로인한 화면 가릴시를 위한 스크롤 기능 구현
- [x] 생일, 성별, 메모 입력 폼 구현
- [x] 성별 입력 폼 남,여 둘 중 하나만 선택 가능하게 하기
- [x] 하단 취소, 저장버튼 ripple 효과 넣기
- [x] 저장 버튼을 누르면 토스트 출력
  - [x] 필수 입력 값 미입력시 별도 메시지 출력
  - [x] 미입력된 항목으로 Focus 이동
- [x] 취소 버튼을 누르면 토스트 메시지 출력
### 2단계 기능
- [x] 연락처 등록 화면 구현
- [x] 연락처 목록 화면 구현
  - [x] 연락처 초과 시 스크롤 기능
  - [ ] 연락처 터치 시 상세 화면 이동
- [ ] 연락처 상세 화면 구현
- [x] 연락처 작성 중 뒤로가기 실행시 입력 데이터 존재 확인
  - [x] 데이터가 존재하면 확인 다이얼로그 출력