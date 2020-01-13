# Twitter_Toolkit
Query twitter using standard and premium API

![Using the Twitter_Toolkit Premium](link-to-image)

Provides access to both the Twitter Free standard API and the subscription based Premium API.
Currently set up to provide search only functionality although could be extended to allow posting tweets and control of a user account.
There a a few differences in formatting queries and available parameters between standard and premium which for now I'm relying on any user checking the twitter documentation.
It requires setting up a developer account with Twitter which is a bit of a overhead but you need  to an APIKey and APISecretKey to do any searching.
I can provide API keys for testing purposes of both the standard and premium (for which I have a subscription (paid by Buro Happold)).

Longer term users will need their own APIKey and APISecretKey (Consumer API keys)
For the Free standard API you can register here as a developer: 
https://developer.twitter.com/en/apply-for-access
- you first need a tiwtter account to login.
Getting a premium account is a little more lengthy and costly but a Sandbox is availble free. Applications will be reviewed by Twitter this can take a few days.

The Twitter documentation is quite frustring as the Standard and Premium search differ significantly !
This is the start point https://developer.twitter.com/en/docs/tweets/search/overview

As mentioned above for now the toolkit depends on users being familar with formatting queries longer term we could BHoM wrap this into something simpler if that seems the best course of action.


