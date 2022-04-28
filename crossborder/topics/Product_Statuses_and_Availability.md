[//]: # (title: Product Statuses and Availability)

## Product Statuses
To start selling a product on Ozon:
- Set a price.
- Update the stocks in your warehouse.
- Wait for moderation (1–3 days).

Product statuses and visibility are displayed in the [Products and prices → Manage Inventory](https://seller.ozon.ru/app/products?filter=all) section. 
The status shows whether the product has successfully passed moderation, and it includes the following:
- **Main Status**,
- **Substatus**, which explains why the product has such main status.

Visibility shows whether the PDP is available on Ozon. All foreign sellers work using the FBS scheme, 
so you should pay attention to FBS visibility. FBO visibility is not relevant for you. 
It is displayed for sellers who work using the FBO scheme.

``` python
a = 5
b = 6
c = 7

# Uncomment below to take inputs from the user
# a = float(input('Enter first side: '))
# b = float(input('Enter second side: '))
# c = float(input('Enter third side: '))

# calculate the semi-perimeter
s = (a + b + c) / 2

# calculate the area
area = (s*(s-a)*(s-b)*(s-c)) ** 0.5
print('The area of the triangle is %0.2f' %area)
```
{collapsible="true" show-white-spaces="true" collapsed-title="Python Program to find the area of triangle"}

<table>
<tr>
<td>Main
</td>
<td>Substatus
</td>
<td>Visibility
</td>
<td>Explanation
</td>
</tr>
<tr>
<td>On sale
</td>
<td>-
</td>
<td>Yes
</td>
<td>The product can be purchased on Ozon.
</td>
</tr>
<tr>
<td>On sale
</td>
<td>Updating the product
</td>
<td>Yes
</td>
<td>You have edited the product, and now we are checking the changes. The product displayed on Ozon has the old characteristics and can be purchased.
</td>
</tr>
<tr>
<td>On sale
</td>
<td>Not updated
</td>
<td>Yes
</td>
<td>You have edited the product, but the changes could not be applied. The product displayed on Ozon has the old characteristics and can be purchased.

</td>
</tr>
<tr>
<td>Ready for sale
</td>
<td>Out of stock
</td>
<td>No
</td>
<td>The product cannot be purchased as long as it is out of stock. Please enter its quantity in your warehouse.
</td>
</tr>
<tr>
<td>Ready for sale
</td>
<td>You have turned the visibility off	
</td>
<td>No
</td>
<td>You have turned the visibility of the product off, and it cannot be purchased on Ozon.
</td>
</tr>
<tr>
<td>Not on sale
</td>
<td>Creating
</td>
<td>No
</td>
<td>The product has not yet been created on Ozon, and it cannot be purchased yet.
</td>
</tr>
<tr>
<td>Not on sale
</td>
<td>Blocked
</td>
<td>No
</td>
<td>The product is blocked and cannot be purchased on Ozon.
</td>
</tr>
</table>

## Availability in the Warehouse

In order to see the detailed information on the quantity of the product in the warehouse, 
hover over the quantity of the necessary product on the <control>Products and prices → Manage Inventory</control> page:

![](status.251fba16.png)

Status values:
- **Available**: the quantity of products that can be purchased on Ozon. This quantity includes marked-down products.
- **Marked-down**: the quantity of marked-down products that can be purchased on Ozon. This status is not used for sellers from abroad.

- **Reserved**: the quantity of products that have been reserved by buyers. Products are considered to be reserved from the moment an order is placed on Ozon and until they are packed for delivery to the buyer.

- **Total Products**: the total quantity of products in the warehouse.