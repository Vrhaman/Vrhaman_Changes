# Vendor:

# Payment Process

## Working Secanrio in Single Flow:

- Customer selects a vehicle, Now two options:

> a) Pay Now(20%):

- Cx click on Pay Now.
- Vendor Accepts booking
- ![alt text](image-1.png)
- Partial Payment done
- Booking Confirmed in customer App and in vendor App
- ![alt text](image-2.png)
- Go to Home->Bookings-> Make full payment-> Payment successfull
- ![alt text](image-4.png) ![alt text](image-5.png)
- ![alt text](image-3.png)

> b) Pay Full Amount

- cx click on pay full amount
- vendor accepts booking
- ![alt text](image-13.png)
- Customer click Make Payment-> Payment Gateway opens:
- ![alt text](image-15.png)
- Payment Successfull-> Booking confirmed.
- ![alt text](image-16.png)
- ![alt text](image-14.png)

## Non- Working Secanrio in Single Flow:

> b) Pay Full Amount

- cx click on pay full amount
- vendor accepts booking but in customer side still showing waiting for confirmation
- ![alt text](image-8.png)
- ![alt text](image-6.png)
- No customer has no option to go back. So cx minimizes the app and reopens
- bookings->payment->direcly payment gateway opens but price is Rs. 1 (It should be 10)
- ![alt text](image-9.png) ![alt text](image-10.png)
- Cx pays Rs.1-> Payment Successfull
- ![alt text](image-11.png)
- Status completed on all platforms: customer, vendor, admin.
- ![alt text](image-12.png)![alt text](image-7.png)

# Non Working Scenarios When Customer Minimizes the app:

> a) Pay Now(20%):

- Cx click on Pay Now.
- Vendor Accepts booking
- ![alt text](image-18.png)
- Cx doesnot do the payment. Cx closes the app and reopens-> bookings-> click on Payment:
- ![alt text](image-20.png) ![alt text](image-21.png)
- Payment Sucessfull. Now status showing completed in all platforms:
- ![alt text](image-22.png)![alt text](image-19.png)
- Now no option of Full Payment.
- ![alt text](image-23.png)
- In all platforms, the status should be "confirmed" not "completed"

> b) Pay Full Payment:

- Cx click on Pay Now.
- Vendor Accepts booking
- ![alt text](image-24.png)
- Cx doesnot do the payment. Cx closes the app.
- bookings->payment->direcly payment gateway opens but price is Rs. 1 (It should be 10)
- ![alt text](image-9.png) ![alt text](image-10.png)
- Payment Sucessfull. Now status showing completed in all platforms:
- ![alt text](image-26.png)
- ![alt text](image-25.png)
- In all platforms, the status should be "confirmed" not "completed"

# Admin_Panel:

- All users are showing inactive even if we are using the customer app.
- Number of users in not same in dashboard and useres section. For example, in dashboard it is 10 and in users section it is 53.
# Customer:

- Add terms & privacy and About Vrhaman.
- For incorrect otp, shows Instance of server exception.
- If Loaction is already off and customer opens the app. No pop-up for enable location
- After Log out-> if we click on back option- the login session continues with error. Video shared.
- In my customer account(7381211213), under the bookings, it is showing as Error. It is happening only for me. Tried in 2 devices
- ![alt text](image.png)
