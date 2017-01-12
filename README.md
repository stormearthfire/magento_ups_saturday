### Magento UPS Delivery on Saturday

By default Magento comes with a preinstalled module which supports UPS delivery and allows shop owner to choose which of their delivery methods they want to offer.

UPS also has a service which allows delivery on Saturday, and it usually costs $16.76 more than the regular service, but that delivery method is not covered by Magento's module. It is available only for the following delivery methods: UPS Next Day Air, UPS Next Day Air Early A.M. and UPS Second Day Air.

This module expands support for UPS services by allowing shop owners to choose whether they want to offer Saturday delivery as an option.


### Installation steps

1. Install the module as any other Magento module
2. Login to admin, clear the Magento cache if it's activated
3. Go to **System**->**Configuration**, then from the left menu choose **Shipping Method**, and find **UPS Shipping** tab
4. Check UPS Type parameter - it has to be set to "**United Parcel Service XML**", it will now work with CGI "United Parcel Service" option - Saturday deliveries can not be fetched with CGI queries
5. Set "**Delivery on Saturday**" parameter to "Yes"
6. Clear the Magento cache once again, if it is activated

