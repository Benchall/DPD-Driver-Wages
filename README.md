# Driver Pay Log

A single web page (`index.html`) for logging DPD driver wages.

- Log each route: date, driver name, route number, depot, van type and stop count.
- Pay: £1.20 per stop on big van routes, £1.00 per stop on little van routes.
- Van hire: £10 per day comes off each driver's pay, once for each day they work.
- Charges taken off pay: dropped route (£100 by default), van damage, parking tickets, advance payments, fuel over allowance.
- Payments added to pay: bonus, ridealong (£50 a day by default), top up.
- Views: day by day, weekly by driver, and a 4-week pay period total that resets every 28 days.
- Rates, van hire, the dropped route charge, the ridealong rate, the pay period start date and the list of little van routes can be changed under "Rates and pay period".

The page is published as a claude.ai Artifact, which stores the log in its own database.
