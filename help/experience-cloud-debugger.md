---
description: Debugger는 웹 페이지를 검사하여 Experience Cloud 솔루션 구현 방법과 관련된 문제를 찾는 데 도움이 됩니다
keywords: 디버거;experience cloud debugger extension;chrome;extension
seo-description: Adobe Experience Cloud Debugger Chrome Extension에 대한 기술 설명서 - 웹 페이지를 살펴보고 Experience Cloud 솔루션 구현의 문제를 파악합니다.
seo-title: Adobe Experience Cloud Debugger Chrome Extension
title: Adobe Experience Cloud 디버거 확장
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: f89c8300a24a7bef204e3dc64da1a479597b5ce5

---


# Adobe Experience Cloud 디버거 확장{#adobe-experience-cloud-debugger-extension}

The [Adobe Experience Cloud Debugger extension for Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) examines your web pages and helps you find problems with how your Experience Cloud solutions are implemented.

다음과 같은 워크플로우에서 Adobe Experience Cloud Debugger 익스텐션을 다른 Adobe 활성화 솔루션과 함께 사용하십시오.

1. Launch [또는](https://docs.adobelaunch.com) DTM [을 사용하여](https://experiencecloud.adobe.com/resources/help/en_US/dtm/) 페이지에서 Adobe Experience Cloud [솔루션을 활성화하는](https://marketing.adobe.com/resources/help/en_US/mcloud/) 코드를 삽입합니다.

1. Adobe [Cloud Platform Auditor를](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) 사용하여 구현을 테스트합니다.
1. Adobe Experience Cloud Debugger 확장 프로그램을 사용하여 감사에서 발견한 문제를 디버깅하거나 구현에 대한 다른 정보를 조사합니다.

위의 단계는 해당 순서대로 반드시 수행되는 것은 아니지만 일반적인 프로세스입니다.

모든 웹 페이지에서 디버거를 실행할 수 있지만 공개 크롬 탭 중 하나에서 Experience Cloud에 인증되는 경우에는 모든 비공개 데이터만 확장에서만 사용할 수 있습니다.

## 사용 사례 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

디버거를 사용하여 Experience Cloud 솔루션의 구현 방법을 이해하는 데 도움이 되는 정보를 수집합니다. 예:

* **** Launch, by Adobe:페이지에 배포되는 속성, 환경, 빌드를 확인하십시오.
* **** 타겟:자격 조건을 갖추었는지 여부를 확인하고 자격 조건을 충족하지 못한 활동과 그 이유를 확인합니다.
