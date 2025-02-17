## 📕프로젝트 설명
본 프로젝트는 로또 게임을 구현하는 것이다. 로또 게임은 사용자가 구매한 로또(1~45사이의 중복되지 않은 6개의 수로 구성)를
당첨번호 및 보너스 번호와 매치하여 당첨 내역과 수익률을 출력하는 게임입니다.

---
## ✏️구현할 기능 정리
- [x] 로또 번호 6개를 랜덤으로 생성하는 기능
- [x] 로또 번호를 오름차순으로 정렬하는 기능
- [x] 당첨 번호를 입력하는 기능
- [x] 보너스 번호를 입력하는 기능
- [x] 당첨 번호와 로또 번호를 비교하여 같은 수의 개수를 반환하는 기능
- [x] 로또 번호가 보너스 번호를 포함하는지 판별하는 기능
- [x] 당첨 번호와 로또 번호를 비교하여 등수를 정하는 기능
- [x] 로또 구입 금액을 입력하는 기능
- [x] 총 상금 금액을 산출하는 기능
- [x] 수익률을 산출하는 기능(소수점 둘째 자리에서 반올림)
- [x] 구매한 로또 번호를 출력하는 기능
- [x] 당첨 결과를 출력하는 기능
- [x] 수익률을 출력하는 기능
- [x] 게임을 실행하는 기능 
- [x] 게임 오류 발생시 오류를 처리하는 기능
---
## ⚒️예외처리
- [x] 로또 번호가 서로 다른 번호로 구성되었는지 검증 기능
- [x] 로또 번호가 1부터 45사이에 수로 구성되어 있는지 검증 기능
- [x] 보너스 번호가 1부터 45사인지 검증하는 기능
- [x] 보너스 번호가 기존 로또 번호와 겹치지 않는지 검증 기능
- [x] 당첨 번호가 숫자와 ,로 구성되었는지 검증 기능
- [x] 당첨 번호의 ,의 위치가 처음과 끝이 아닌지 검증 기능
- [x] 로또 구입 금액이 숫자로 구성되어있는지 검증 기능
- [x] 로또 구입 금액이 1000원 단위로 입력되었는지 검증
- [x] 보너스 번호 입력이 숫자인지 검증 기능
- [x] 구입 금액은 1000원보다 큰지 검증 기능
- [ ] 당첨 번호는 ,로 분리시 숫자만 있는지 검증 기능