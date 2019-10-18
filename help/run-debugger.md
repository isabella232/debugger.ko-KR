---
description: 'null'
keywords: 디버거;experience cloud debugger extension;chrome;extension;summary;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: 'null'
seo-title: 요약 화면
title: 요약 화면
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 요약 화면{#summary-screen}

Experience Cloud Debugger를 실행하려면 확장 막대에서 확장 아이콘 을 클릭한 다음 Chrome에서 검사할 페이지를 엽니다.

![](assets/start-icon.jpg)

Adobe Experience Cloud 디버거 요약 화면이 나타납니다.

![](assets/summary.jpg)

이 화면에는 페이지의 축소판뿐만 아니라 페이지의 URL 및 제목이 표시됩니다. 또한 각 Adobe Experience Cloud 솔루션에 대한 정보도 표시됩니다. 표시되는 정보는 솔루션마다 다르지만, 일반적으로 솔루션 라이브러리 및 버전(예: "AppMeasurement v2.9")과 계정 식별자(예: Analytics 보고서 세트 ID, Target 클라이언트 코드, Audience Manager 파트너 ID 등) 등의 정보가 포함됩니다

창 위쪽에 있는 탭 옆의 파란색 숫자는 수행된 서버 호출 수를 보여줍니다. 각 탭 내에서 모든 요청 **[!UICONTROL 지우기를 클릭하여 이]** 값을 0으로 재설정할 수 있습니다.

예를 들어 다음 이미지는 Adobe Target에 대한 정보를 보여줍니다. 인증 없이 아래에 설명된 활동 세부 정보를 표시하려면 코드 또는 태그 관리자에서 디버깅 이벤트 리스너를 구현하고 Target UI에서 필요한 [응답 토큰을](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) 켜야 합니다.

![](assets/summary-target2.jpg)

## 감사자에서 감사 실행 {#section-82bc57440406461ebf27a16855b71655}

Adobe Auditor를 사용하여 페이지에서 일련의 감사를 실행할 수 있습니다. Auditor를 실행하려면 상단 **[!UICONTROL 메뉴에서 Auditor]** 를 클릭한 다음 지금 **[!UICONTROL 감사 페이지를 클릭합니다]**. Adobe Auditor를 열려면 지금 **[!UICONTROL 다중 페이지 감사 실행을 클릭합니다]**.

## 디버거에 표시된 정보 {#section-88a95ba53dca43d9b96a585e75e5f5cf}

디버거에는 각 솔루션에 대한 다음 정보가 표시됩니다.

**페이지 정보**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>페이지 스크린샷 </p> </td> 
   <td colname="col2"> <p>페이지의 축소판 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>페이지의 URL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Title </p> </td> 
   <td colname="col2"> <p>&lt;TITLE&gt; <span class="codeph"> 태그에 지정된</span> 이름 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>보고서 세트 </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external">보고서 세트</a>는 선택한 웹 사이트, 웹 사이트 집합 또는 웹 페이지의 하위 집합에 대한 전체적이고 독립적인 보고를 정의합니다 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>버전 </p> </td> 
   <td colname="col2"> <p>페이지에 <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> 대해</a> 정의된 AppMeasurement 버전 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>방문자 버전 </p> </td> 
   <td colname="col2"> <p>방문자 ID <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> 라이브러리의</a> 버전. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>페이지 이름 </p> </td> 
   <td colname="col2"> <p>Analytics <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> 로</a> 보내진 pageName 변수는 사이트에 대한 사용자 친화적인 이름을 포함합니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>모듈 </p> </td> 
   <td colname="col2"> <p>Adobe Analytics에서 로드한 모듈 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>파트너 </p> </td> 
   <td colname="col2"> <p>DIL 인스턴스의 <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> 파트너 이름</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>버전 </p> </td> 
   <td colname="col2"> <p>DIL<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"> 인스턴스의 버전 번호</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>DIL <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> 인스턴스와</a> 연결된 고유 사용자 ID </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>이름 </p> </td> 
   <td colname="col2"> <p>Adobe Launch <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> 속성의 이름</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>버전 </p> </td> 
   <td colname="col2"> <p>터빈 <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> 버전</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>빌드 날짜 </p> </td> 
   <td colname="col2"> <p>시작 <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> 라이브러리</a> 빌드 날짜 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>환경 </p> </td> 
   <td colname="col2"> <p>Launch 라이브러리에서 사용하는 <a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"> 환경</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>스크립트 디렉토리 </p> </td> 
   <td colname="col2"> <p>론치 스크립트가 저장되는 디렉토리 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>라이브러리 이름 </p> </td> 
   <td colname="col2"> <p>Adobe DTM 라이브러리의<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> 이름</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>버전 </p> </td> 
   <td colname="col2"> <p>터빈 버전 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>빌드 날짜 </p> </td> 
   <td colname="col2"> <p>시작 <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> 라이브러리</a> 빌드 날짜 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>환경 </p> </td> 
   <td colname="col2"> <p>DTM 라이브러리에서 사용하는 환경 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>스크립트 디렉토리 </p> </td> 
   <td colname="col2"> <p>DTM 스크립트가 저장되는 디렉토리 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID 서비스**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud 조직 ID </p> </td> 
   <td colname="col2"> <p>Your <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> Organization ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>버전 </p> </td> 
   <td colname="col2"> <p>방문자 ID<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> 라이브러리</a> 버전 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>클라이언트 코드 </p> </td> 
   <td colname="col2"> <p>Your Target <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Client Code </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>버전 </p> </td> 
   <td colname="col2"> <p>현재 <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> 또는 mbox.js 버전 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>글로벌 Mbox 이름 </p> </td> 
   <td colname="col2"> <p>글로벌<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> mbox</a> 는 Target 구현의 각 웹 페이지 맨 위에서 수행된 단일 서버 호출을 나타냅니다 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mbox 이름 </p> </td> 
   <td colname="col2"> <p>페이지의 <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> 위치</a> 주위의 mbox 이름입니다. 코드 또는 태그 관리자에서 디버깅 이벤트 리스너를 구현하고 Target UI에서 필요한 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 응답 토큰을</a> 켜는 경우에만 인증 없이 사용할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>활동 이름 </p> </td> 
   <td colname="col2"> <p>타겟 <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> 캠페인 또는 활동의</a>이름입니다. 코드 또는 태그 관리자에서 디버깅 이벤트 리스너를 구현하고 Target UI에서 필요한 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 응답 토큰을</a> 켜는 경우에만 인증 없이 사용할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>활동 ID </p> </td> 
   <td colname="col2"> <p>Target 활동의 ID입니다. 코드 또는 태그 관리자에서 디버깅 이벤트 리스너를 구현하고 Target UI에서 필요한 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 응답 토큰을</a> 켜는 경우에만 인증 없이 사용할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>레서피 이름 </p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> 경험의</a>이름입니다. 코드 또는 태그 관리자에서 디버깅 이벤트 리스너를 구현하고 Target UI에서 필요한 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 응답 토큰을</a> 켜는 경우에만 인증 없이 사용할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>레서피 ID </p> </td> 
   <td colname="col2"> <p>Target 레서피의 ID입니다. 코드 또는 태그 관리자에서 디버깅 이벤트 리스너를 구현하고 Target UI에서 필요한 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 응답 토큰을</a> 켜는 경우에만 인증 없이 사용할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>오퍼 </p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> 오퍼의</a>이름입니다. 코드 또는 태그 관리자에서 디버깅 이벤트 리스너를 구현하고 Target UI에서 필요한 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 응답 토큰을</a> 켜는 경우에만 인증 없이 사용할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>오퍼 ID </p> </td> 
   <td colname="col2"> <p>Target 오퍼의 ID입니다. 코드 또는 태그 관리자에서 디버깅 이벤트 리스너를 구현하고 Target UI에서 필요한 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 응답 토큰을</a> 켜는 경우에만 인증 없이 사용할 수 있습니다. </p> </td> 
  </tr> 
 </tbody> 
</table>
