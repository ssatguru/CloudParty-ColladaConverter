# CloudParty-ColladaConverter
An application to help Blender users develop animations for CloudParty's default avatars. 

It fixes an issue with the Blender Collada Import/Export plugin.The plugin alters the bone roll of the skeleton on import/export and because of this any animations created, using this skeleton, does not play correctly on the original CloudParty skeleton. 
This application corrects the animation by "undoing" the bone roll introduced by the plugin. 

Implemented at http://ssatguru.appspot.com/CloudParty/b2c.html
