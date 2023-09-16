## Search Intent

This document pertains to the intent of purchasing or utilizing a product or service. The Buyer Supporting Node (BSN) allows consumers to declare their intentions, which include:

- What they desire (product, service, offer)
- Whom they require (seller, service provider, agent, etc.)
- Where they wish to obtain it and the source
- When they need it (start and end times for fulfillment)
- How they intend to make the payment

This declaration encompasses properties such as a search string, provider, fulfillment, category, item, etc. Typically, the BSN employs this information to communicate the user's search purpose. Subsequently, the BPP uses this information to identify products or services within its offerings that align with the user's intent.

For instance, for Rideshare, a consumer declares their intent, specifying various aspects of their journey:

- Starting location for their journey (intent.fulfillment.start.location)
- Ending location for their journey (intent.fulfillment.end.location)
- Desired start time (intent.fulfillment.start.time)
- Desired end time (intent.fulfillment.end.time)
- Preferred transport service provider (intent.provider)
- Passenger information (not recommended in public networks) (intent.fulfillment.customer)
- Choice of a product (intent.item)
- Selection of additional services
- Preferred service category (intent.category)

Similarly, in retail, a consumer declares their intent for a lab booking, outlining various booking aspects:

- Preferred scan/test location (intent.fulfillment.start.location)
- Desired scan/test time (intent.fulfillment.start.time)
- Expected results delivery time (intent.fulfillment.end.time)
- Preferred service provider (intent.provider)
- Information about the individual undergoing the test/scan (intent.fulfillment.customer)
- Choice of test/scan type (intent.item)
- Selection of the service category (intent.category)
- Preferred payment method (intent.payment)
