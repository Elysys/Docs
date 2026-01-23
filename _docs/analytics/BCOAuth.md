---
title: Data Dictionary Analytics
tags: 
 - Analytics
description: How to start with the use of this BI solution
---
![/assets/img/ElysysLoansLogo.png](../../assets/img/ElysysWealthLogo.png)

# About this guide

This guide provides clear, step-by-step instructions on how to register an Azure App Registration and configure it for OAuth authentication with Microsoft Dynamics 365 Business Central. It covers creating the app registration, setting the required redirect URI, assigning delegated and/or application API permissions, granting admin consent, and generating a client secret for secure authentication.

|  |  |
| --- | --- |
| **1. Access the Azure Portal** <br> Sign in to the Azure portal with an account that has rights to create App Registrations and manage API permissions (often Application Administrator or Global Administrator, depending on tenant policy). | ![/assets/img/BCOAuth/image01.png](../../assets/img/BCOAuth/image01.png) |
| **2. Open App registrations**<br>In the top search bar, type **App registrations**.<br>Select **App registrations** from the results (this opens the Azure AD / Entra app registration area). | ![/assets/img/BCOAuth/image02.png](../../assets/img/BCOAuth/image02.png) |
| **3. Create a new app registration**<br>Select **New registration** to start creating a new application identity in Azure. | ![/assets/img/BCOAuth/image03.png](../../assets/img/BCOAuth/image03.png) |
| **3.1. Fill registration basics**<br>**Name**: enter a clear name (e.g. BCRESTAPIOAuth).<br>Choose **Single tenant**<br>Click **Register** to create the app. | ![/assets/img/BCOAuth/image04.png](../../assets/img/BCOAuth/image04.png) |
| **3.2. Confirm the app is created**<br>After creation, you will land on the app’s **Overview** page.<br>Capture the key identifiers (you will typically need them later):<br>**Application (client) ID**<br>**Directory (tenant) ID** | ![/assets/img/BCOAuth/image05.png](../../assets/img/BCOAuth/image05.png) |
| **4. Configure authentication settings**<br>In the left menu of the app registration, select **Authentication** (this is where redirect URIs and platform settings live). | ![/assets/img/BCOAuth/image06.png](../../assets/img/BCOAuth/image06.png) |
| **4.1. Add a Redirect URI**<br>Click **Add a Redirect URI** | ![/assets/img/BCOAuth/image07.png](../../assets/img/BCOAuth/image07.png) |
| **4.2. Choose platform type**<br>Select **Web** as the platform type (this matches how Business Central completes the OAuth flow). | ![/assets/img/BCOAuth/image08.png](../../assets/img/BCOAuth/image08.png) |
| **4.3. Enter the redirect URl of the application**<br>https://businesscentral.dynamics.com/OAuthLanding.htm <br> then choose **Configure**. | ![/assets/img/BCOAuth/image09.png](../../assets/img/BCOAuth/image09.png) |
| 5. In the left menu, select **API permissions**. <br>This defines what the app is allowed to access. | ![/assets/img/BCOAuth/image10.png](../../assets/img/BCOAuth/image10.png) |
| 5.1. Choose **Add a permission**. | ![/assets/img/BCOAuth/image11.png](../../assets/img/BCOAuth/image11.png) |
| 5.2. Find **Dynamics 365 Business Central** and click it. | ![/assets/img/BCOAuth/image12.png](../../assets/img/BCOAuth/image12.png) |
| 5.3. You can choose the required permissions according to your situation.<br>For example: Choose **Delegated permissions**. | ![/assets/img/BCOAuth/image13.png](../../assets/img/BCOAuth/image13.png) |
| 5.4. Select the permissions, and then choose **Add permissions**. | ![/assets/img/BCOAuth/image14.png](../../assets/img/BCOAuth/image14.png) |
| 5.5. Choose **Add a permission** again. | ![/assets/img/BCOAuth/image15.png](../../assets/img/BCOAuth/image15.png) |
| 5.6. Choose **Dynamics 365 Business Central**. | ![/assets/img/BCOAuth/image16.png](../../assets/img/BCOAuth/image16.png) |
| 5.7. Choose **Application permissions** this time. | ![/assets/img/BCOAuth/image17.png](../../assets/img/BCOAuth/image17.png) |
| 5.8. Select the permissions shown <br>**(app_access, API.ReadWrite.All, Automation.ReadWrite.All)**,<br> then choose **Add permissions**. | ![/assets/img/BCOAuth/image18.png](../../assets/img/BCOAuth/image18.png) |
| 5.9. Choose **Grant admin consent for \<Tenant name\>**. | ![/assets/img/BCOAuth/image19.png](../../assets/img/BCOAuth/image19.png) |
| 5.10. Choose **Yes** to confirm granting consent.<br>After this, the permissions should show a status indicating consent has been granted. | ![/assets/img/BCOAuth/image20.png](../../assets/img/BCOAuth/image20.png) |
| | ![/assets/img/BCOAuth/image21.png](../../assets/img/BCOAuth/image21.png) |
| **6. Create a client secret**<br>In the left menu, select **Certificates & secrets**. | ![/assets/img/BCOAuth/image22.png](../../assets/img/BCOAuth/image22.png) |
| 6.1. Choose **New Client secret**. | ![/assets/img/BCOAuth/image23.png](../../assets/img/BCOAuth/image23.png) |
| 6.2. Enter **Description** and select **Expires (Select 24 Months)**, then choose **Add**. | ![/assets/img/BCOAuth/image24.png](../../assets/img/BCOAuth/image24.png) |
| 6.3. **Please save the secret value immediately**.<br>Copy the **Value** field as soon as it appears. You will not be able to retrieve it again after leaving the page.<br>Store it in a secure location (Key Vault / password vault). | ![/assets/img/BCOAuth/image25.png](../../assets/img/BCOAuth/image25.png) |
| 6.4. Choose **Overview**. | ![/assets/img/BCOAuth/image26.png](../../assets/img/BCOAuth/image26.png) |
| 6.5. Please save the **Application ID and Directory ID**. | ![/assets/img/BCOAuth/image27.png](../../assets/img/BCOAuth/image27.png) |

We need following information

<ul><strong>
<li>Application (client) ID</li>
<li>Client Secret</li>
<li>Directory (tenant) ID</li>
</strong></ul>