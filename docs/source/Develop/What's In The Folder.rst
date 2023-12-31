What's In The Folder?
======================

📂 There's a lot of folders and files under the root folder, 
here's the explanations of them!

.. note:: 
    🔞: Some folders/files are not in the github repository,
    as they are generated or created in your local computer.
    These kind of folders/files will be tagged
    with a 🔞 because we don't show it to the public.  
    
    🐶: This is a cute dog.

.git🔞
____________________
Contains files generated by `git <https://git-scm.com/>`_.

.github
____________________
Contains configs about the github repository.

.godot🔞
____________________
Contains files generated by godot engine.

.out_android🔞
____________________
Export folder for android platform.  
Might contains ``dicolo!.apk`` and ``dicolo!.apk.idsig``

.out_linux🔞
____________________
Export folder for linux platform.  
Might contains ``dicolo!.x86_64``

.out_windows🔞
____________________
Export folder for windows platform.  
Might contains ``dicolo!.exe``

.security
____________________
Contains the debug and release key for Android export.

- debug: ``debug.keystore``
  
  - user: ``androiddebugkey``, password: ``android``

- release: ``dicolo.keystore``
  
  - user: ``dicolo``, password: ``dicolo!``

.. note:: 
    These .keystore files path, user and password are stored at 
    ``.godot/export_credentials.cfg``, **differ** from 
    normal export config file `export_presets.cfg`_!

.src_file
____________________
Contains the original (source) files of the image and other assets, 
for example: ``.xcf`` ``.psd`` ``.svg``.

addons🔞
____________________
This folder contains the extensions of godot engine.  
Currently we **don't use any extension**, but you can add some extensions 
that are not depended on by the game script, 
like `godot-git-plugin <https://github.com/godotengine/godot-git-plugin>`_.

audio
____________________
Contains all the sound files in the game (exclude the beatmap music).

data
____________________
Contains scripts for loading/saving data or configs, 
and language files (``.csv``, ``.translations``).

map
____________________
Contains internal beatmaps, but remember to be aware of copyright!

scene
____________________
Contains all the scene files (``.tscn`` or ``.scn``), and theres scripts (``.gd``).

visual
____________________
Contains all the "visual" files --- includes:

- font (``.ttf``) and font settings.
- theme
- icon
- background
- texture
- ui_icon
- shader (``.gdshader``)

website
____________________
Contains the webpage related files.

.gitattributes
____________________
A git config.

.gitignore
____________________
A git config, which listed all the file that git should ignore.  
This defines those 🔞 contents.

CNAME
____________________
A webpage config that defines the address of dicolo! website.

export_presets.cfg
____________________
The export config in godot, you should edit it in godot editor.

index.html
____________________
The webpage.

LICENSE
____________________
The license of this project.

project.godot
____________________
The project settings in godot.

README.md
____________________
The readme file shows in github repository page.