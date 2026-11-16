# RGS Monopoly

Pre-order site for RGS Monopoly, Year 11 Tycoon Enterprise, RGS Guildford.

## How orders work
Customers fill in the form, then pay £25 per set through the SumUp payment link (`paymentLink` in the `CONFIG` block of `index.html`). Each order is emailed to rgs.monopoly@gmail.com with a reference (RGS-1234). Only count an order once a SumUp payment with that reference or name has arrived. Cancel unpaid orders after 48 hours.

When you've sold as many sets as you can make, change `fullyReserved: false` to `true` in `CONFIG`. The form then shows "All sets reserved".

The very first order triggers an activation email to rgs.monopoly@gmail.com: click **Activate Form** once and every order after that arrives as an email.

## Dates
The fair date and the reservation deadline live in the `CONFIG` block in `index.html` (`fairDate` and `closeDate`, in UK time). Currently the fair is Sat 28 Nov and reservations close Mon 23 Nov at 6pm.

## Images
`img/` holds the board, card and title deed images shown on the site. They're rendered from the print set, so ask Claude to re-render them when the designs or photos change.
