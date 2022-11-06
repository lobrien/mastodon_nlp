# Sentiment Analysis of Mastodon Toots using OpenAI

This is just a proof of concept: 

* Authenticate with Mastodon
* Pull timeline
* Extract seq of toot content
* Write a sentiment-analysis prompt, hoping for zero-shot results
* Map content 

Requires:

* `Mastodon.py` package from pip (conda-forge version is obsolete)
* `openai` package 

Conda environment in `environment.yml`.

You'll need to set the following environment variables:

* `OPENAI_KEY` - your OpenAI API key
* `MASTODON_BASE_URL` - your Mastodon instance URL
* `MASTODON_USER` - your Mastodon username
* `MASTODON_PASS` - your Mastodon password

[MIT License](LICENSE)