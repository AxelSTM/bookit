# Stripe

To use **Stripe** as a payment method for appointments, go to **BookIt Calendar > Settings > Payments**.\
Enable Stripe and enter **Stripe Publish Key** and **Stripe Secret key.**

![](https://lh6.googleusercontent.com/WZSgGu\_jPvSsx-Fn0b56vHFiNjLDduB3BaY3nXM48WcMJSPcRQsXs7hxcnN9SmSwh-8V5X-MNQWb3yB8ZAtStkweeRzXbZf59B3UkzYTaumyloB9W3be9oV2wsUeQcBMtx0sr1QS)

{% hint style="info" %}
You can create a Stripe account on the official website of [Stripe](https://stripe.com/).
{% endhint %}

To collect the keys you need to log in to the Stripe site. All the keys are available on the Home page of your Dashboard.&#x20;

In order to get the test key, follow **Dashboard > Get your test API keys**, and to get the live keys, go to **Dashboard > Get your live API keys**.

![](../.gitbook/assets/101.png)

Copy your Keys and paste them to the required fields under the **Payments** tab.

![](../.gitbook/assets/102.png)

When customers are booking the appointment they need to select **Pay now with Credit Card** option and click **Book Now**.

![](../.gitbook/assets/103.png)

![](../.gitbook/assets/104.png)

After the successful appointment request, customers will get a similar email message, where all the booking details can be found:

![](../.gitbook/assets/105.png)

The admin will also get an email notification:

![](../.gitbook/assets/106.png)

If you follow to **Dashboard > Bookit Calendar > Appointments** you will see that the payment status has changed automatically.

![](../.gitbook/assets/107.png)

{% hint style="info" %}
Please note that all transactions are managed by **Stripe**.
{% endhint %}

After payment is received, the appointment can be managed by the admin, who needs to **Approve** it.&#x20;
