# fabric8's hubot slack

This is the [Hubot](https://hubot.github.com/) instance configured with a [Mattermost](https://about.mattermost.com/) adapter for use with Mattermost

## Configuration Variables  

_NOTE_ see [hubot base image](https://github.com/fabric8io/hubot-base) for extra plugin configuration variables

see hubot mattermost https://github.com/renanvicente/hubot-mattermost

### Example:  

from https://github.com/renanvicente/hubot-mattermost

	export MATTERMOST_ENDPOINT=/hubot/incoming # listen endpoint
	export MATTERMOST_CHANNEL=town-square # optional: if you want to override your channel
	export MATTERMOST_INCOME_URL=http://<your mattermost instance>:<port>/hooks/ncwc66caqf8d7c4gnqby1196qo # your mattermost income url
	export MATTERMOST_TOKEN=oqwx9d4khjra8cw3zbis1w6fqy # your mattermost token
	export MATTERMOST_ICON_URL=https://s3-eu-west-1.amazonaws.com/renanvicente/toy13.png # optional: if you want to override hubot icon
	export MATTERMOST_HUBOT_USERNAME="matterbot" # optional: if you want to override hubot name
	export MATTERMOST_SELFSIGNED_CERT=true # optional: if you want to ignore self signed certificate

