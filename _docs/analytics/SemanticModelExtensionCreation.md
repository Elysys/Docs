---
title: Semantic Model Extension Creation
tags: 
 - Semantic
 - Model
description:
---
![/assets/img/ElysysLoansLogo.png](../../assets/img/ElysysWealthLogo.png)

# Semantic Model Extension Creation

## About this guide

This guide provides clear instructions on how to **create a semantic model extension based on the Position View model.**

**Business Scenario:** the client has custom/ specific calculations that are needed to be built into the model.


| **In Power BI Desktop create a blank report** |  |
| --- | --- |
| In **Get data** menu, select Power BI semantic model | ![](../../assets/img/SemanticModelExtensionCreation/image001.png) |
| Select the semantic model you want to use and click **connect**. In this example we will use **Position View** semantic model | ![](../../assets/img/SemanticModelExtensionCreation/image002.png) |
| In the **model view**, click on **Make changes to this model**. | ![](../../assets/img/SemanticModelExtensionCreation/image003.png) |
| A message will appear -> click on Add local model | ![](../../assets/img/SemanticModelExtensionCreation/image004.png) |
| Press **Submit** | ![](../../assets/img/SemanticModelExtensionCreation/image005.png) |
| Now you can edit the model. You can add new measures, new tables, rename columns, etc. |  |
| In this example we will add a new table and create a new measure. Click on New table | ![](../../assets/img/SemanticModelExtensionCreation/image006.png) |
| A table will appear. We rename the table to Demo Table | |
| Right click on the Demo Table and add a new measure – Demo Measure | ![](../../assets/img/SemanticModelExtensionCreation/image007.png) |
| In report view, you can see the new table and the new measure | ![](../../assets/img/SemanticModelExtensionCreation/image008.png) ![](../../assets/img/SemanticModelExtensionCreation/image009.png) |
| Save and publish the new semantic model | ![](../../assets/img/SemanticModelExtensionCreation/image010.png) ![](../../assets/img/SemanticModelExtensionCreation/image011.png) |
| In the workspace you can see now 2 semantic models: Position View and Position View Extension | ![](../../assets/img/SemanticModelExtensionCreation/image012.png) |
| You can start using the new semantic model to create reports. | ![](../../assets/img/SemanticModelExtensionCreation/image013.png) |