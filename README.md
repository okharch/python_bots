# Python Bot Automation Suite

A collection of versatile Python bots designed to monitor various information sources, automating tasks and delivering timely notifications about important events.

## Key Features
Background/Service Execution: Run bots as background processes or services for continuous operation.
Flexible Monitoring: Customize bots to watch a wide range of information resources (websites, APIs, data feeds, etc.).
Event-Driven Notifications: Receive instant updates about critical events directly within your preferred bot communication channels.
Python Power: Leverages Python's rich ecosystem for efficient development and customization.

### hello_time Bot

This bot offers a convenient way to keep track of the current time within a Telegram channel.

#### Features:

* On-Demand Time Updates: Send the /tell_time command to receive an immediate response with the current time.
* Customizable Intervals: Use the /test_time <interval_in_seconds> command to initiate regular time updates at your desired interval. For example, /test_time 300 would send time updates every 5 minutes.
#### Purpose:

Serves as a simple "Hello World" introduction to building Telegram bots.
Demonstrates the basics of command handling and timed updates for bots.
Getting Started:

1. Set up your Telegram bot token: Follow the instructions to create a new bot with BotFather on Telegram.
2. Install dependencies: pip install pyTelegramBotAPI datetime threading (or time if you prefer)
3. Configure and run the bot: Replace placeholders in the bot's Python code with your bot token and adjust any additional settings as needed.

