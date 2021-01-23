# Show AfterPay to localized customers/regions only
Simple script to only display AfterPay on the product pages if a customer is from a selected region. Out of the box if you're a US AfterPay merchant it will display for every location not just the US and vice versa for AU merchants. This is an extremely poor implementation on their behalf and is a poor experience for the customer who expects AfterPay even in a region where you're not a merchant because it displays for EVERYONE.
This should be basic functionaility provided out of the box by AfterPay but they do not. 

Simply remove the afterpay src script and replace it with this JS. You can also replace US with whatever region you're an afterpay merchant in or use multiple regions for CBT.
