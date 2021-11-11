# Payment-System
Payment system using symfony + stripe

# Testing
1. Click your checkout button
2. Fill out the payment details with the test card information:
   - Enter 4242 4242 4242 4242 as the card number.
   - Enter any future date for card expiry.
   - Enter any 3-digit number for CVC.
   - Enter any billing postal code.
3. Click Pay.
4. You’re redirected to your new success page.
Next, find the new payment in the Stripe Dashboard. Successful payments appear in the Dashboard’s list of payments. When you click a payment, it takes you to the payment detail page. The Checkout summary section contains billing information and the list of items purchased, which you can use to manually fulfill the order.
