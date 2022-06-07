# instagram-insight

This project employs the  ***Instagram Graph API***

## Required Libraries
1.os
2.csv
3.requests
4.json
5.argparse
6.subprocess

## To execute:
1. Generate a *Facebook App* at developers.facebook.com 
2. Find *Graph API Tools* to procure the Access Token (https://developers.facebook.com/tools/explorer/)
3. Select User Token
4. Add the following permissions to access the Instagram Graph API
        *instagram_basic*
        *instagram_manage_comments*
        *instagram_manage_insights*
        *pages_read_engagement*
        *pages_show_list*
5. Generate the Access Token with 1 hour validity
6. Now copy the access token and Enter in **defines.py**
7. Copy your **Client ID** and **Client Secret Key** from the developers.facebook.com App
8. Now execute the ***debug_access_token.py*** file to check the connection to the  ***Graph API***
9. Now execute ***get_long_lived_access_token.py*** to get access token valid for 60 Days & Enter it in ***defines.py***
10. Now run ***get_uer_facebook_pages.py***  to get the **Facebook Page ID** & Enter this in ***defines.py***
11. Now run ***get_uer_instagram_account.py***  to get the **Instagram Account ID** & Enter this in ***defines.py***
12. Now Enter the Instagram Username you wish to fetch details of in the ***ig_username.csv*** file
13. Now run ***business_discovery.py*** to fetch the details of the usernames you entered in the ***ig_username.csv*** file
14. Now open the ***ig_business.csv*** newly created and verify for desired results
15. Now run ***media_discovery.py*** to fetch the details of the usernames you entered in the ***ig_username.csv*** file
16. Now open the ***ig_media.csv*** newly created and verify for desired results
17. Now Enter the Instagram Hashtag you wish to fetch Post of in the ***ig_hashtag_input.csv*** file
18. Now run ***hashtag_discovery_recent_media.py*** to fetch the details of the usernames you entered in the ***ig_hashtag_input.csv*** file
19. Now open the ***ig_hashtag_top_media.csv*** newly created and verify for desired results
20. Now run ***hashtag_discovery_top_media.py*** to fetch the details of the usernames you entered in the ***ig_hashtag_input.csv*** file
20. Now open the ***ig_hashtag_top_media.csv*** newly created and verify for desired results
