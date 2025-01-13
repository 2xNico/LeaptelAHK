This is a set of automated commands to speed up work. Used to working from ahk directly, not so much compiling into an exe. As a result, some things do break a little. 
Patching issues where I find them.

On open, it will open the NBN sso link, if this is not done, it will result in a bigip error. This is NBN’s fault, not mine. 

F9 presses F5 every 2.5 seconds. The idea is to refresh the page while waiting for authentication attempts, email updates, testing to complete, reprovisioning to complete etc. 

F10 stops this

Pressing Left+Right Alt reloads the script, 
Pressing Left+Right Ctrl suspends the script

Ctrl+Del - Searches what’s in your clipboard, such as NBN LOC IDs, PRIs, INC’s etc. 
Also does Auspost codes, links, google searches and tries to do MAC addresses (Make sure there are no spaces)

?ffs - Typing this will open a dropdown menu, allowing you to select a wholesaler, and automatically type out the relevant FFS script. 

?ph - Typing this autofills  1300 205 327

?bookedsms - Types out Your Leaptel NBN install is booked for [Time]. Please make sure someone is available, any issues call %phone%

?fault - Types out an email prompting contact on a fault
?faultsms - Types out “Leaptel here. Please get in contact with us regarding your open fault on 1300 205 327, so we can assist further.”
?closesms - Types out “Hi XXX, Leaptel here. We have closed off your fault, if you continue experiencing issues please let us know on 1300 205 327. “


?order - Types out an email prompting contact on an order
?ordersms - Types out “Please call Leaptel Customer Service Team on 1300 250 327. We unfortunately cannot proceed with your order until we make contact with yourself. Thank you”

?nudge - Types out an email advising fault will be closed if there’s no contact in 48hrs

?bpay - Opens a GUI window that creates an email with customer’s BPAY details 
Some characters may be broken, and require manual fixing. 

