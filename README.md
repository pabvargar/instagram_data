# instagram_data
Create a Meta App which extracts user's data using API
# Create a Meta App

1. Go to [facebook apps](https://developers.facebook.com/apps) and sign-in with your facebook user:
2. Create an app with the following config
   ![pic](fb_1.png)
   ![pic](fb_2.png)
   ![pic](fb_3.png)
   ![pic](fb_4.png)
   ![pic](fb_5.png)

# Get User Token

1. Go to Basic Display and add a testing User
   ![pic](fb_8.png)
   ![pic](fb_9.png)
3. Log in Instagram with the testing user account, go to Setting, then to Apps & Websites and accept the invite to the app
   ![pic](fb_10.png)
   ![pic](fb_11.png)
4. Generate token and accept from the testing user instagram account
![pic](fb_12.png)
![pic](fb_13.png)
# Your first API call

Get the user profile with this URl (add your own access_token):
```
https://graph.instagram.com/me/media?fields=media_url&access_token=
```
Voilà!

[Documentation](https://developers.facebook.com/docs/instagram-basic-display-api/guides/getting-profiles-and-media)
