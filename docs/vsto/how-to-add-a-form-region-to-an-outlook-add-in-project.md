---
title: "How to: Add a Form Region to an Outlook Add-in Project | Microsoft Docs"
ms.custom: ""
ms.date: "02/02/2017"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "office-development"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "VSTO.NewFormRegionWizard.Page1"
  - "VSTO.NewFormRegionWizard.Page3"
  - "VSTO.NewFormRegionWizard.Page2"
  - "VSTO.NewFormRegionWizard.Page0"
dev_langs: 
  - "VB"
  - "CSharp"
helpviewer_keywords: 
  - "form regions [Office development in Visual Studio], adding"
ms.assetid: 49fa3d1e-1b8a-48be-95fb-35c59c4711f6
caps.latest.revision: 38
author: "kempb"
ms.author: "kempb"
manager: "ghogen"
---
# How to: Add a Form Region to an Outlook Add-in Project
  Create a form region to extend a standard or custom Microsoft Office Outlook form by using the **New Outlook Form Region** wizard. You can create a new form region and design the user interface in Visual Studio, or you can import a form region that was designed in Outlook and add Visual Basic or C# code.  
  
 If you have an Outlook form region that you used in another Outlook project, you can reuse it in your current Outlook VSTO Add-in project by using the **Add Existing Item** dialog box. For more information, see [Creating Outlook Form Regions](../vsto/creating-outlook-form-regions.md).  
  
 [!INCLUDE[appliesto_olkallapp](../vsto/includes/appliesto-olkallapp-md.md)]  
  
### To add a new form region to an Outlook project  
  
1.  Open or create an Outlook VSTO Add-in project in [!INCLUDE[vsprvs](../sharepoint/includes/vsprvs-md.md)]. For more information, see [How to: Create Office Projects in Visual Studio](../vsto/how-to-create-office-projects-in-visual-studio.md).  
  
2.  In **Solution Explorer**, select the Outlook VSTO Add-in project node.  
  
3.  On the **Project** menu, click **Add New Item**.  
  
4.  In the **Add New Item** dialog box, select **Outlook Form Region**.  
  
5.  Type a name for the form region in the **Name** box, and then click **Add**.  
  
     The **NewOutlook Form Region** wizard starts.  
  
6.  On the **Select how you want to create the form region** page, select whether you want to design the form region by dragging managed controls onto a visual designer or import a form region that was designed in Outlook.  
  
    > [!NOTE]  
    >  If you choose to import a form region that was designed in Outlook, then you must specify the location of an Outlook Form Storage (.ofs) file. You cannot add managed controls to a form region that you design in Outlook; you can only add code behind the existing UI. For more information, see [Creating Outlook Form Regions](../vsto/creating-outlook-form-regions.md).  
  
7.  On the **Select the type of form region you want to create** page, review the form region types and select one, and then click **Next**. For more information about form region types, see [Creating Outlook Form Regions](../vsto/creating-outlook-form-regions.md).  
  
8.  On the **Supply descriptive text and select your display preferences** page, in the **Name** box, type a name for the form region. For the replacement and replace-all form region types, the **Title** and **Description** boxes are also available.  
  
     For information about where the name, title, and description appear in Outlook when you deploy the form region, see [Creating Outlook Form Regions](../vsto/creating-outlook-form-regions.md).  
  
9. Select one or more display modes in which you want the form region to appear.  
  
     All form region types can appear in Inspectors, in compose mode (for creating items) and in read mode (for viewing items). Adjoining, replacement, and replace-all form region types can also appear in the Reading Pane.  
  
10. Click **Next**.  
  
11. On the **Identify the message classes that will display this form region** page, select standard Outlook message classes or type the names of one or more custom message classes, and then click **Finish**. For more information, see [Associating a Form Region with an Outlook Message Class](../vsto/associating-a-form-region-with-an-outlook-message-class.md).  
  
## See Also  
 [Accessing a Form Region at Run Time](../vsto/accessing-a-form-region-at-run-time.md)   
 [Outlook Solutions](../vsto/outlook-solutions.md)   
 [Creating Outlook Form Regions](../vsto/creating-outlook-form-regions.md)   
 [Guidelines for Creating Outlook Form Regions](../vsto/guidelines-for-creating-outlook-form-regions.md)   
 [Walkthrough: Designing an Outlook Form Region](../vsto/walkthrough-designing-an-outlook-form-region.md)   
 [Walkthrough: Importing a Form Region That Is Designed in Outlook](../vsto/walkthrough-importing-a-form-region-that-is-designed-in-outlook.md)   
 [Custom Actions in Outlook Form Regions](../vsto/custom-actions-in-outlook-form-regions.md)  
  
  