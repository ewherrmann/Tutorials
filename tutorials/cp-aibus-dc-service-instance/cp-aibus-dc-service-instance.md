---
title: Create Service Instance for Document Classification with Trial Account
description: Create a service instance and the associated service keys for Document Classification, one of the SAP AI Business Services, using the SAP Cloud Platform trial cockpit.
auto_validation: true
time: 15
tags: [tutorial>beginner, topic>machine-learning, topic>artificial-intelligence, products>sap-cloud-platform, products>sap-ai-business-services, products>document-classification]
primary_tag: topic>machine-learning
---

## Details
### You will learn
  - How to check your Document Classification entitlements
  - How to create a service instance of Document Classification
  - How to create service keys for your service instance

---

[ACCORDION-BEGIN [Step 1: ](Enter your trial account)]

1. In your web browser, open the [SAP Cloud Platform trial cockpit](https://cockpit.hanatrial.ondemand.com/).

2. Navigate to the trial global account by clicking **Enter Your Trial Account**.

    !![Trial global account](01_Foundation20Onboarding_Home.png)

    >Document Classification is only available in the Europe (Frankfurt) region. Follow the steps described in [Get a Free Trial Account on SAP Cloud Platform](hcp-create-trial-account) and choose the Europe (Frankfurt) region. If this is not possible, create a new subaccount in the Europe (Frankfurt) region. You should then be able to find **Document Classification Trial** in your new subaccount **Entitlements**.

    >If this is your first time accessing your trial account, you'll have to configure your account by choosing a region. Your user profile will be set up for you automatically.

    >Wait till your account is set up and ready to go. Your global account, your subaccount, your organization, and your space are launched. This may take a couple of minutes.

    >Choose **Continue**.

    >!![Account setup](02_Foundation20Onboarding_Processing.png)

3. From your global account page, choose the `trial` tile to access your subaccount.

    !![Subaccounts](enter-trial-account.png)

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 2: ](Check entitlements)]

To use Document Classification, you need to make sure that your account is properly configured.

On the navigation side bar, click **Entitlements** to see a list of all eligible services. You are entitled to use every service in this list according to the assigned service plan.

Search for **Document Classification Trial**. If you find the service in the list, you are entitled to use it. Now you can set this step to **Done** and proceed with Step 3.

![Entitlements](check-entitlements.png)

If you do not find the service in your list, proceed as follows:

  1. Click **Configure Entitlements**.

    ![Configure Entitlements](configure-entitlements.png)

  2. Click **Add Service Plans** to add service plans to your entitlements.

    ![Add Service Plan](add-service-plans.png)

  3. Select **Document Classification Trial**, and choose the **default** service plan. Click **Add 1 Service Plan**.

    ![Add Service Plan](add-entitlements.png)

  4. **Save** your entitlement changes.

    ![Add Service Plan](save-entitlements.png)

You are now entitled to use the service and to create instances of the service.

>For more details on how to configure entitlements, quotas, subaccounts and service plans on SAP Cloud Platform Trial, see [Manage Entitlements on SAP Cloud Platform Trial](cp-trial-entitlements).

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 3: ](Access space)]

All applications and services live in spaces. By default, trial accounts only have the **dev** space available.

To access your spaces, click **Spaces** on the navigation side bar and select the **dev** space to open it.

![Spaces](access-space.png)

In this space you will create your service instance.

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 4: ](Access service via Service Marketplace)]

The **Service Marketplace** is where you find the available services on SAP Cloud Platform.

To access it, click **Service Marketplace** on the navigation side bar.

![Service Marketplace](access-service-marketplace.png)

Next, search for **Document Classification**. Click the tile to access the service.

![Document Classification in Service Marketplace](access-dc.png)

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 5: ](Create service instance)]

You will now create an instance of your service.

Click **Create Instance** to start the creation dialog.

![Service Instance](create-instance.png)

In the dialog, leave the default value for the service and the service plan. Enter a name for your new instance as `dc-inst` and click **Create Instance** to skip the other steps and create the instance.

![Create Instance](create-instance-dialog.png)

In the following dialog, click on **View Instance** to be navigated to the list of your service instances.

![View Instances](view-instances.png)

You have successfully created a service instance for Document Classification.

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 6: ](Create service keys)]

You are now able to create service keys for your new service instance. Service keys are used to generate credentials to enable apps to access and communicate with the service instance.

  1. Click the navigation arrow to open the details of your service instance. Then, click the dots to open the menu and select **Create Service Key**.

      ![Service Keys](create-service-keys.png)

  2. In the dialog, enter `dc-key` as the name of your service key. Click **Create** to create the service key.

      ![Create Service Key](create-service-key-name.png)

You have successfully created service keys for your service instance. You can now either view the service key in the browser or download it.

![View Service Key](view-service-key.png)

You will need the service keys values in the next tutorial.

[VALIDATE_1]
[ACCORDION-END]
