---
description: Experience Platform Debugger는 웹 페이지를 검사하여 Experience Cloud 솔루션 구현 방법과 관련된 문제를 찾는 데 도움을 줍니다.
keywords: debugger;experience Platform Debugger extension;chrome;extension
seo-description: Adobe Experience Platform Debugger Chrome 및 Firefox 확장 프로그램에 대한 기술 문서 - 웹 페이지를 살펴보고 Experience Cloud 솔루션 구현과 관련된 문제를 파악합니다.
seo-title: Adobe Experience Platform Debugger Chrome 및 Firefox 확장 프로그램
title: Adobe Experience Platform Debugger 확장 프로그램
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 62%

---


# (베타) Adobe Experience Platform Debugger {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger는 현재 베타 버전입니다. 설명서 및 기능은 변경될 수 있습니다.

[Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) 및 [Firefox](https://addons.mozilla.org/ko-KR/firefox/addon/adobe-experience-platform-dbg/) 용 Adobe Experience Platform 디버거는 웹 페이지를 검사하여 Experience Cloud 솔루션이 구현되는 방식에 문제를 찾도록 도와줍니다.

다음과 같은 워크플로우에서 플랫폼 디버거를 다른 Adobe 활성화 솔루션과 함께 사용하십시오.

1. [Launch](https://docs.adobe.com/content/help/ko-KR/launch/using/overview.html) 또는 [DTM](https://docs.adobe.com/content/help/ko-KR/dtm/using/dtm-home.html)을 사용하여 페이지에서 [Adobe Experience Cloud](https://docs.adobe.com/content/help/ko-KR/core-services/interface/experience-cloud.html) 솔루션을 활성화하는 코드를 삽입합니다.

1. Use [Adobe Experience Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) to test your implementations.
1. Adobe Experience Platform Debugger를 사용하여 감사에서 발견한 문제를 디버깅하거나 구현에 대한 다른 정보를 검사합니다.

위의 단계는 반드시 해당 순서대로 수행되는 것은 아니지만, 일반적인 프로세스입니다.

모든 웹 페이지에서 Platform Debugger를 실행할 수 있지만 모든 비공개 데이터는 열린 Chrome 탭 중 하나에서 Experience Cloud에 인증된 경우에만 확장 기능에서만 사용할 수 있습니다.

## 사용 사례 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

플랫폼 디버거를 사용하여 Experience Cloud 솔루션의 구현 방법을 이해하는 데 도움이 되는 정보를 수집합니다. 예:

* **Adobe Experience Platform Launch:** 페이지에 배포되는 속성, 환경, 빌드를 확인합니다.
* **Target:** 자격이 되거나 되지 않는 활동 및 그 이유를 확인합니다.

## 비디오 자습서

>[!VIDEO](https://video.tv.adobe.com/v/32156?quality=12&learn=on)