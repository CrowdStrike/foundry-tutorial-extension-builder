![CrowdStrike](/images/cs-logo.png#gh-light-mode-only)
![CrowdStrike](/images/cs-logo-red.png#gh-dark-mode-only)

[![CrowdStrike Subreddit](https://img.shields.io/badge/-r%2Fcrowdstrike-white?logo=reddit&labelColor=gray&link=https%3A%2F%2Freddit.com%2Fr%2Fcrowdstrike)](https://reddit.com/r/crowdstrike)<br/>

# Extension Builder tutorial Foundry app

> [!IMPORTANT]  
> To view this tutorial and import the app, you need access to the Falcon console.

This code is the result of doing the Falcon Foundry [Create a Detection Enrichment App with Foundry Extension Builder](https://falcon.crowdstrike.com/documentation/page/gbf78cc9/create-a-detection-enrichment-app-with-foundry-extension-builder) tutorial.

## Prerequisites

- Falcon Insight XDR or Falcon Prevent (one app)
- Falcon Next-Gen SIEM or Falcon Foundry (1+ apps depending on entitlement)

## Getting Started

1. [Download this repository as a zip file](https://github.com/CrowdStrike/foundry-tutorial-extension-builder/archive/refs/heads/main.zip).
2. [Log in to the Falcon console](https://falcon.crowdstrike.com/login?unilogin=true) and go to **Foundry** > **App manager**.
3. Click **Import app** and select the zip file you downloaded.
4. Click **Import**.

> [!TIP]
> If you get an error that the name already exists, change the name to something unique to your CID when importing the app.

## Links

This example uses the following CrowdStrike products:

* [Falcon Platform](https://www.crowdstrike.com/platform/)
* [Falcon Foundry](https://www.crowdstrike.com/platform/next-gen-siem/falcon-foundry/)

## Help

Please post any questions as [issues](https://github.com/CrowdStrike/foundry-tutorial-extension-builder/issues) in this repo, ask for help in our [CrowdStrike subreddit](https://www.reddit.com/r/crowdstrike/), or post your question to our [Foundry Developer Community](https://community.crowdstrike.com/groups/foundry-developer-community-82).

## Support

The foundry-tutorial-extension-builder repo is the resulting code from doing the Foundry Create a Detection Enrichment App with Foundry Extension Builder tutorial. While not a formal CrowdStrike product, foundry-tutorial-extension-builder is maintained by CrowdStrike and supported in partnership with the open source developer community.

## License

MIT, see [LICENSE](LICENSE).
