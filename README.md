# Fix this! - Todo system for the level editor ( ue4 plugin )

![fixthis](/Resources/ft2.png)

### About 

Fix this is a useful editor tool created for everyone who needs to leave text notes or todos in the level for the team members.

### Download

Unreal market place - [Fix This! - Download](https://www.unrealengine.com/marketplace/fix-this-todo-system-for-the-level-editor)

### Install

It's preferred to install the plugin as a project plugin ( not as an engine plugin ) into the folder `[MyProjet]/Plugins/`

### Workflow

**Level**
Click on the object in the scene, write a comment, choose priority and click *Create Task*. The note will be automatically aligned with the selected object. By default, a newly created note will stay selected, this can be disabled in the config section.

If no object is selected, a note will be created in front of the camera. 

**Blueprints**

Open the config section and set paths where the plugin should look for your blueprints assets. The default is `/Game/` which is the root folder but you should customize this according to your project. 

There are 2 ways of how to convert your comment into TODO. Firstly, every comment that starts with *TODO:* will be converted. e.g. `TODO: Fix this` You can define your own search word if needed in the config section. 

The second option how to convert comment to a task is to check *Color Bubble* in comment *Details* (see picture). In this case, you don't need to start your comments with the search word.

![fixthis](/Resources/color_bubble.png)

> Note: Search options will be improved in the next release. I'm working on a more user-friendly way of selecting folders. Also, I'm not providing recursiveness because this should be an expensive operation - speaking of big projects.

### Shortcuts
G - toggle show/hide of notes in the level

## See it in action
[![youtube tutorial](/Resources/ft_youtube.png)](https://youtu.be/5OI5-ibnpgU 
"YouTube")

## Support

If you have any issues or questions please log them in the [issues](https://github.com/alexhajdu/fix_this/issues) tab or hit me up on twitter [@alexhajdu](https://twitter.com/alexhajdu)

## Credits
Icons made by [Dave Gandy](http://fontawesome.io/) from [www.flaticon.com](https://www.flaticon.com/) is licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/)

