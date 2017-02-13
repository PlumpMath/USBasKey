# USB 스크린 세이버

평문의 암호대신 USB를 일종의 키로 사용하는 화면 잠금 프로그램

## [KeyMaker](/KeyMaker)

키 등록/수정/삭제가 가능합니다. 현재는 콘피그 파일 `key.config` 파일로 저장이 됩니다.

## [USBasKey](/USBasKey)

화면을 잠그는 프로그램입니다. 키로 등록된 USB가 컴퓨터에 삽입되어 있거나 실행 중 삽입이 되면 잠금이 해제되면서 프로그램이 종료됩니다. 현재는 콘피그 파일 `key.config` 로부터 설정을 읽어옵니다.

------
### **TODO**
- **보안 강화**
- 리팩토링
- 그래픽 최적화 (WPF로 다시 만들 의향이 있음)
- 잠금 해제에 필요한 도구를 추가할 생각. 셀카봉이라던가