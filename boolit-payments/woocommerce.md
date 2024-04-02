# WooCommerce

If you’d like to use WooCommerce as a payment method, enable WooCommerce under the payment tab in the **BookIt Calendar** Settings.&#x20;

![](https://lh4.googleusercontent.com/tCnj9tFd9LlbDmBA-Dp6ZX4Eect6qEISHHdIg2mYpNzOxPZas1iUiD\_pasmtD5VYaKByjAzNeyxmplHtAgAUQ3wdqD45H9jMhgg6ACdcuJOOv--\_nB1n7WQ7P63MnLX2nZuQ1pvi)

You will need to specify the WooCommerce product for it. You can create one WooCommerce product for all services and specified it in the BookIt Calendar settings. Just select it from the dropdown under the **WooCommerce Product** title.

{% hint style="danger" %}
The instructions above consider that the WooCommerce plugin is already set up on your site. If not, please follow the WooCommerce instructions here: [https://docs.woocommerce.com/documentation/plugins/woocommerce/getting-started/](https://docs.woocommerce.com/documentation/plugins/woocommerce/getting-started/)
{% endhint %}

For the services, you can create one Simple Product and set the maximum number for the Stock quantity as all services will be checked out through this product.\
For the product's price specify any number, except 0. The price of the service will be applied automatically.&#x20;

![](../.gitbook/assets/108.png)

When booking appointments, customers will need to select the **WooCommerce Checkout** option.

![](../.gitbook/assets/109.png)

After appointment submission, the customer will be redirected to the WooCommerce checkout page.&#x20;

![](../.gitbook/assets/110.png)

After that, the customer will be required to fill in all the fields and select the payment method.&#x20;

{% hint style="info" %}
The design of the checkout page and the display of the fields fully depend on the site's active Theme. For example, on the screenshot below we used the TwentyTwenty WP theme.
{% endhint %}

![](../.gitbook/assets/111.png)

{% hint style="info" %}
All the methods available for WooCommerce can be used. The BookIt Calendar plugin does not control payments.&#x20;
{% endhint %}

After the successful payment, the customer will be redirected to the Default Order Received page.

![](../.gitbook/assets/112.png)

Admin can check the order details in **WooCommerce > Orders**.

![](../.gitbook/assets/114.png)

{% hint style="info" %}
All offline payment methods and PayPal Sandbox require the admin to change the payment methods manually in orders.&#x20;
{% endhint %}

After successful payment, the admin has to approve the appointment manually.

![](../.gitbook/assets/115.png)
