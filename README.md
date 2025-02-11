# 🍞 Bakery Sales Data Analysis and Renewal Strategy
이 프로젝트는 제빵 매장의 판매 데이터를 분석하고, 효율적인 제품 리뉴얼 전략을 제안하는 분석 보고서입니다.  

## 📂 파일 구성  
- `bakery_data_processing.ipynb`  
  - 데이터 전처리 및 정리를 수행하는 노트북  
- `Sales_Insights_and_Renewal_Suggestions.ipynb`  
  - 판매 데이터 분석 및 리뉴얼 전략 제안 노트북  

## 📊 데이터 설명  
이 프로젝트에서 사용한 데이터는 다음과 같은 변수로 구성됩니다:  

- **`date`**: 거래가 발생한 날짜  
- **`time`**: 거래 시간 (HH:MM 형식, 24시간제)  
- **`ticket_number`**: 개별 거래를 식별하는 고유한 번호  
- **`article`**: 전처리 완료된 제품명  
- **`Quantity`**: 구매 수량 (이상치 처리 완료)  
- **`unit_price`**: 개별 제품 가격 (전처리 완료)  
- **`total_price`**: 제품 가격 × 수량  
- **`hour`**: 거래가 발생한 시간대 (07~19시, 이상치 처리 완료)  
- **`month_day`**: 구매 월과 일 정보  
- **`part_of_day`**: 시간대 구분  
  - 오전 (07:00-10:59)  
  - 점심 (11:00-14:00)  
  - 오후 (12:00-23:59)  
- **`weekday`**: 요일 (0 = 월요일, 6 = 일요일)  

※ 데이터 전처리 과정은 `bakery_data_processing.ipynb`에서 자세히 다루고 있습니다.  

## 🚀 실행 방법  
1. `bakery_data_processing.ipynb`를 실행하여 데이터를 정리합니다.  
2. `Sales_Insights_and_Renewal_Suggestions.ipynb`를 실행하여 분석 결과를 확인합니다.  

## 🔍 주요 분석 내용  
- **요일별 & 시간대별 매출 분포 분석**  
- **시간대별 주요 매출 제품 도출**  
- **제품 조합 분석** (함께 자주 구매되는 제품)  
- **비효율적인 제품 식별 및 리뉴얼 제안**  
