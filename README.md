# RuneLite Notification Forwarder for ntfy.sh

## Introduction

This plugin is designed to forward notifications from the RuneLite client to your preferred notification system using [ntfy.sh](https://ntfy.sh/).

`ntfy.sh` is a versatile and lightweight notification tool that sends push notifications directly to your devices. It supports various notification platforms, including Pushover, Pushbullet, and simple SMTP for email, allowing you to receive important alerts wherever you are.

## Prerequisites

- RuneLite client with plugin installed.
- ntfy.sh topic name chosen, for example "skeldoor-lootdrop-notifcations"
- App of your chosen system installed and configured to subscribe to your topic, see [here](https://docs.ntfy.sh/subscribe/phone/)

## Configuration

To utilize this plugin, users must configure it with their unique `ntfy Topic` and, if self hosting ntfy, the `ntfy URL`.

### ntfy Topic

`ntfyTopic` is a mandatory configuration parameter. It is the topic to which ntfy.sh will send notifications.

### ntfy URL (Optional)

For users who choose to self-host their ntfy.sh instances, the `ntfyURL` configuration parameter must be set. `ntfyURL` should point to the user's self-hosted ntfy.sh server.

For users who do not self-host, probably most people, this parameter can be ignored.
