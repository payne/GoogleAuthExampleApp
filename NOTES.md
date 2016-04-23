following the notes at 
http://markgandolfo.com/blog/2016/01/05/gmail-gem-and-omniauth-google-oauth2-setup-in-a-rails-app/ 
helped.  
Specifically: "ensure you have Contacts Api, Google Plus and Gmail Api enabled to follow along with this post."

I also needed to `rm db/*3; rake db:setup` to start fresh.

After this, I was able to see the email address in the database.  I suspect I don't need all three of those APIs enabled... will experiment later.


