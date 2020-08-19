---
description: Experience Cloud Debugger 네트워크 화면
keywords: debugger;experience cloud debugger extension;chrome;extension;network;information
seo-description: Experience Cloud Debugger 네트워크 화면
seo-title: 네트워크 정보
title: 네트워크 정보
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: tm+mt
source-git-commit: 1d81f427e2c1a68a182fae8262d0e2ad32a87223
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 95%

---


# 네트워크{#network}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0은 현재 베타 버전입니다. 설명서 및 기능은 변경될 수 있습니다.

네트워크 정보를 보려면 **[!UICONTROL Network]**&#x200B;를 클릭합니다.

네트워크 화면은 페이지에서 수행된 모든 Adobe Experience Cloud 솔루션 호출을 집계하여 왼쪽에서 오른쪽으로 표시합니다. 표준 매개 변수는 친숙한 이름으로 자동으로 레이블이 지정되며, 동일한 역할에 따라 일반 매개 변수를 그룹화하여 정렬됩니다.

![](assets/network.jpg)

이 화면은 전체 조회수의 키 값 쌍 비교에 유용합니다. Experience Cloud 방문자 ID 또는 추가 데이터 ID와 같이 통합에 사용된 매개 변수가 통합에서 일관되는지 확인할 수 있습니다.

>[!NOTE]
>
>현재 솔루션 호출에서 전달된 모든 매개 변수(예: Analytics 컨텍스트 변수, Target 사용자 지정 매개 변수 또는 Experience Cloud ID 서비스 고객 ID)가 네트워크 화면에 표시되는 것은 아닙니다.

솔루션별로 정보를 변경하려면 왼쪽 탐색 메뉴의 목록에서 보려는 솔루션을 선택합니다. 다음은 Analytics만 표시되도록 필터링하는 예입니다.

![](assets/network-analytics.jpg)

모든 솔루션이 표시되도록 돌아가려면 **[!UICONTROL Network]**&#x200B;를 클릭합니다.

확장된 보기로 전환하려면 네트워크 보기에서 항목을 클릭합니다. 확장된 보기 창에서 표시된 정보를 클립보드에 복사할 수 있습니다.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

목록을 지우려면 **[!UICONTROL Remove Events]**&#x200B;를 클릭합니다.

이 화면의 정보가 포함된 Excel 파일을 다운로드하려면 **[!UICONTROL Download]**&#x200B;를 클릭합니다.