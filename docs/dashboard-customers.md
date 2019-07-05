---
id: dashboard-customers
title: Customers
---

View the details of all users who have provided you with their information by setting up an account or placing an order.

![Customers list](assets/dashboard-customers/1.png)

Click on an individual customer to get an overview of the general information, address, customer activity, and recent orders.

![Customer details](assets/dashboard-customers/2.jpg)


## Editing General Information

Make changes to the customer name and e-mail by simply typing into the relevant field in the General Information section. The Save button in the footer will change color once changes have been made that need to be saved.

In the General Information, there is a checkmark next to the text [[User account active]]. Accounts will be active as soon as they are created but you can check the box to suspend a customer account, for example, if you suspect malicious activity. If you have implemented a backend protocol that requires users to confirm account activation from an e-mail, which is not a default feature, this may also be useful if a user has issues with replying to the e-mail and asks for a manual activation.


## Removing a Customer

- Click on the individual customer overview from the main list
- Click the red Remove button in the footer then confirm deletion

> In compliance with GDPR laws in Europe, clicking [[Remove]] will delete the customer profile but information will be retained in active and prior orders for fulfillment purposes.


## Customer Orders and History

The Customer History section gives a brief overview of customer activity. You can view a single or all orders of a specific customer by clicking in the Recent Orders section. From there you can amend and take actions as described in the Orders section of these documents.


## Managing Customer Addresses

Click [[Manage]] in the Address field to edit or delete a customer address. You can set an address as the default shipping or billing address by clicking on the three dots in the right corner of the header of a specific address. 

In the top right corner of the Address Book page, there is an [[Add Address]] button. If a customer asks the administrator to manually add an address, it can be done here. When a customer has more than one address listed, it is important to assign the correct billing and shipping addresses, as described above.

> **Localized Addresses**
>
> When creating addresses in different countries, Saleor uses Google’s address internationalization database to validate addresses automatically (in both local language/alphabet and their Latinized version: “北京” vs. “Beijing”).
> 
> Saleor can also provide front-end code with information on:
>
> - which fields should be visible
> - how the fields should be arranged
> - what field labels to use (“zip code” vs. “postal code”, “state” vs. “district”, etc.)