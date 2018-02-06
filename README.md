# ansible-tweetplugin
A callback plugin to tweet the result of provisioning with ansible.

## How to Use
1. Install **requests** and **requests_oauthlib** from pip. See "Installation" section of [README.rst](https://github.com/requests/requests-oauthlib/blob/master/README.rst).
```
$ pip install requests requests_oauthlib
```
1. Make **./callback_plugins** directory under the directory of playbook file, and put **tweet.py** in there.
1. Modify **Twitter API Info** section of tweet.py to yours. You can create tokens from the [Twitter Application Management](https://apps.twitter.com/).
```
# Twitter API Info
consumer_key="#YOUR_CONSUMER_KEY"
consumer_secret="#YOUR_CONSUMER_SECRET"
access_token_key="#YOUR_ACCESS_TOKEN_KEY"
access_token_secret="#YOUR_ACCESS_TOKEN_SECRET"
```
1.After the modify, tweets will send to your twitter accont as below.
<img src="https://pbs.twimg.com/media/DVLPEctV4AACT1e.jpg">

1.Enjoy!
