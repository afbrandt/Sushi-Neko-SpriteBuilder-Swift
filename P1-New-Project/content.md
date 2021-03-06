---
title: Create a new project in SpriteBuilder
slug: new-project
---

> [action]
> Let's start the work on our game by creating a new SpriteBuilder project:
>
> ![image](./SpriteBuilder_New_Project.png)
>
> Name your new project “SushiNeko” and change the Primary Language to Swift. Once the project is created, open Finder and take a look at the folder structure of your project. If you can't find your project in Finder, search for it using Spotlight at the top right of your screen.

The folder structure should look something like this:

![image](./SpriteBuilder_Filesystem.png)

SpriteBuilder created a new folder (SushiNeko.spritebuilder). Inside it are a SpriteBuilder project (SushiNeko.ccbproj) and a new Xcode project (SushiNeko.xcodeproj).

The default SpriteBuilder project comes with one scene (MainScene.ccb). Your empty project should look like this:

![image](./SpriteBuilder_Empty_Project.png)

#Testing your setup

Let’s make sure everything was generated correctly. Click the publish button (on left side of the toolbar) in SpriteBuilder:

![image](./SpriteBuilder_Publish.png)

Now open SushiNeko.xcodeproj to view the project in Xcode. Run this on the iPhone simulator and verify it shows the “SpriteBuilder” message:

![image](./Simulator_New.png)

Congratulations! We are now ready to get started!
