---
description: Adobe Debugger의 솔루션 탭 사용
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;solutions;solution;information;analytics;target;audience manager;media optimizer;amo;id service
seo-description: Adobe Debugger의 솔루션 탭 사용
seo-title: Adobe Debugger의 솔루션 탭
title: 솔루션 탭
uuid: 5e999ef2-6399-4ab5-a841-3a839d081728
translation-type: ht
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: ht
source-wordcount: '1063'
ht-degree: 100%

---


# 솔루션 탭{#solution-tabs}

솔루션 탭을 클릭하여 특정 Adobe Experience Cloud 솔루션에 대한 결과를 확인합니다.

## Analytics {#section-f71dfcc22bb44c86bec328491606a482}

Analytics 탭은 [Analytics](https://docs.adobe.com/content/help/ko-KR/analytics/landing/home.html) 구현에 대한 정보를 제공합니다.

**히트 수**

기본적으로 동일한 보고서 세트에 대해 수행된 모든 서버 호출이 축소됩니다.

![](assets/analytics-hits.jpg)

**다운로드:** 표시된 모든 보고서 세트에 대한 정보를 Excel 스프레드시트로 다운로드합니다.

**모든 요청 지우기:** Analytics 보기에서 표시된 모든 요청을 제거합니다. 요청을 지운 후에는 새 요청이 있을 경우 표시됩니다.

보고서 세트 ID를 클릭하여 보기를 확장합니다.

![](assets/analytics-hits-expand.jpg)

이 화면에는 Adobe Experience Platform Debugger가 열려 있거나 요청이 삭제된 이후의 모든 요청이 표시됩니다. 기본 매개 변수는 친숙한 이름에 자동으로 매핑됩니다. 다음 &quot;Analytics 연결&quot; 기능을 사용하여 인증하는 경우(아래 참조) [Prop 및 eVar](https://docs.adobe.com/content/help/ko-KR/analytics/implementation/vars/page-vars/evar.html) 변수를 친숙한 사용자 지정 이름에 매핑할 수 있습니다(예: &quot;prop1&quot;이 &quot;사용자 유형&quot;으로 표시될 수 있음). 요청은 왼쪽에서 오른쪽으로 순서대로 표시됩니다.

**다운로드:** 보고서 세트에 수행된 모든 요청을 Excel 스프레드시트로 저장합니다.

**요청 지우기:** 이 보고서 세트에 대한 모든 요청을 제거합니다. 새 요청은 있을 경우 표시됩니다.

**연결된 계정(기존)**

**[!UICONTROL Link Account]**&#x200B;를 클릭한 다음 요청된 정보를 입력하여 Analytics 계정을 Platform Debugger에 연결합니다.

>[!NOTE]
>
>현재 이 기능은 기존 Analytics 사용자 로그인 자격 증명에 대해서만 지원됩니다.

![](assets/analytics-link-account.jpg)

**후 처리된 히트 검색**

처리 규칙이 실행된 후 Analytics 히트에 대한 값을 보려면 후 처리된 히트 검색 옵션을 활성화합니다. 이 기능을 사용하려면 Adobe Experience Cloud에 로그인해야 합니다.

이 옵션이 활성화화된 경우 디버깅 매개 변수가 Analytics 요청에 추가됩니다. 히트 수는 다른 히트 수와 마찬가지로 계속 처리됩니다. Platform Debugger는 Analytics 디버깅 API를 폴링하여 원래 히트 ID가 있는 모든 히트에 대한 후 처리 규칙 값을 검색합니다. 후 처리된 히트는 배경이 보라색이며 기존 히트 옆에 표시됩니다.

대부분의 Analytics 구현의 경우 몇 분 이내에 후 처리 규칙 정보를 사용할 수 있습니다. A4T(Analytics for Target) 구현은 훨씬 더 오래 걸립니다.

## Target {#section-988873ba5ede4317953193bd7ac5474c}

Target 탭에서 [Target](https://docs.adobe.com/content/help/ko-KR/target/using/target-home.html) 요청이나 [Mbox 추적](https://docs.adobe.com/content/help/ko-KR/target/using/activities/troubleshoot-activities/content-trouble.html) 응답 세부 사항을 볼 수 있습니다.

**[!UICONTROL Requests]**&#x200B;를 클릭한 다음 환경을 확장하여 타겟에 대한 정보를 봅니다.

![](assets/target-requests.jpg)

**[!UICONTROL Clear All Requests]**&#x200B;를 클릭하여 현재 표시된 요청을 제거합니다. 더 많은 요청이 있을 때마다 표시됩니다.

Target 필터를 사용하여 [Target 디버깅 목적을 위해 MBox 추적을 활성화](https://docs.adobe.com/content/help/ko-KR/target/using/activities/troubleshoot-activities/content-trouble.html)할 수도 있습니다.

Mbox 추적을 활성화하려면 Experience Cloud에 인증된 Chrome 탭이 열려 있어야 합니다. 활성화되어 있으면 Adobe Id 사용자 이름이 표시됩니다. 사용자 이름을 확장하여 액세스 권한이 있는 Experience Cloud 조직과 연결된 Target 클라이언트 코드를 표시합니다. Mbox 추적을 활성화할 클라이언트 코드를 클릭하고 녹색 확인 표시가 나타나는지 확인합니다. 이제 Mbox 추적 정보가 있는 모든 Target 요청이 클라이언트 코드로 그룹화되어 표시됩니다. Mbox 추적 정보를 탐색하려면 요청을 확장하여 탭을 확인합니다.

* [활동](https://docs.adobe.com/content/help/ko-KR/target/using/activities/activities.html) 활동 탭에는 활동에 대한 자격이 있는지 여부에 관계없이 Target 요청 이름과 연관된 모든 활동이 표시됩니다. 일치된 활동은 자격이 있고 오퍼가 응답으로 전달된 활동입니다. 활동 이름을 확장하여 현재 활동에 있는 경험과 활동에 대해 자격이 있는 대상 및 타겟팅 조건을 확인할 수 있습니다. 평가 활동은 자격이 있는지 여부에 관계없이 평가된 모든 활동입니다. 평가 활동이지만 &quot;일치된&quot; 활동이 아닌 활동에 대해 자격이 없는 이유를 해결하려면 활동 이름을 확장하고 &quot;일치하지 않는 대상&quot; 섹션을 검토합니다.

* 요청

   [Mbox 추적](https://docs.adobe.com/content/help/ko-KR/target/using/activities/troubleshoot-activities/content-trouble.html)의 요청 탭은 기본 요청 탭과 유사합니다. 요청 헤더 외에 Target 요청에서 전달한 모든 매개 변수를 볼 수 있습니다.
* 프로필

   프로필 스냅샷 섹션을 확장하여 Target 프로필 데이터베이스에서 방문자로 저장된 [프로필 정보](https://docs.adobe.com/content/help/ko-KR/target/using/audiences/visitor-profiles/variables-profiles-parameters-methods.html)를 봅니다. 모든 Mbox 내 및 스크립트 프로필은 물론 일부 시스템 프로필이 여기에 표시됩니다. 상태 열에는 이 요청의 범위 내에서 변경된 프로필과 요청이 프로필 시스템에 입력되기 전후의 값이 표시됩니다.
* Audience Manager

   Audience Manager 탭의 &quot;segmentIds&quot; 및 &quot;cachedSegmentIds&quot; 섹션에는 Experience Cloud에서 Target으로 공유되고 자격이 있는 [대상](https://docs.adobe.com/content/help/ko-KR/target/using/audiences/target.html)의 ID가 표시됩니다. 이러한 대상은 Audience Manager, Analytics 또는 People Core Service의 Audience Builder에서 만든 대상일 수 있습니다. 이러한 ID는 Audience Manager 사용자 인터페이스에서 조회하여 대상 이름을 찾을 수 있습니다.

다음 비디오는 일반적인 Target 기능을 보여 줍니다.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=kor)

다음 비디오는 Mbox 추적을 보여 줍니다.

>[!VIDEO](https://video.tv.adobe.com/v/23113t2/?captions=kor)

## Audience Manager {#section-1d4484f8b46f457f859ba88039a9a585}

[Audience Manager](https://docs.adobe.com/content/help/ko-KR/audience-manager/user-guide/aam-home.html) 탭을 사용하여 [이벤트](https://docs.adobe.com/content/help/ko-KR/audience-manager/user-guide/api-and-sdk-code/dcs/dcs-event-calls/dcs-event-calls.html) 세부 사항을 볼 수 있습니다. 조직을 클릭하여 확장하고 정보를 표시합니다.

![](assets/audience-manager.jpg)

**[!UICONTROL Clear All Events]**&#x200B;를 클릭하여 표시된 정보를 재설정합니다. 새 이벤트가 발생할 때 표시됩니다.

**ID 동기화**

ID 동기화는 인바운드 비동기 데이터 전송 프로세스의 첫 번째 단계입니다. 이 단계에서 Audience Manager와 공급업체는 해당 사이트 방문자의 ID를 비교하고 일치시킵니다.

![](assets/aam-idsync.jpg)

자세한 내용은 Audience Manager 제품 설명서의 [인바운드 데이터 전송에 대한 ID 동기화](https://docs.adobe.com/content/help/ko-KR/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/id-sync-http.html)를 참조하십시오.

## Advertising Cloud {#section-ee80a9c509f2462c89c1e5bd8d05d7c8}

Advertising Cloud 탭을 사용하여 Advertising Cloud 요청을 봅니다.

**[!UICONTROL Requests]**&#x200B;를 클릭한 다음 환경을 확장하여 Advertising Cloud에 대한 정보를 봅니다.

**[!UICONTROL Clear All Requests]**&#x200B;를 클릭하여 현재 표시된 요청을 제거합니다. 더 많은 요청이 있을 때마다 표시됩니다.

## Experience Cloud ID 서비스 {#section-a96c32f8e63a4991abb296f6e8ea01cf}

Experience Cloud ID 서비스 탭을 사용하여 [Experience Cloud ID 서비스](https://docs.adobe.com/content/help/ko-KR/id-service/using/home.html) 요청을 봅니다.

**[!UICONTROL Requests]**&#x200B;를 클릭한 다음 환경을 확장하여 Experience Cloud ID 서비스에 대한 정보를 봅니다.

**[!UICONTROL Clear All Requests]**&#x200B;를 클릭하여 현재 표시된 요청을 제거합니다. 더 많은 요청이 있을 때마다 표시됩니다.
