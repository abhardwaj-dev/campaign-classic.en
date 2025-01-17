---
product: campaign
title: Use an external recipient table
description: Use an external recipient table
feature: Audiences
exl-id: b6aabc68-707d-4c6c-b008-277609166c6c
---
# Use an external recipient table{#using-an-external-recipient-table}

![](../../assets/common.svg)

If the delivery table is an external table, you will need to make additional configurations. The **[!UICONTROL nms:seedmember]** schema must be extended. A tab is added to the seed addresses to define the adequate fields, as shown below:

![](assets/s_ncs_user_seedlist_new_tab.png)

In this case, to add seed addresses to the delivery, enter the adequate fields directly in the matching tab, or import the address templates:

![](assets/s_ncs_user_seedlist_add_new_tab.png)

The **nms:seedMember** schema extension is [this section](../../configuration/using/seed-addresses.md).
