# KeyAuth-Register-Without-A-Key

The original method was deleted because a lot of people couldn't tell the code wasn't secure, not sure how... 
NOTE, you must have the seller subscription for this method to work. This method is also different from the last one. The last one auto created a key for you, then inserted that into the license field. This simply creates a new account just using username and password. 

However, here is the new method. 

1. Go to https://docs.keyauth.cc
2. Go to the users section and create "Create User" (first link)
3. Log into https://keyauth.cc
4. Go to webhook page
5. Add https://keyauth.win/api/seller/?sellerkey=sellerkeyhere&type=adduser& into the webhook file. MAKE SURE YOU ACTUALLY CHANGE THE SELLERKEY
6. On your form after you have added KeyAuth already, on your register button, add KeyAuthApp.webhook("WebhookID", user=usernamehere&sub=default&expiry=1&pass=passwordhere);  - for the usernamehere and passwordhere make sure you put usernamebox.Text and passwordbox.Text or whatever you have assigned...
7. Run your application and there you go. 


As always make sure you read all code before you use it :) - just because you think it comes from a secure location does not mean it is secure. Sites like virustotal help with that virus wise. If something private appears to be grabbed easily, you probably shouldn't use it :) 
