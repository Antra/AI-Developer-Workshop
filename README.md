# Welcome 

Welcome to the one day AI Developer Workshop. This material is based on the four day [Cloud AI Bootcamp](https://azure.github.io/LearnAI-Bootcamp/).

In this workshop we will focus on hands-on activities that develop proficiency in AI-oriented services such as Azure Bot Services, Azure Search, and Cognitive Services. These labs assume an introductory to intermediate knowledge of these services, and if this is not the case, then you should spend the time working through the pre-requisites.

The structure is intended to be hands-on. Each lab should be able to be run in relative isolation, so as long as **appropriate pre-requisites are met**, an individual should be able to complete a given lab without needing to complete the others.

# Goals

The goal of this workshop is to provide a kick-start to individuals who need to develop deeper proficiency with the range of the Microsoft Cloud AI platform. This is not "Getting Started with..." the various services and assume a 100-200-level familiarity with the products prior to getting started.

Most challenges observed by customers in these realms are in stitching multiple services together. As such, where possible, we have tried to place key concepts in the context of a broader example. 

At the end of this workshop, you should be able to:

- Understand how to configure your apps to call Cognitive Services
- Build an application that calls various Cognitive Services APIs (specifically Computer Vision)
- Understand how to implement Azure Search features to provide a positive search experience inside applications
- Configure an Azure Search service to extend your data to enable full-text, language-aware search
- Build, train, and publish a LUIS model to help your bot communicate effectively
- Build an intelligent bot using Microsoft Bot Framework that leverages LUIS and Azure Search
- Effectively log chat conversations in your bot
- Perform rapid development/testing with Ngrok and test your bots with unit tests and direct bot communication
- Effectively leverage the custom vision service to create image classification services that can then be leveraged by an application

# Pre-requisites

This workshop is meant for an AI Developer on Azure. Since this is only a short workshop, there are certain things you need before you arrive.

Firstly, you should have some previous exposure to Visual Studio. We will be using it for everything we are building in the workshop, so you should be familiar with [how to use it](https://docs.microsoft.com/en-us/visualstudio/ide/visual-studio-ide) to create applications. Additionally, this is not a class where we teach you how to code or develop applications. We assume you have some familiarity with C# (intermediate level - you can learn [here](https://mva.microsoft.com/en-us/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Lvld4EQIC_2706218949)), but you do not know how to implement solutions with Cognitive Services. 

Secondly, you should have some experience developing bots with Microsoft's Bot Framework. We won't spend a lot of time discussing how to design them or how dialogs work. If you are not familiar with the Bot Framework, you should complete [this tutorial](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-sdk-quickstart?view=azure-bot-service-4.0) prior to attending the workshop.

Thirdly, you should have experience with the portal and be able to create resources (and spend money) on Azure. We will not be providing Azure passes for this workshop.

Finally, before arriving at the workshop, we expect you to have completed [1_Setup](./lab01.1-computer_vision/1_Setup.md) along with the configuring the following for Custom Vision:
  * Training API Key: The training API key allows you to create, manage and train Custom Vision project programmatically.
    * You can obtain a key by creating a new project at https://customvision.ai and then clicking on the “setting” gear in the top right. 
 


# Agenda

Please note: This is a rough agenda, and the schedule is subject to change pending class activities and interaction.

- 8-9 (optional): Setup assistance
- 9-10: Introduction and Context for Cognitive Services and Bots
- 10-12: [Lab 1.1: Simplifying Cognitive Services App Development using Portable Class Libraries][lab-cogsrvc-301]
- 12-13: Lunch
- 13-13:30: [Lab 1.2: Creating an Image Classification Application using the Custom Vision Service I][lab-cogsrvc-321]
- 13:30-14:30: [Lab 1.5: Developing Intelligent Applications with LUIS][lab-cogsrvc-341]
- 14:30-15:30: [Lab 2.1: Developing Intelligent Applications with Azure Search][lab-azsearch-301]
- 15:30-17:00: [Lab 2.2: Bulding Intelligent Bots][lab-intelbot-301]

Extra labs:

- [Lab 1.3: Creating an Image Classification Application using the Custom Vision Service II][lab-cogsrvc-322]
- [Lab 1.4: Creating an Image Classification Application using the Custom Vision Service III][lab-cogsrvc-323]
- [Lab 2.3: Log Chat Conversations in your Bot][lab-intelbot-311]
- [Lab 2.4: Testing your Bot][lab-intelbot-321]

[lab-cogsrvc-301]: ./lab01.1-computer_vision/0_README.md
[lab-cogsrvc-321]: ./lab01.2_customvision01/0_README.md
[lab-cogsrvc-322]: ./lab01.3_customvision02/0_README.md
[lab-cogsrvc-323]: ./lab01.4_customvision03/0_README.md
[lab-cogsrvc-341]: ./lab01.5-luis/0_README.md
[lab-azsearch-301]: ./lab02.1-azure_search/0_README.md
[lab-intelbot-301]: ./lab02.2-building_bots/0_README.md
[lab-intelbot-311]: ./lab02.3-logging_chat_conversations/0_README.md
[lab-intelbot-321]: ./lab02.4-testing_bots/0_README.md

