# My Obsidian Setup Guide
## Overview
I have been getting quite a bit of people reaching out, asking how to replicate my [Obsidian](https://obsidian.md) setup. I figured I would make a quick guide on how to do it.

![UI](/images/main.png) 

### Gif Demo
![Demo video](/images/main.gif) 


## Getting Started
### Step 1: Install Obsidian and Create a Vault
First things first, you need to install Obsidian. You can download it [here](https://obsidian.md). Once you have it installed, create a new vault. This is where all of your notes will be stored.

### Step 2. Install the Cupertino Theme
The Cupertino theme is a theme that I have been using for a while now. It is a clean, minimalistic theme that is easy on the eyes. To install it, follow these steps:
1. Go to `Settings` -> `Appearance` -> `Themes` and click on `Manage`.
2. Search for `Cupertino` and click on `Install & User`.

![theme](https://github.com/aaaaalexis/obsidian-cupertino/blob/main/img/hero.png?raw=true)

**GitHub Link**: https://github.com/aaaaalexis/obsidian-cupertino/tree/main


### Step 3: Install the Community Plugins
**Note**: I have included a folder in the project called `04 Plugins` that contains all the plugins that I use. You can download them from there but they may be out of date. I would reccomend downloading them from the community store in Obsidian or from their GitHub Repos that are linked.

In Obsidian, go to `Settings` -> `Community plugins` and install the following plugins:
#### 1. Autofit Tabs
![Demo video](/images/autofit-demo.gif) 

**Description**: This plugin will automatically resize the width of the tabs to fit the title of the document and the icon.

**GitHub Link**: [Autofit Tabs](https://github.com/bwya77/autofit-tabs)

**Custom Settings**: Using all default settings

---

#### 2. Dynamic Outline

![dynamic outline](https://github.com/theopavlove/obsidian-dynamic-outline/raw/master/assets/demo-usage.gif)

**Description**: Adds a customizable GitHub-like floating table of contents to Obsidian.

**GitHub Link**: [Dynamic Outline](https://github.com/theopavlove/obsidian-dynamic-outline/)

**Custom Settings**: Using all default settings

---

#### 3. Editing Toolbar

![dynamic outline](https://github.com/PKM-er/obsidian-editing-toolbar/raw/master/editing-toolbar-demo.gif)

**Description**: Provides a toolbar similar to MS-Word，and adds a minimal and user friendly text editor modal for a smoother writing/editing experience

**GitHub Link**: [Editing Toolbar](https://github.com/PKM-er/obsidian-editing-toolbar)

**Custom Settings**: I have the editing toolbar theme set to 'glass'

---

#### 4. Obsidian Hider

**Description**: Enables you to hide certain parts of the Obsidian UI

**GitHub Link**: [Obsidian Hider](https://github.com/kepano/obsidian-hider)

**Custom Settings**: Hide Properties in Reading View is enabled

---

#### 5. Settings Search

**Description**: Adds a search bar to Obsidian.md's settings

**GitHub Link**: [Settings Search](https://github.com/javalent/settings-search)

**Custom Settings**: Using all default settings

---

#### 6. Smart Typography

**Description**: Automatically converts straight quotes to curly quotes, straight apostrophes to curly apostrophes, and three dots to an ellipsis.

**GitHub Link**: [Smart Typography](https://github.com/mgmeyers/obsidian-smart-typography)

**Custom Settings**: Reference the picture below

![settings](/images/smarttypographySettings.png)


---

#### 7. Style Settings

**Description**: A dynamic user interface for adjusting theme, plugin, and snippet CSS variables within Obsidian

**GitHub Link**: [Style Settings](https://github.com/mgmeyers/obsidian-style-settings)

**Custom Settings**: I am currently not setting anything with this plugin but its nice to have as as themes and plugins are updated, more settings may appear. 

---

#### 8. Collapsible Code Blocks

![Collapsible Code Blocks](https://github.com/bwya77/collapsible-code-blocks/blob/main/images/demo.gif?raw=true)

**Description**: Makes code blocks collapsible in reading and edit view as well as enabling scroll-able code blocks.

**GitHub Link**: [Collapsible Code Blocks](https://github.com/bwya77/collapsible-code-blocks)

**Custom Settings**: Using all default settings


---

#### 9. Dynamic Editor Width
This plugin is pending approval to the community store, for now you will have to install it manually. To install it manually, follow these steps:
1. Go to your Obsidian vault folder and navigate to `.obsidian/plugins`. (this is a hidden folder, you may need to enable hidden folders in your file explorer)
2. Create a new folder called `dynamic-editor-width`
3. Paste the `main.js`, `styles.css` and `manifest.json` file from the Releases in GitHub

![Dynamic Editor Width](https://github.com/bwya77/dynamic-editor-width/blob/main/images/demo.gif)

**GitHub Link**: [Dynamic Editor Width](https://github.com/bwya77/dynamic-editor-width)

**Custom Settings**: Default Editor width: 20

---

### Step 4: Install the Custom CSS Snippets
In Obsidian, go to `Settings` -> `Appearance` -> `CSS snippets` and open your snippets folder. Paste the snippets from this projects `snippets` folder into your snippets folder and enable them. 


### Step 5: Settings and Colors
In Obsidian, go to `Settings` -> `Appearance` and udner `interface` disable `show ribbobn.`
Next, go to `Settings` -> `Appearance` -> `Accent Color` and set it to 205, 86, 84

### Step 6: Fonts
Download all the font file in the projects `Fonts` folder and install it on your computer. Restart Obsidian then go to `Settings` -> `Appearance` -> set the interface and text font to `Bear Sans UI` and the monospace font to `IBM Plex Mono`

