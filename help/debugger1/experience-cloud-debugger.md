---
description: 디버거는 웹 페이지를 검사하여 Experience Cloud 솔루션 구현 방법과 관련된 문제를 찾는 데 도움을 줍니다.
keywords: 디버거;experience cloud debugger 확장 프로그램;chrome;확장 프로그램
seo-description: Technical documentation for the Adobe Experience Cloud Debugger Chrome Extension - examine your web pages and understand problems with your Experience Cloud solution mplementations
seo-title: Adobe Experience Cloud Debugger Chrome Extension
title: Adobe Experience Cloud Debugger 확장 프로그램
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
exl-id: 02d88172-3fb1-4111-a80d-e9d46df9ea1e
source-git-commit: 3b07bfe5764b46a2510b577df8978a35a753ab7b
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 84%

---

# Adobe Experience Cloud Debugger 확장 프로그램{#adobe-experience-cloud-debugger-extension}

>[!IMPORTANT]
>
>현재 사용할 수 있는 새로운 버전의 디버거가 있습니다. 최신 기능에 대한 자세한 내용은 [Adobe Experience Platform Debugger 설명서](../debugger2/experience-cloud-debugger.md).

[Chrome용 Adobe Experience Cloud Debugger 확장 프로그램](https://chrome.google.com/webstore/detail/adobe-experience-platform/bfnnokhpnncpkdmbokanobigaccjkpob)은 웹 페이지를 검사하고 Experience Cloud 솔루션이 구현되는 방식과 관련된 문제를 찾는 데 도움이 됩니다.

다음과 같은 작업 과정에 대한 다른 Adobe 활성화 솔루션으로 Adobe Experience Cloud Debugger 확장 프로그램을 사용합니다.

1. 사용 [태그](https://experienceleague.adobe.com/docs/launch/using/home.html?lang=ko-KR) 를 활성화한 코드를 삽입하려면 [Adobe Experience Cloud](https://experienceleague.adobe.com/docs/home.html) 솔루션 을 참조하십시오.
1. Adobe Experience Platform Auditor를 사용하여 구현을 테스트합니다.
1. Adobe Experience Cloud Debugger 확장 프로그램을 사용하여 감사에서 발견한 문제를 디버깅하거나 구현에 대한 다른 정보를 조사합니다.

위의 단계는 반드시 해당 순서대로 수행되는 것은 아니지만, 일반적인 프로세스입니다.

모든 웹 페이지에서 디버거를 실행할 수 있지만 열려 있는 Chrome 탭 중 하나에 있는 Experience Cloud에 인증되는 경우에는 모든 비공개 데이터를 확장 프로그램에서만 사용할 수 있습니다.

## 사용 사례 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

디버거를 사용하여 Experience Cloud 솔루션의 구현 방법을 이해하는 데 도움이 되는 정보를 수집합니다. 예:

* **Platform Launch:** 페이지에 배포되는 속성, 환경, 빌드를 확인합니다.
* **Target:** 자격이 되거나 되지 않는 활동 및 그 이유를 확인합니다.
