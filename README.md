# Publora for Antigravity

Publora publishes and schedules social media posts. With this plugin your Antigravity agent can write a post, check which accounts you have connected, save a draft, schedule it, or publish it on LinkedIn, X, Instagram, Threads, TikTok, YouTube, Facebook, Bluesky, Mastodon and Telegram.

## What you need

A Publora account with at least one connected social account. You can [register for free](https://publora.com/register) and connect accounts in the [dashboard](https://app.publora.com/dashboard).

The free Starter plan includes 3 social accounts, 15 posts a month, 3 scheduled posts at a time and scheduling up to 7 days ahead. It covers every network except X, which needs a paid plan. See [pricing](https://publora.com/pricing).

## Setup

Install the plugin from the Antigravity Marketplace, or from GitHub:

```bash
agy plugin install https://github.com/publora-team/antigravity-publora
```

Then sign in. In Antigravity CLI, run `/plugin`, expand publora under **Installed** and choose **Sign in**. In the Antigravity App, open **Customizations > Installed**, find Publora under **MCP Servers** and click **Authenticate**. Finish signing in to Publora in your browser and paste the authorization code when asked.

The plugin signs in with OAuth, so you don't need an API key.

## What's included

The Publora MCP server at `https://mcp.publora.com/mcp`, and nine skills that hold each network's rules:

| Skill | Use it for |
|---|---|
| `linkedin-post` | Text, images, video, PDF documents and @mentions |
| `linkedin-analytics` | Impressions, reactions, comments and follower growth |
| `x-post` | Posts and threads, split automatically past 280 characters |
| `instagram-post` | Images, carousels, Reels and Stories |
| `threads-post` | Posts, connected chains, carousels and reply control |
| `tiktok-post` | Videos, carousels, privacy and interaction settings |
| `bluesky-post` | Posts up to 300 characters, images and video |
| `telegram-post` | Channel and group posts through your bot |
| `social-post` | YouTube, Facebook Pages and Mastodon |

## Try it

- Show which social accounts are connected to my Publora workspace
- Write a LinkedIn post about the latest change in this repo and save it as a draft
- Schedule this announcement for LinkedIn and Bluesky tomorrow at 10:00 my time

Antigravity asks for your approval before it runs an MCP tool, unless you have changed that in your permission settings. Read the tool call before you approve it, because a post that has been published goes out to your audience.

## Uninstall

```bash
agy plugin uninstall publora
```

This removes the plugin from Antigravity. Your social accounts stay connected in Publora.

## Help

- Setup and troubleshooting: [docs.publora.com/mcp/troubleshooting](https://docs.publora.com/mcp/troubleshooting)
- Support: [support@publora.com](mailto:support@publora.com)
- [Privacy policy](https://publora.com/privacy) and [terms](https://publora.com/terms)

MIT licensed.
