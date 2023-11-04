# Office_Ordering_Application
This is a simple Office Ordering Supplies Application that allows employees to order items they need to work.The aaplication is driven by Sharepoint-site called "OfficeOrderingSite"

On that site we have 3 lists:

"Categories" (these are all required fields!)
- Title = default Sharepoint-field (will serve as the category name)
- CategoryID = number field
- CategoryImage = image field (I used 250x250 jpg-images)

"Items" (these are all required fields!)
- Title = default Sharepoint-field (will serve as the item name)
- ItemID = number field
- CategoryID = number field
- ItemPrice = currency field
- ItemImage = Image field (I used 250x250 jpg-images)

"OrderHeader" (these are all required fields, except for "Notes"!)
- ID = default Sharepoint-field
- Email = default Title-field renamed to "Email"
- Orderer = required single line of text field
- OrderDate = required single line of text field
- Notes = not-required multiple lines of text field
- TotalAmount = required currency field
- NumberOfItems = required number field
- Status = required Choice-field (with options: Ordered, Approved, Rejected, NeedsApproval)


<img width="716" alt="Screenshot_1" src="https://github.com/RathogwaInnocent/Office_Ordering_Application/assets/17208775/51037c21-d254-4ceb-85f3-3e17a99f9bbb">

>>> This Home page serves as the main contact of the application, you have two buttons that allows to create an order for what you need and that will be sent to approved and decline.
>>> You also get an 2nd button which you can view existing orders that were sent 

<img width="716" alt="Screenshot_2" src="https://github.com/RathogwaInnocent/Office_Ordering_Application/assets/17208775/5c3a2b6d-5f70-4b9d-b9dc-b9f0caa3e682">

>>> This is the create new order screen,where you add all items. you have a button to clear the backet and confirm order once you are ready to submit your order.

<img width="716" alt="Screenshot_3" src="https://github.com/RathogwaInnocent/Office_Ordering_Application/assets/17208775/2a4f72db-0dac-4399-8b96-f99109dbb448">

>>> On the Existing Order screen you get to view all orders submitted, you can also see you own orders that you placed.
