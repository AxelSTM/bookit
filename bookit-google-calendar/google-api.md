# Google Calendar API

The Google Calendar add-on allows linking the plugin to the Google Calendar. The Bookit plugin interacts with the Google Calendar through Google Calendar API that the appointments in the Bookit plugin transfer to the Google Calendar.

It is required to get a **Client ID** and **Client Secret** key from the **Google Developers** website: [https://console.developers.google.com](https://console.developers.google.com) to synchronize Google Calendar events to the addon.

{% hint style="info" %}
[Google Developers](https://console.developers.google.com) is the special website for software development tools and platforms, APIs, and technical resources.
{% endhint %}

## App creation preparation

If you visited the Google Developers website for the first time, it is necessary to make a registration and agree on Google's Terms and Services.

![](<../.gitbook/assets/image (9).png>)

Afterward, click the **Select a project** button from the upper-left corner of the site.&#x20;

![](<../.gitbook/assets/image (71).png>)

On the opening modal, select the New Project.

![](<../.gitbook/assets/image (203).png>)

The Project name should be entered and the location can be left with **No organization** as a default.

![](<../.gitbook/assets/image (166).png>)

## **OAuth consent screen**

Afterward, you will be forwarded to the Dashboard of **APIs & Services**. Go to the **OAuth consent screen** menu.

![](<../.gitbook/assets/image (90).png>)

Select the **External** User Type and click the **Create** button.

![](<../.gitbook/assets/image (160).png>)

It is required to go through four steps of registration in the **OAuth consent screen** menu.

![](<../.gitbook/assets/image (19).png>)

In the first step, fill up all the required fields according to your domain information.

![](<../.gitbook/assets/image (56).png>)

{% hint style="danger" %}
**Important!**

If you upload the company's logo to the appropriate field, it requires verification from Google. It means that Google checks all the provided app details and this process may take some time.
{% endhint %}

On the **Authorized domains** section, enter the domain's name and developer contact email.

![](<../.gitbook/assets/image (8).png>)

In the second step, the **Scopes** can be added or removed. Scroll down and click the **Save and Continue** button after making changes.

![](<../.gitbook/assets/image (121).png>)

In the third step, the testing users can be added to test the app. Click the **Save and Continue** button after making changes.

![](<../.gitbook/assets/image (74).png>)

In the fourth step, the summary of the entered information displayed to check its correctness.

![](<../.gitbook/assets/image (118).png>)

Scroll down and click the **Back to Dashboard** button.

![](<../.gitbook/assets/image (66).png>)

By default, the app is created with the Testing status. By clicking the **Publish App** button, the app will be publishing, and the status changes to In Production.

![](<../.gitbook/assets/image (155).png>)

The below-listed Google verification conditions should be provided in case if you uploaded your logo to push your app to production.

![](<../.gitbook/assets/image (84).png>)

## Library

Go to the **Library** and type the **Google Calendar API** on the searching field.

![](<../.gitbook/assets/image (97).png>)

![](<../.gitbook/assets/image (39).png>)

Select the Google Calendar API and **Enable** the calendar integration.

![](<../.gitbook/assets/image (161).png>)

## Credentials

Afterward, go to the **Credentials** menu to add a new credential.

![](<../.gitbook/assets/image (177).png>)

Press the **Create Credentials** button.

![](<../.gitbook/assets/image (117).png>)

On the opening modal, select **OAuth client ID**.

![](<../.gitbook/assets/image (5).png>)

Select the **Web application** as the Application type.

![](<../.gitbook/assets/image (184).png>)

Any name can be inserted into the **Name** field to identify the OAuth web client.

![](<../.gitbook/assets/image (138).png>)

Copy the **Redirect URI** link taken from the **Bookit plugin's** path of **Dashboard > Settings > Google Calendar** and paste it to the Google's **Authorized redirect URIs** field.

![](<../.gitbook/assets/image (113).png>)

After pasting the URI, click the **Create** button.

![](<../.gitbook/assets/image (132).png>)

Afterward, the OAuth client creation confirmation pops up, providing a unique **Client ID** and **Client Secret**.

![](<../.gitbook/assets/image (61).png>)

Copy the Client ID and Client Secret and paste to the **Bookit plugin's** path of **Dashboard > Settings > Google Calendar.**

![](<../.gitbook/assets/image (126).png>)

{% hint style="danger" %}
**Important!**

To make Google calendar work properly and synchronize appointments properly it is required to set the time zone in WordPress general settings in UTC format. For example if you live in New York the time zone should be selected as UTC -5.
{% endhint %}
