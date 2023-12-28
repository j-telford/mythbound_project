# The Mythbound Project

## Overview
The Mythbound Project is a multifaceted community initiative that encompasses web development, bot integration, and content automation. It's designed to provide a seamless and dynamic experience for its users by leveraging various technologies and services.

## Components
1. **Website (https://project.mythbound.online):**
   - The project includes a dedicated website accessible via [https://project.mythbound.online](https://project.mythbound.online). This website serves as the central hub for project information and interaction.

2. **Discord Bot:**
   - A Discord bot is a vital part of the project, capable of performing various tasks and integrations within Discord servers.

3. **Web App (Bot Portal - https://botportal.mythbound.online):**
   - The project's web app, known as the Bot Portal, is accessible via [https://botportal.mythbound.online](https://botportal.mythbound.online). This portal acts as a control panel for managing and configuring the Discord bot.

## Functionality
- **Discord Bot Integration:**
  - The Discord bot integrates with your Discord server to provide specific features:
    - It scrapes your Twitter profile for the latest tweets and posts links to them in a designated channel.
    - It scrapes your Instagram profile for the latest posts and shares links to them in a designated channel.
    - It monitors an RSS feed from your website and posts links to new articles in a specified channel.
  - The bot performs these tasks automatically at regular intervals (e.g., every 4 hours) while avoiding duplication.

- **Database Management:**
  - The project includes a MySQL database named "discord_bot_social_cache" with three tables: RSS, Twitter, and Instagram. These tables store links to posts, tweets, or articles to avoid duplicate postings.

- **Message Processing:**
  - The bot processes messages within Discord servers to:
    - Convert inline date commands (!date:YYYY-MM-DD) into Discord timestamps and replace the original message.
    - Convert inline time commands (!time:HHMM) into Discord timestamps.
    - Convert role mentions (!role:role_name) into @mentions, replacing the original message.

## Project Stages
- Development of the project occurs in stages:
  - A "dev" branch is created from the "main" branch.
  - Sub-branches are created for different project parts: Website, Web App, Bot, and Database.
  - Features are developed individually within their respective sub-branches.
  - Once features are complete, they are merged into their parent branches.
  - The project moves from alpha to beta release stages after all parts are merged into the "development" branch.

## Time Scale
- The project is expected to progress throughout most of 2024 to reach its first beta release.

## Future Updates
- The project's README will be updated with more comprehensive information in the near future.

The Mythbound Project represents a comprehensive and innovative community effort that integrates web development, automation, and Discord bot functionality to enhance user experiences across multiple platforms. It's a testament to your dedication to creating a dynamic and engaging community space.

