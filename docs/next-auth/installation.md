---
layout: default
parent: Next-Auth
title: Installation
nav_order: 1
has_children: false
---

## Installation

In order to be able to use NextAuth in your webapp you need to collect your credentials from the providers you want to integrate into your application.

# Google

1. Visit the Google [Developer Console](https://console.cloud.google.com/apis/credentials?project=nextjs-boilerplate-425602) and sign in with your startup Google account.
1. If you don't have an existing project, you'll need to create a new one. Click on the project dropdown menu at the top of the page, then select "New Project." Follow the prompts to set up your new project.
1. After enabling the API, navigate to the "Credentials" section in the left sidebar. Click on the "Create credentials" dropdown and select "OAuth client ID."
1. If you haven't configured the OAuth consent screen for your project yet, you'll be prompted to do so. Select "External" if you want anybody with a Google account to access your application. Follow the instructions to configure the required information, such as your application's name, logo, and authorized domains.
1. Then navigate to the "Credentials" section in the left sidebar. Click on the "Create credentials" dropdown and select "OAuth client ID."
1. When creating OAuth client credentials, you'll need to choose the application type. For web applications, select "Web application."
1. You'll need to specify the redirect URIs that your application will use for OAuth authentication. Make sure to include the correct redirect URIs used by your Next.js application.
1. After creating OAuth client credentials, Google will provide you with a client ID and client secret. These are the values you'll use for GOOGLE_ID and GOOGLE_CLIENT_SECRET in your Next.js application.
1. Ensure that you store your client ID and client secret securely. It's common practice to use environment variables to store these values securely in your application.

- [x] Video walkthrough: [1](https://www.google.com/search?q=how+to+setup+google+login+with+next-auth&rlz=1C1ONGR_deCH1078CH1078&oq=how+to+set+uo+google+login+with+next-&gs_lcrp=EgZjaHJvbWUqCQgBECEYChigATIGCAAQRRg5MgkIARAhGAoYoAHSAQkxMTU5OWowajeoAgCwAgA&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:064b82b2,vid:k1TL-AzavvY,st:0)

# Twitter

...

# NextAuth Integration

[NextAuth 5 Integration](https://blog.stackademic.com/authentication-in-next-js-with-auth-js-nextauth-5-b74e3ae18ab8)
[Auth in server and client sides](https://judy-webdecoded.medium.com/how-i-integrated-authentication-next-auth-v5-in-my-nextjs-14-application-0d57f84cf4ac)



