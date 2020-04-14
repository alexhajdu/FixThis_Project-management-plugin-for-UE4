# Fix this! - The advanced TODO system for C++ and Blueprints projects

![](/Resources/github_header.png)

# NOTE FROM THE AUTHOR

> I'm not making support for the plugin momentary. I'm just a one guy with work and family and this is my side project. This project gets funding from Epic Mega Grants and I'm hard working on the improved, stable and feature-full version. Repository is public, so you can follow my progress here. Please consider buying the plugin later. Apologies to you who are having some issues. Thanks for understanding. Alex

---

# About 

Fix this! is an advanced TODO system for both Blueprint and C++ projects. 

Leave visual notes right in the level for your teammates. Create todos from comments and keep track of all your comments in your whole projects. Get the whole picture of what needs to be done in your project. 

# Download

Unreal market place - [Fix This! - Download](https://www.unrealengine.com/marketplace/fix-this-todo-system-for-the-level-editor)

# Install

It's preferred to install the plugin as a project plugin ( not as an engine plugin ) into the folder `[MyProjet]/Plugins/`

# Workflow

## Level

Click on the object in the scene, write a comment, choose priority and click *Create Task*. The note will be automatically aligned with the selected object. By default, a newly created note will stay selected, this can be disabled in the config section.

If no object is selected, a note will be created in front of the camera. 

## Blueprints

Open the config section and set explicit paths where the plugin should look for your blueprints assets. The default is `/Game/` which is the Content root folder but you should customize this according to your project. 

There are 2 ways of how to convert your comment into TODO. 

1. Every comment that starts with *TODO:* will be converted. e.g. `TODO: My important task` You can define your own search word if needed in the config section. 

2. The second option how to convert comment to a task is to check *Color Bubble* in comment *Details* (see picture). In this case, you don't need to start your comments with the search word.

![](/Resources/color_bubble.png)

> Note: Definition of search paths will be improved in the next release! I'm working on a more user-friendly way of selecting folders. Also, I'm not providing recursiveness because this should be an expensive operation - speaking of big projects.

## Shortcuts
G - toggle show/hide of notes in the level

# See it in action

[![youtube how to convert blueprints to tasks](/Resources/ft_yt_bp.png)](https://youtu.be/YHrOzj2uNow 
"YouTube")

[![youtube how to create tasks in the level](/Resources/ft_youtube.png)](https://youtu.be/5OI5-ibnpgU 
"YouTube")

# Support

If you have any issues or questions please log them here in the [issues](https://github.com/alexhajdu/fix_this/issues) or hit me up on twitter [@alexhajdu](https://twitter.com/alexhajdu)

# Credits
Icons made by [Dave Gandy](http://fontawesome.io/) from [www.flaticon.com](https://www.flaticon.com/) is licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/)
