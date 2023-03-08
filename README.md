# Creating coupons via BigCommerce API
**Create a promotion with the proper rules, you can pick an example from here:**
<p>https://developer.bigcommerce.com/promotions/beta/api-docs/code-samples/category</p>
<p>In the Parameters, add “store_hash” id and unique “X-Auth-Token” (this can be created in BigCommerce > Settings > API > API Accounts, see instructions here:</p> https://developer.bigcommerce.com/promotions/beta/api-docs/overview) 

<p><br>In the "redemption_type" replace “AUTOMATIC” with “COUPON”</p>

<p>To add coupon code to the promotion, go to this page:</p>

<p>https://developer.bigcommerce.com/promotions/beta/api-reference/operations/create-a-store-v-3-promotion-code</p>

<p>Left side select Coupon Codes (Single) > Create A Coupon Code [POST]
Update the fields on the right side of the screen with coupon name.</p>

<p>Copy the JSON code that worked for your promotion in case you need to make updates in the future.</p> 

<p>If coupon code needs to be updated, you can go to this page:</p>
https://developer.bigcommerce.com/promotions/beta/api-reference/operations/update-a-store-v-3-promotion
 
<p><br>On the left side go to Promotions (Single) > Update Promotion (Beta)
On the right side insert the promotion fields and parameters.</p>  
