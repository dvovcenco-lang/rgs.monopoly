# RGS Monopoly

Pre-order site for RGS Monopoly, Year 11 Tycoon Enterprise, RGS Guildford.

## How reservations work
Reserving is free. Each reservation is emailed to rgs.monopoly@gmail.com with a reference (RGS-1234), marked "not paid yet". Once a set is made, email that customer how to pay.

When you've had as many reservations as you can make, open `index.html`, find `fullyReserved: false` in the `CONFIG` block and change it to `true`. The form then shows "All sets reserved".

The very first reservation triggers an activation email to rgs.monopoly@gmail.com: click **Activate Form** once and every reservation after that arrives as an email.

## Dates
The fair date and the reservation deadline live in the `CONFIG` block in `index.html` (`fairDate` and `closeDate`, in UK time). Currently the fair is Sat 28 Nov and reservations close Mon 23 Nov at 6pm.

## Images
`img/` holds the board, card and title deed images shown on the site. They're rendered from the print set, so ask Claude to re-render them when the designs or photos change.
