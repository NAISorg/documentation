---
description: >-
  Market View 6, released in fall 2022, enables schools to sync admissions data
  from their admission software. This guide walks you through how to set this
  up.
---

# Sync data from Blackbaud

## Overview <a href="#step-1-add-market-view-to-veracross" id="step-1-add-market-view-to-veracross"></a>

### Audience <a href="#step-1-add-market-view-to-veracross" id="step-1-add-market-view-to-veracross"></a>

This guide is for schools who are [NAIS ](https://www.nais.org)members, and use Blackbaud for admissions or application data.&#x20;

After one person at your school completes this process, the integration will work for everyone at your school. Each user should use their own login. Any NAIS member school can have unlimited staff accounts. Add and manage your school's roster at [my.nais.org](https://my.nais.org).

### Goal <a href="#step-1-add-market-view-to-veracross" id="step-1-add-market-view-to-veracross"></a>

This integration syncs two types of data from Blackbaud into Market View.

1. Applicants. If it exists, we will sync names, grades, addresses, and student IDs for students who applied to your school.
2. Enrollments. If it exists, we will sync names, grades, addresses, and student IDs for students who enrolled in your school.

{% hint style="info" %}
Market View is committed to the highest security of your data. We encrypt all data in transit from your admission software, and any time it is used. We encrypt the data within our database. Your data will never leave our database or be shared. We take data security and privacy extremely seriously.[ Read more about how Market View protects your data. ](../../data-privacy.md)
{% endhint %}

## Step 1: Give yourself permissions in Blackbaud

You'll need to go to Core > Security > Roles. (Do not try to manage roles for this from the security/control panel area).

Find the role in the list and choose Manage Roles from the menu.

Go to Members, Add member and search for yourself to add.

![](<../../../.gitbook/assets/image (37).png>)



You'll need these roles:

1. Platform Manager or Environment Admin
2. Academic Group Manager, Schedule Manager, or Platform Manager
3. SKY API Data Sync
4. Admissions Manager

## Step 1: Add Market View to Blackbaud <a href="#step-1-add-market-view-to-veracross" id="step-1-add-market-view-to-veracross"></a>

{% hint style="warning" %}
This step must be performed by one of your school’s administrators of Blackbaud, someone with “Platform Manager”, "Environment Admin" or equivalent permissions. If you aren’t an admin, feel free to forward these instructions to someone who is.
{% endhint %}

* [ ] Log into Blackbaud.
* [ ] Click this link: [https://app.blackbaud.com/marketplace/applications/442d9d54-20c1-4d72-9f82-be631861a49d?envid=t-f-g5WCInc0Gkwv\_5fvgxjA](https://app.blackbaud.com/marketplace/applications/442d9d54-20c1-4d72-9f82-be631861a49d?envid=t-f-g5WCInc0Gkwv\_5fvgxjA)
* [ ] You should see something like this

![](../../../.gitbook/assets/Fullscreen\_8\_17\_22\_\_3\_21\_PM.png)

* [ ] Click "Connect"/ "Get Started"
* [ ] Follow the steps to finishing adding Market View as an integration partner

## Step 2: Authorize Market View <a href="#step-2" id="step-2"></a>

{% hint style="info" %}
This step requires an admin user of Blackbaud with one of the following roles: Academic Group Manager, Schedule Manager, Platform Manager. In addition, the user must have the Admissions Manager role and Sky API Data Sync role. If that's not you, feel free to send these instructions to your administrator to complete.&#x20;
{% endhint %}

* [ ] Log into Market View: [https://marketview.nais.org](https://marketview.nais.org)
* [ ] Click on "Connect to Blackbaud"
* [ ] Click "Log in with your Blackbaud Account"
* [ ] A window should pop open where you can log in with your Blackbaud credentials
* [ ] You should be routed back to Market View. Congratulations!

![](<../../../.gitbook/assets/image (5).png>)

## Next steps

* [ ] Now that your integration is complete, you can sync fresh data from Blackbaud anytime by clicking the "Sync" button.

{% hint style="info" %}
Get an error? Need more help? Email marketview@nais.org.
{% endhint %}
