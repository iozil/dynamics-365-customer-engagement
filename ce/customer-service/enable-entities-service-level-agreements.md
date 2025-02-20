---
title: "Enable entities for service level agreements (Dynamics 365 Customer Service) | MicrosoftDocs"
description: "Learn how to enable entities for service level agreements in Dynamics 365 Customer Service."
ms.date: 06/16/2022
ms.topic: article
author: Soumyasd27
ms.author: sdas
manager: shujoshi
search.audienceType: 
  - admin
  - customizer
  - enduser
search.app: 
  - D365CE
  - D365CS
ms.custom: 
  - dyn365-customerservice
---

# Enable entities for service level agreements

Service level agreements are not just important in the customer service space, but also for sales and marketing to ensure efficient handling of leads from start to finish.  
  
> [!IMPORTANT]
> Only enhanced SLAs can be created for other entities. A standard SLA can be created only for the Case entity.

## Entities (record types) that support SLAs

With Customer Service, you can create enhanced SLAs for entities that are enabled for SLA. A system administrator or customizer can enable SLAs for the following entities:  

- Account  

- Contact  

- Order  

- Invoice  

- Quote  

- Opportunity  

- Lead

- Activity entities such as Email, PhoneCall, and Appointment&mdash;but not RecurringAppointment or its instances  

  > [!NOTE]
  >  SLAs can also be enabled for custom entities and custom activities.
  
### To enable an entity for SLA
  
1. [!INCLUDE[proc_permissions_system_admin_and_customizer](../includes/proc-permissions-system-admin-and-customizer.md)]  
  
    #### Check your security role  
  
   - [!INCLUDE[proc_follow_steps_in_link](../includes/proc-follow-steps-in-link.md)]  
  
2. [!INCLUDE[proc_settings_customization](../includes/proc-settings-customization.md)]  
  
3. Select **Customize the System**.  
  
4. In the solution explorer, in the left nav pane, select the entity that you want to enable for SLA.  
  
5. Under **Communication & Collaboration**, select the **Enable for SLA** check box.  
  
6. Select **Save**.  
  
7. Select **Publish**.  
  
> [!NOTE]
>
> - A maximum of seven entities can have active SLAs for your organization.
> - A maximum of five SLA KPIs are allowed per entity for your organization.  
  
### See also

 [Configure service level agreements](../customer-service/define-service-level-agreements.md)


[!INCLUDE[footer-include](../includes/footer-banner.md)]
