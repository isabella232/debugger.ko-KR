---
description: 디버거는 웹 페이지를 검사하여 Experience Cloud 솔루션 구현 방법과 관련된 문제를 찾는 데 도움을 줍니다.
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Adobe Experience Cloud Debugger 2.0 Chrome 및 Firefox Extension에 대한 기술 문서 - 웹 페이지를 살펴보고 Experience Cloud 솔루션 구현 시 발생하는 문제를 이해합니다.
seo-title: Adobe Experience Cloud Debugger 2.0 Chrome 및 Firefox Extension
title: Adobe Experience Cloud Debugger 2.0 Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: b9147536b8312599dd3144cac31dea9f0f1c3625

---


# Adobe Experience Cloud Debugger 2.0 Extension{#adobe-experience-cloud-debugger-extension}

The [Adobe Experience Cloud Debugger 2.0 extension for Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/adobe-experience-platform-dbg/) examines your web pages and helps you find problems with how your Experience Cloud solutions are implemented.

다음과 같은 워크플로우에서 Adobe Experience Cloud Debugger 2.0 익스텐션과 다른 Adobe 정품 인증 솔루션을 함께 사용하십시오.

1. [Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) 또는 [DTM](https://docs.adobe.com/content/help/en/dtm/using/dtm-home.html)을 사용하여 페이지에서 [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) 솔루션을 활성화하는 코드를 삽입합니다.

1. [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/)를 사용하여 구현을 테스트합니다.
1. Adobe Experience Cloud Debugger 확장 프로그램을 사용하여 감사에서 발견한 문제를 디버깅하거나 구현에 대한 다른 정보를 조사합니다.

위의 단계는 반드시 해당 순서대로 수행되는 것은 아니지만, 일반적인 프로세스입니다.

모든 웹 페이지에서 디버거를 실행할 수 있지만 열려 있는 Chrome 탭 중 하나에 있는 Experience Cloud에 인증되는 경우에는 모든 비공개 데이터를 확장 프로그램에서만 사용할 수 있습니다.

## 사용 사례 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

디버거를 사용하여 Experience Cloud 솔루션의 구현 방법을 이해하는 데 도움이 되는 정보를 수집합니다. 예:

* **Experience Platform Launch:** 페이지에 배포되는 속성, 환경, 빌드를 확인하십시오.
* **Target:** 자격이 되거나 되지 않는 활동 및 그 이유를 확인합니다.