---
title: Overview of Bot templates for Azure Bot Service | Microsoft Docs
description: Learn about Bot templates for Azure Bot Service.
keywords: Bot Framework, Azure Bot Service, continuous integration
author: Toney001
manager: rstand
ms.topic: bot-service-article
ms.prod: botframework
ms.service: Azure Bot Service
ms.date: 3/21/2017
ms.reviewer:
#ROBOTS: Index
---

#Overview of bot templates

Bot templates are the quickest way to get your first bots up and talking. They are based on Azure Bot Service and is powered by <a href="https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference" target="_blank">Azure functions</a>. 

There's no need to use a desktop code editor. The online Azure editor is all you need. Keep in mind, though, that the Azure editor does not allow you to add new files or rename and delete existing files. 

If you need to manage the files, you should set up [continuous integration](bot-framework-azure-continuous-integration.md), which would let you use the IDE and source control of your choice (for example, Visual Studio Team, GitHub, and Bitbucket). Continuous integration will automatically deploy to Azure the changes that you commit to source control. Once you have set up continuous integration, you can [debug your bot locally](bot-framework-azure-debug.md).

> [!NOTE]
> After configuring continuous integration, you will no longer be able to update the bot in the Azure editor.

## Bot templates to get you started
Azure Bot Service has five bot templates to get you started creating your bots. If you're new to bots, start with the basic bot and then grow your bot coding skills from there. 

### Basic bot

Use the [basic bot template](bot-framework-azure-basic-bot.md) to create a simple bot. You'll learn the basics about managing a conversation flow by using dialogs that respond to user input. 

### Form bot

Use the [Form bot template](bot-framework-azure-form-bot.md) to create a guided conversation to collect user input. A Form bot for buying a bicycle, for example, might ask the user questions like "What terrain do you plan on riding over?" Or "What size tires?" After the user answers the questions, various models  of bicycles are displayed.

### Language understanding bot

Use the [language understanding bot template](bot-framework-azure-natural-language-bot.md) to create a bot that uses natural language models (LUIS) to understand user intent. For example, if a user asks the bot, "Get environmental news about Montana," your bot needs to understand that the user is asking for environmental and not, say, political news about only one specific state.

### Proactive bot

Use the [Proactive bot template](bot-framework-azure-proactive-bot.md) to create a bot that alerts the user to events. For example, if a user has ordered a pizza, the bot will alert the user when the pizza is ready to pick up.
 
### Question and answer bot

Use the [Question and Answer bot template](bot-framework-azure-question-and-answer-bot.md) to create a bot that displays question and answer pairs based upon a link you supply to your company's FAQ. When a user asks question to your bot, it responds with answers from the content that was displayed in the FAQ. 

## Next steps

Review the following articles in this section to learn more about building bots using the Azure Bot Service.

- Follow a [step-by-step tutorial](bot-framework-azure-getstarted.md) so that you can quickly build and test a simple bot.
- [Manage conversation flow using dialogs](bot-framework-dotnet-howto-manage-conversation-flow.md)

If you encounter problems or have suggestions regarding Azure Bot Service, 
see [Support](resources-support.md) for a list of available resources. 