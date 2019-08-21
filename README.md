# SherpaDerp
All-in-one software for DDL.

SherpaDerp is software that unites administrative processes for the Sales People, Administrators, Accounting, Service Dispatch, and Executives in one. 
The need for this software arose from the usage of multiple software packages that had a hard time communicating with one another.  We have one for accounting that doesn't include all the features we would like to have, another for sales people that looks like it was designed 15 years ago and has endless bugs, and another that spams your emails with useless information (which wouldn't be so bad except the notifications for everyone must be managed by one admin, so everything is just always on).  
An advantage of paying no licensing fees and having the software built in house to meet the exact needs of DDL was another driving factor. Because the software is specific to one company, it can be very lightweight and features can be added on the fly without paying inflated development costs to a third party.  The software can also be scaled to include more members of any part of the company without additional cost.  
Now instead of having to decide who 'really' needs a license and who doesn't, everyone has access.  When new employees join the company we don't have to commission new licenses, and if the company contracts, we aren't committed to too many licenses.
On top of all that, having a lightweight, streamlined, web-based software to use makes everything more efficient.  No more work arounds -- just fluid process.


Notes
-------------------------------------------------
USER STRUCTURE
1 Directors (Perry, Jim, Lisa)
	- Reports	
	- simple mode / full priveleges mode.  In simple mode the directors will only see what they want to see -- Reports.  They will make their decisions and tell people what to do. No need for Administrative functions to clutter their UI.  But they should have the ability to click a button and enable "full priv mode" which would give them admin abilities as well.  When they are done with it they can turn it off again and just see their favourite reports.
2 Managers 
	- Reports
	- Sales funnel (still need more info on what this is)
	- Rep stats
	- Leasing and customer info
3 Sales Reps
	- Customer Equipment
	- Lease tracker
	- Proposals (with config validation)
	- Paperwork
	- Submit Orders (as quotes to admin team)
	- Prospect management
	- Sales teams
	- Sales Zones
	- "named" accounts
	- Sales funnel (still need more info on what this is)
4 Administrators (krishani, sumira, lisa, michelle)
	- orders (received as quotes, converted in to Sales Orders, then converted into invoices)
	- purchase orders
	- invoicing
	- receivables
	- on hold
	- accounting
	- customers
	- reports
5 Accounting dept (lyra, Lisa)
	- everything administrators have +
	- Payables
	- Banking
	- Journal Entries
6 Warehouse crew
	- dispatch centre tasks
	- inventory centre


ROLES
- roles should have access to modules (apps), and you assign users to groups which have roles assigned to them.


Dashboard
- the dashboard will be a widget section.  I'm currently envisioning a card layout with descriptions. You could maybe choose between the card layout and a simpler heiroglyphic style setup, where the name would show up on hover. like a circular logo with a hidden name underneath that shows when you hover the module.  Yah I like that.
- The roles would be easier to do because you would just have a list of widgets, or apps, and assign them to groups. You assign users to groups, and bam, they can see those widgets.
- This makes a flow where the user will come back to the dashboard to get a birds eye view of the things they can do, then select one and drill down into using it.
- Received receipts for documents could be cool.  Basically when you send an invoice or whatever from the system, in the email it asks the user to click a button showing they have received the invoice.  This way, if the user clicks that button, it will send a JSON response to the originator's account -- updating a little flag on the document to show "receipt confirmed".
