# arxiv_slack

This system utilizes ChatGPT to summarize arXiv papers and notify Slack.
I used [Google Cloud Platform(GCP)](https://cloud.google.com/?hl=ja) for running this system.

## Caution
1. I hid the API key in the main.py. Get the your API key in Official.
1. This code is for running in local env. If you deploy this for GCP, change the comment out in `#def main(event, context)`:
1. if you chose higher `num_papers`, get the billing.

[Reference](https://zenn.dev/ozushi/articles/ebe3f47bf50a86)