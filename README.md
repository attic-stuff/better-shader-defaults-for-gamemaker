# better shader defaults for gamemaker
#### use these instead of those !

the default shaders for gm kinda suck imo so i use these. to install them you will need to override the default shader text files each time gm updates. at publication time i am using the long term stable build so its all good.

to override them you will have to magellan on over to your gamemaker version's ``defaults`` directory. for example, on my machine the lts defaults directory looks like ``C:\Program Files\GameMaker-LTS\defaults``. i have no idea where that directory is on mac or linux so if you're using those glhf. the important thing on windows is that you are in program files not program data.

once you do find that folder there are two text files: ``fshader.txt`` and ``vshader.txt``—override those two knuckleheads with the same-named text files in this repo.

these defaults include **vv_pos**, a varying that passes x y and depth from the vertex shader to the fragment shader. very useful for things for you probably.

![showoff](https://github.com/attic-stuff/better-shader-defaults-for-gamemaker/blob/main/showoff.png)

now when you right-click the asset browser to make a new shader friend, yours will look like the good side and not the bad side.

you're welcome, cowboys.
