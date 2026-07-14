<!-- codex-summary:start -->
# exc

Exercise Scenario

## 구현 기능 요약

### App 화면

- 역할: 화면 정보 표시와 사용자 입력 처리

### Detail 화면

- 역할: 화면 정보 표시와 사용자 입력 처리

### Info 화면

- 역할: 업무 명령 실행
- 주요 항목: Ok
- 사용자 동작: 팝업 또는 화면 닫기 [onCloseDialog]

### Not Found 화면

- 역할: 화면 정보 표시와 사용자 입력 처리

### Flight Customers 화면

- 역할: 목록 조회 및 항목 선택, 조건 입력 및 값 선택, 상세 정보 표시·편집, 업무 명령 실행
- 주요 항목: New Customer, Bookings, Create Customer, General Data, Form, Customer Name, Discount, Address Data
- 사용자 동작: 입력 내용 저장/확정 [onSave], 값 변경 반영 [onCustomerChange], Filter Customers [onFilterCustomers]
- 처리 내용: 검색 조건으로 목록을 필터링; 팝업/다이얼로그를 열어 추가 입력이나 확인을 처리
- 주요 기능: 입력 내용 저장/확정, 팝업 또는 화면 닫기, 값 변경 반영, Filter Customers

## 실행 방법

```bash
npm install
npm start
```

<!-- codex-summary:end -->

## 기존 문서

## Application Details
|               |
| ------------- |
|**Generation Date and Time**<br>Mon Jul 18 2022 13:49:15 GMT+0000 (Coordinated Universal Time)|
|**App Generator**<br>@sap/generator-fiori-freestyle|
|**App Generator Version**<br>1.6.6|
|**Generation Platform**<br>SAP Business Application Studio|
|**Floorplan Used**<br>simple|
|**Service Type**<br>SAP System (ABAP On Premise)|
|**Service URL**<br>http://s4d.virtual:443/sap/opu/odata4/sap/ux_ui_customer_o4/srvd/sap/ux_ui_customer/0001/
|**Module Name**<br>exc|
|**Application Title**<br>Exercise Application|
|**Namespace**<br>sap.training|
|**UI5 Theme**<br>sap_fiori_3|
|**UI5 Version**<br>1.96.10|
|**Enable Code Assist Libraries**<br>False|
|**Add Eslint configuration**<br>False|

## exc

Exercise Scenario

### Starting the generated app

-   This app has been generated using the SAP Fiori tools - App Generator, as part of the SAP Fiori tools suite.  In order to launch the generated app, simply run the following from the generated app root folder:

```
    npm start
```

- It is also possible to run the application using mock data that reflects the OData Service URL supplied during application generation.  In order to run the application with Mock Data, run the following from the generated app root folder:

```
    npm run start-mock
```

#### Pre-requisites:

1. Active NodeJS LTS (Long Term Support) version and associated supported NPM version.  (See https://nodejs.org)
