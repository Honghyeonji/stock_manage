# 재고관리 서비스
1. 아이템과 총 재고, 재고 발품 단위, 현재 재고량 입력
2. 재고 수정 - 현재 재고량, 총 재고량 수정 가능
3. 재고 출품 - 재고량 하나 출품
4. 총재고량과 현재 재고량 비교하여 게이지바로 보이게 함
5. 재고 추가 - 필요한 재고량 입력하면 장바구니같은 것에 해당 재고와 재고량 추가됨
6. 어떤 분야에서든 재고 관리에 용이하게 유연한 기능으로 배치해야 함


피그마 사이트
https://www.figma.com/file/Yd9xSvsR8UOL16upcb20tS/stock_manage?node-id=0%3A1


초기설정시 실행 안 되던 이유가 프로젝트가 속한 파일이 "바탕 화면" 이었기 때문에 한글이름 파일이라 경로의 폰트가 깨져서 발생한 오류였음
choco로 node패키지 설치하면 LTS버전이 아닌 가장 최근 버전이 설치됨 -> 17이상 버전은 npx react-native run-android시 에뮬레이터 실행 안 됨, node.js삭제하고 LTS버전으로 바꿔줘야 함.
