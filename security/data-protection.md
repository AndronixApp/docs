---
description: >-
  This will guide you through the cautions we here at Andronix take to keep your
  data in safe hands.
---

# Data Protection

## What happens to my data when-

### I register on Andronix?

Now here we can divide this into two separate sections, one for email/password authentication and the second for Google sign in. We try to minimize the storage of sensitive data on any for our servers at all given times. 

#### Email/Password Authentication

When you sign up using email and password on Andronix, we send your email and password to our server \(we use Google's [Firebase](https://firebase.com) for the backend of the app\). The email and password are all stored encrypted safely. **We do not store your emails in any for our databases,** which throws the possibilities to have breach in the database due to poor security rules. This also limits the possibility of us selling the actual data or in general spamming emails with promotional content.

#### Google sign-in

When using Google sign-in, the entire OAuth process is handled by [Firebase](https://firebase.com). We only have access to your **email** and your **profile picture** and nothing else. **We neither store your email or your profile picture on a separate database.** Your picture is fetched in real-time using Google's APIs.

### I do an in-app purchase?

If you buy Andronix Premium, your **email will be stored** on our severs for security and authentication purposes. 

Apart from Andronix Premium, any purchase you make **will not include any identifiable information**. Everything is referred via the Unique ID of the user, when signed in.

## Use of Analytics and Crashlytics

We use Google Analytics that comprises of Crashlytics. Analytics enables us to take a look at what users are using the most in the app **\*** and improve the UX of the app. Whereas Crashlytics helps us to identify the issues and crashes automatically before a user manually reports the crashes.

**We don't use the meta data is anyway other than improving the user-experience. It is not stored on our servers.**

**\***_This maybe include the user's course location, device metadata such as the Android version, model number and other hardware info. More info on that_ [_here_](https://support.google.com/analytics/answer/6318039?hl=en)_._

### 

