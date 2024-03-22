https://www.notion.so/8f705f3c79f34820bff746188d1c6e8d (초기 기획안)

## 정벼리 담당 기능 요약 ##

1. BeautifulSoup과 Flask 서버를 통한 유기동물정보 크롤
 - 국가동물보호정보시스템에서 공고중인 모든 유기동물 정보를 스케쥴러에 
   등록된 시간에 맞춰 크롤링 
  (https://www.animal.go.kr/front/awtis/public/publicList.do)
 - 리액트의 geoLocation -> 카카오API를 통해 받은 도로명주소를 확인하여 
   사용자가 속한 지역의 유기동물정보들만을 CSS 키프레임을 사용하여 
   부드럽게 렌더링
 - 렌더링 된 각 아이템들을 클릭하면 국가동물보호정보시스템의 
   상세정보페이지로 이동함
 
2. 확인사항
 - 멍냥멍냥 프론트엔드(https://github.com/VerifiedIdiot/Doggo-frontend)
 - 멍냥멍냥 백엔드(https://github.com/VerifiedIdiot/DoggoEx)
 - 멍냥멍냥 플라스크(https://github.com/VerifiedIdiot/DoggoFlask)
 - 멍냥멍냥 통합(https://github.com/VerifiedIdiot/DoggoTotals)

인사담당관님의 피드백을 환영합니다!
