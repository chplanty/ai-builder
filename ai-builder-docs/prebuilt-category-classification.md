---
title: Prebuilt category classification model - AI Builder | Microsoft Docs
description: Describes the prebuilt category classification AI Builder model.
author: nijemcevic
ms.service: powerapps
ms.topic: conceptual
ms.custom: 
ms.date: 05/11/2020
ms.author: tatn
ms.reviewer: v-dehaas
---

# Category classification prebuilt model (preview)
<!--Okay to add the disclaimer?-->
[!INCLUDE[cc-beta-prerelease-disclaimer](./includes/cc-beta-prerelease-disclaimer.md)]

The prebuilt category classification model is a ready to use AI model that is configured to classify your text into categories that are useful for a specific business scenario. The first prebuilt category classification AI model is built around customer feedback uses. Check back for additional category classification prebuilt models, or check release plans to see what might be coming.
<!--Edits to the following headings okay? I thought this should match the pattern of the entity extraction page, since they're otherwise structured so similarly. -->
## Use in Power Apps

### Explore category classification

You can see the category classification prebuilt model in action without the need to build a flow by using the "try it out" feature.

1. Sign in to [Power Apps](https://make.powerapps.com).
1. In the left pane, select **AI Builder** > **Build**.
1. Under **Get straight to productivity**, select **Category classification model**.
1. In the **Category classification** window, select **Try it out**. 
1. Select predefined text samples to analyze, or add your own text in the **Add your own here** box to see how the model analyzes your text.

### Use the formula bar

You can integrate your AI Builder category classification model<!--Edit okay (here and in the sister articles)? Not sure why it's plural. --> in Power Apps Studio<!--Via Cloud Style Guide--> by using the formula bar. More information: [Use formulas for text AI models](use-model.md#use-formulas-for-text-ai-models)

## Use in Power Automate

For information about how to use this prebuilt model in Power Automate, see [Use the category classification prebuilt model in Power Automate](prebuilt-category-classification-pwr-automate.md).

## Supported data format and languages

- Documents can't exceed 5,000 characters.
- Supported languages:
  - English
  - Chinese-Simplified
  - French
  - German
  - Portuguese
  - Italian
  - Spanish

## Supported classification categories

### Customer feedback prebuilt model

- Issues
- Compliment
- Customer Service
- Documentation
- Price & Billing
- Staff

### Next step

[Use the category classification prebuilt model in Power Automate](prebuilt-category-classification-pwr-automate.md)

### See also

[Overview of the category classification custom model](text-classification-overview.md)