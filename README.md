# EDA를 통한 카드 상점 매출 분석 및 고객 서비스 제안
   
### 목차   
>1. [주제 선정 및 배경](#1-주제-선정-및-배경)   
>2. [데이터 정의 및 전처리](#2-데이터-정의-및-전처리)   
>3. [EDA](#3-EDA)   
>4. [카드사별 특징 분석 및 서비스 제안 ](#4-카드사별-특징-분석-및-서비스-제안)   
  
       
### 1. 주제 선정 및 배경   
- 카드사의 주요 수익원은 회원 연회비 및 가맹점 수수료
- 아래의 이유로 카드사의 수익구조가 무너짐과 동시에 성장 한계에 직면함   
  >1)경제 성장률 둔화   
  >2)가맹점 수수료 인하   
  >3)조달비율 상승   
  >4)금리 상한 인하   
  >5)정부의 보수적 규제 장기화   
  >6)제 2금융 대출 규제 강화   
  >7)핀테크 활성화   
- 이를 극복하기 위해 카드사에서는 다음과 같은 전략 도출
  >1)비대면 영업채널 강화/ 고비용 마케팅 관행 개선   
  >2)규제 샌드박스 활용한 혁신적 금융 서비스 개발   
  >3)디지털 전담부서 조직개편 등 전사적 디지털 전환 추진 
   
- 최근 저비용 맞춤 결제 서비스에 대한 선호 증가로,    
      상점매출 데이터 활용한 사용자 패턴 분석을 진행하여 카드사별 고객 서비스 제안 해보고자 함

### 2. 데이터 정의 및 전처리
- 사용 데이터: 펀다 상점 매출 데이터 (https://dacon.io/competitions/official/140472/data)
![data](https://github.com/dureejung/project_2/blob/main/image/data.PNG)
- 추가컬럼
>1. 시간관련
> - year/month/dayofweek/hour : 'transacted_date'와 'transacted_time'을 기준으로 분리
> - holiday : 토/일요일 및 공휴일(특일정보 기준)인 경우 1, 평일인 경우 0   
> (특일정보: 공공데이터포털 특일정보 https://www.data.go.kr/data/15012690/openapi.do)
>2. 지역관련
> - sido : 'region'에서 광역시 및 도시를 분리
>3. 할부 관련
> - installment : 'installment_term'에서 일반적인 카드 할부수수료 증가 구간에 따라 할부 거래 구간 설정   
> (일시불, 2개월, 3-5개월, 6-9개월, 10-18개월, 19-32개월 단위) 
>4. 업종 관련
> - biz : '한국 산업 표준
### 3. EDA
  


### 4. 카드사별 특징 분석 및 서비스 제안 
