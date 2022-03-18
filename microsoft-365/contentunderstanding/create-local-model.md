---
title: Create a model on a local SharePoint site with Microsoft SharePoint Syntex
ms.author: chucked
author: chuckedmonson
manager: pamgreen
ms.reviewer: ssquires
audience: admin
ms.topic: article
ms.prod: microsoft-365-enterprise
search.appverid: 
ms.collection: 
    - enabler-strategic
    - m365initiative-syntex
ms.localizationpriority:  medium
description: Learn how to create a local model on a local SharePoint site with SharePoint Syntex.
---

# Create a model on a local SharePoint site with Microsoft SharePoint Syntex

SharePoint Syntex now provides an option to create and train models locally on your own SharePoint site. These models can be used only on the site where they're created. 

By activating document classification and extraction on your SharePoint site, SharePoint Syntex lets you classify files in document libraries, extract information from new files, and automate activities based on extracted information.

When you activate local model creation, the following lists and libraries will be added to your site:

- Models document library
- Training files document library
- Explanation templates list
- Model usage list

This feature is available only for creating [document understanding models](apply-a-model.md) and [prebuilt models](prebuilt-models.md). 

## Create a model on a local site

1. From a SharePoint document library, select the files you want to analyze, and then select **Classify and extract**.

    ![Screenshot of a SharePoint document library with the Classify and extract option highlighted.](../media/content-understanding/local-model-classify-and-extract-option.png) 

2. The first time you use this feature, you are activating SharePoint Syntex on your site. You'll see the following message.

    ![Screenshot of the Activate document classification and extraction infomation page.](../media/content-understanding/local-model-first-run-activate-message.png) 

3. Select **Activate** to continue. You'll see the following message.

    ![Screenshot of the Document classification and extraction activated message with the option to Create a model.](../media/content-understanding/local-model-activated-message.png) 

4. Select **Create a model**.

5. On the **Create a model** panel, type the name of the model, select the model type, and then select **Create**.

    ![Screenshot of the Create a model panel.](../media/content-understanding/local-model-create-a-model.png) 

6. Proceed to [train your document understanding model](apply-a-model.md) or to [configure your prebuilt model](prebuilt-models.md) using the files that you selected.

7. When done, the **Add to library** panel opens.

    ![Screenshot of the Add to library panel showing the site and libraries applied.](../media/content-understanding/local-model-add-to-library-panel.png) 

8. On the **Add to library** panel, you'll see the name of your SharePoint site and the document library that the model will be applied to. If you want to apply the model to a different library, select **Back to libraries**, and choose the library you want to use. Then select **Add**.

9. On the model home page, in the **Where the model is applied on this site** section, you can see the libraries that have the model applied. To apply the model to other libraries on the site, select **Apply model**. 

    ![Screenshot of the model home page showing the Where the model is applied on the site section.](../media/content-understanding/local-model-home-page.png) 
