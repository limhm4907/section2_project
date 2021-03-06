# section2_project (통신 회사 고객 이탈 예측)

<br>

**- 프로젝트 개요**

가상의 통신 회사 데이터팀이라고 가정합니다. 신규 고객을 확보하는 것이 기존 고객을 유지하는 것보다 상대적으로 쉽지 않고 높은 비용이 듭니다. 따라서 기존 고객의 이탈을 미리 예측하여 조치를 취함으로써 기존 고객의 가입을 최대한 유지시키고자 합니다. 기존 고객이 가입을 유지할지 혹은 이탈할지 예측하기 위해 고객 정보 데이터를 기반으로 머신러닝 분류 모델을 구축하고자 합니다.

<br>

**- 데이터 설명**

*   `customer ID` : 고객 번호
*   `gender` : 성별 (Male, Female)
*   `SeniorCitizen` : 나이가 65세보다 큰지 여부 (Yes - 1, No - 0)
*   `Partner` : 파트너가 있는지 여부 (Yes, No)
*   `Dependents` : 부양가족이 있는지 여부 (Yes, No) / children, parents, grandparents, etc.
*   `tenure` : 고객이 회사에 머무른 월 수
*   `PhoneService` : 고객의 전화서비스 가입 여부 (Yes, No)
*   `MultipleLines` : 고객의 다회선 사용 여부 (Yes, No, No phone service)
*   `InternetService` : 고객의 인터넷서비스 가입 여부 (DSL, Fiber optic, No)
*   `OnlineSecurity` : 고객의 온라인보안서비스 가입 여부 (Yes, No, No internet service)
*   `OnlineBackup` : 고객의 온라인백업서비스 가입 여부 (Yes, No, No internet service)
*   `DeviceProtection` : 고객의 장치보호플랜 가입 여부 (Yes, No, No internet service)
*   `TechSupport` : 고객의 기술지원플랜 가입 여부 (Yes, No, No internet service)
*   `StreamingTV` : 고객의 TV 스트리밍 이용 여부 (Yes, No, No internet service)
*   `StreamingMovies` : 고객의 Movie 스트리밍 이용 여부 (Yes, No, No internet service)
*   `Contract` : 고객의 계약 유형? 기간? (Month-to-month, One year, Two year)
*   `PaperlessBilling` : 고객의 종이없는 청구서 선택 여부 (Yes, No)
*   `PaymentMethod` : 고객의 결제방법 (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
*   `MonthlyCharges` : 고객의 월별 청구금액
*   `TotalCharges` : 고객의 총 청구금액
*   `Churn` : 고객의 이탈 여부 (Yes, No)
