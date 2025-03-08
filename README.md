![Hackathon Logo](docs/images/hackathon.png?raw=true "Hackathon Logo")

# Sitecore Hackathon 2025

- MUST READ: **[Submission requirements](SUBMISSION_REQUIREMENTS.md)**
- [Entry form template](ENTRYFORM.md)

### ⟹ [Insert your documentation here](ENTRYFORM.md) <<

## Team name

⟹ ByteBuild

## Category

⟹ AI-driven Content Language Translation

## Description

⟹ Write a clear description of your hackathon entry.

- The main purpose of this module is to make the jobs of Content Author easier, as instead of manually going back and forth to browser to translate content, they can do it with just one-click.
- There are many problems that our module solves:

  - Significantly nulifies Human Error
  - Reduces Human effort for a simple task
  - Ensures that translation is grammatically correct and culturally appropriate
  - Also, adaptng any expressions or terminology to reflect local customs, and idioms.
  - Preserve the meaning of the original Content.
  - 

## Video link

[](https://github.com/Sitecore-Hackathon/2025-ByteBuild/blob/main/ENTRYFORM.md#video-link)

⟹ Provide a video highlighing your Hackathon module submission and provide a link to the video. You can use any video hosting, file share or even upload the video to this repository. _Just remember to update the link below_

⟹ [Replace this Video link](https://github.com/Sitecore-Hackathon/2025-ByteBuild/blob/main/ENTRYFORM.md#video-link)

## Pre-requisites and Dependencies

[](https://github.com/Sitecore-Hackathon/2025-ByteBuild/blob/main/ENTRYFORM.md#pre-requisites-and-dependencies)

⟹ Does your module rely on other Sitecore modules or frameworks?

- Sitecore Powershell Module-7.0

## Installation instructions

1. Make sure you have installed all the pre-requisites
2. Download the package _AutoTranslationSingleItem.zip_ from the Github Repository.
3. Go to the Sitecore Dashboard > Development Tools > Installation Wizard, and Install the downloaded package.

### Configuration

1. You have to create an account in Groq cloud and then generate a new api key and paste it in CMS, to run this.

## Usage instructions

To use this module, please follow the below steps:

- Go to "/sitecore/system/Modules/PowerShell/Settings/Groq AI API Key/API Key" path and add you **Groq AI API key.**
- Make sure you have atleast 1 language installed, apart from your default.
- Right-click on any item that you want to translate, and **Scripts > Translate Item**
- Once the script has been executed, you can change the language of the item and Voila! content has been translated.
