---
title: Elysys Corporate Setup
tags: 
 - Elysys Corporate
description: How to setup the Elysys corporate module
---

# Elysys Corporate

Elysys Corporate is a management tool that helps companies manage their
organizational structure, shareholders, owners, directors, properties,
and other third-party individuals and/or organizations associated with
the organization e.g., brokers, attorneys and/or tenants.

It includes features such as tracking shareholders' holding percentage,
capital structure, tax reporting, and agreements and contracts
management.

## Setup 

![](../../assets/img/ElysysCorporate/image001.jpg)

a)  **Corporate Setup**

    Path: Corporate Setup -> Setup -> COP Corporate Setup

1. Define No. Series for the following:

    -   Property

    -   Contact

    -   Company

2. Define professional roles used within the organization, e.g.

    -   Director

    -   Shareholder

    -   Owner

    -   Notary

    ![](../../assets/img/ElysysCorporate/image002.jpg)

    Specify roles under the Mailing Groups.

    ![](../../assets/img/ElysysCorporate/image003.jpg)

b)  **Role Setup**

    Path: Corporate Setup -> Role Setup -> COP Role Setup

Specify roles to which professionals are assigned to.

![](../../assets/img/ElysysCorporate/image004.jpg)

c)  **Incorporation Document Type**

Path: Corporate Setup -> Incorporation Document Type -> Document Type

Specify document types that will be uploaded into the module. The user can define an indefinite number of document types.

![](../../assets/img/ElysysCorporate/image005.jpg)

## Workflow 
### I. Creating Contacts Automatically 
The system allows automatic integration of Business Central contacts
by defining Bus. Relation Code in the Marketing Setup screen for
Customers, Vendors, Bank Accounts and Employees. Once defined, the
system automatically imports all contacts from Business Central into
Corporate Module.

    Path: Marketing Setup -> Interactions -> Bus. Relation Code for

![](../../assets/img/ElysysCorporate/image006.jpg)

### II. Creating Contacts Manually 

    Path: Corporate Activities -> Contact

 All contacts need to be created under the Corporate Activities before
 being assigned to corresponding Administration Activities.

 Contacts can be created as a Person or a Company

**Contact Card**

1.   **General**
![](../../assets/img/ElysysCorporate/image007.jpg)

2. **Communication**
![](../../assets/img/ElysysCorporate/image008.jpg)

3. **Foreign Trade**
![](../../assets/img/ElysysCorporate/image009.jpg)

4.  **Notes:**
    -   Aggregated list for all contacts appears under the Contact view.
    -   Contacts created as companies are in **bold**.

    ![](../../assets/img/ElysysCorporate/image010.jpg)

### III. Administration Activities 

Before a Corporate Contact is created, any related contacts previously
created need to be assigned to a corresponding role or roles under the
Administration Activities.

One contact can be assigned to one or multiple roles.

![](../../assets/img/ElysysCorporate/image011.jpg)

![](../../assets/img/ElysysCorporate/image012.jpg)

![](../../assets/img/ElysysCorporate/image013.jpg)

### IV. Corporate Contact 

Corporate Contact stores detailed information regarding a company or a
person, its contact details, tax information, shareholders and share
distribution, ultimate owners, and directors.

**GENERAL INFORMATION**

**Corporate Contact Information**

![](../../assets/img/ElysysCorporate/image014.jpg)

**Warning Dates**

![](../../assets/img/ElysysCorporate/image015.jpg)
Warning 1-3 -- Specifies the important deadlines regarding the Corporate
Contact.

Warning Date 1 -- Specifies the important dates to be tracked by the
company.

Define Warning Events/Dates if you wish to be notified of any upcoming
deadline up to three months before its due date.

![](../../assets/img/ElysysCorporate/image016.jpg)

![](../../assets/img/ElysysCorporate/image017.jpg)

#### i. Corporate Contacts -\> Functions 

Under Functions of the Corporate Contact the user can specify Capital
Structures, upload documents, record tax information and assign bank
accounts.

![](../../assets/img/ElysysCorporate/image018.jpg)
-   **Capital Structures**
![](../../assets/img/ElysysCorporate/image019.jpg)

-   **Various Corporate** -- supporting information.
![](../../assets/img/ElysysCorporate/image020.jpg)

-   **Documents History** -- a file can be attached by clicking Upload
    Document then choosing the files to be uploaded.
![](../../assets/img/ElysysCorporate/image021.jpg)

-   **Tax Filling** -- in order to define Tax Information, go to Tax
    Filling Card then Function where you can define Tax Information of
    the Corporate Contact.
![](../../assets/img/ElysysCorporate/image022.jpg)

-   **Banks Assigned** -- in order to define Bank Accounts related to
    the Contact go to Banks card.

#### ii. Corporate Contacts -\> Property 

Used to link associated contacts with the corporate contact, e.g., its
Shareholders and Partners and Corporate Owners, their holding
percentage, date of appointments, Directors and other.

    Path: Corporate Contact -> Property
                               Shareholders or Partners
                               Notary
                               Board and Authority
                               Power of Attorney
                               Corporate Property
                               Director or Officer
                               Corporate Owner
                               Insurer

![](../../assets/img/ElysysCorporate/image023.jpg)

**Shareholders or Partners**

In order to define a Shareholder's holding percentage, select **Type =
Shareholder**.

![](../../assets/img/ElysysCorporate/image024.jpg)

To link another Corporate Contact and its holding percentage, a company,
or a person, select **Type = Corporate Contact.**

![](../../assets/img/ElysysCorporate/image025.jpg)

View the chart displaying Organizational Structure and its Shares
Distribution under the main screen of the module.

![](../../assets/img/ElysysCorporate/image026.jpg)

### V. Property 

![](../../assets/img/ElysysCorporate/image027.jpg)

![](../../assets/img/ElysysCorporate/image028.jpg)

###  i. COP Property Card 

Property Card specifies the details of the property, its owners, shares
distribution, tenants, and other third party\'s companies and
individuals, such as a Broker and/or an Insurer assigned to the
property.

![](../../assets/img/ElysysCorporate/image029.jpg)

-   **Ultimate Owner**

        Path: COP Property Card -\> Property -\> Ultimate Owner

    Specifies Ultimate Owners of the property and the shares distribution.

    ![](../../assets/img/ElysysCorporate/image030.jpg)

-   **Tenant**

        Path: COP Property Card -> Property -> Tenant

    Specifies details about the tenants occupying the property, the rent
amount and payment method.

    ![](../../assets/img/ElysysCorporate/image031.jpg)

-   **Corporate Property**

    Specifies the company which has full or partial ownership of the
    property.

    ![](../../assets/img/ElysysCorporate/image032.jpg)

-   **Notary, Insurer and Broker**

    Specifies the Notary, Insurer and Broker associated with the property.

-   **Power of Attorney Action**

    Specifies the details of the Attorney and the type of authority it
holds.

    ![](../../assets/img/ElysysCorporate/image033.jpg)
