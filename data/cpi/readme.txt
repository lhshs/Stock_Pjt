- a 월의 cpi 지표는 a+1월에 발표되므로 
  investing.com의 지표를 크롤링 후 괄호 안(a월) 날짜로 변경함
  ex) 2023년 10월 10일 (9월) -> 2023-09

- 근원 소비자 물가 지수가 있는 나라는 해당 데이터 모두 수집
   (core_cpi)

- 전월 대비, 전년 대비 데이터가 있는 나라는 해당 데이터 모두 수집
  (compare_last_month, compare_last_year)