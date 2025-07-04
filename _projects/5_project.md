---
layout: page
title: TTRPG
description: a project with a background image
img: assets/img/1.jpg
importance: 3
category: fun
---

"As you all lay down to sleep for the first time in this strange place, you think about what the next day will bring. When the sun rises and you set out in the morning, will you be able to save anyone? Will you learn anything new? Will you become more powerful, more prepared? However, as the night passes and you awaken, it is not to the brightness of the sun. Your eyes are groggy and there is no sun to welcome you. You realize, then, that the night has not passed at all. It has only continued. There is no morning to greet you – only the eternal blackness of the sky with its swirling cosmos and the ever-looming presence of the moon, which at one point offered comfort to you as a light in the dark, but now feels more like a giant eye staring down at you, watching your failures." 

I'm currently working on designing my own TTRPG campaign based off of creations like Bloodborne, the Call of Cthulhu RPG, and D&D 5E Modules like "Curse of Strahd". Players will take control of Hunters that seek to cleanse the streets of sickly beasts in the early days of the scourge. Combat is heavily inspired by Bloodborne and will be fast moving and risky. It is based around a system of trade-offs. For example, spellcasters will find that their spells are more powerful and deal extra damage as their sanity dwindles. They become more linked to the arcane systems that govern magic but wreak havoc on their minds. As a result, they can deal high damage and even create spells, but are more vulnerable to instances that test their resolve and grip on reality. In melee combat, players may decide to take a risk and "parry" enemies. This offers the potential for players to deal critical damage if their parry works. If it doesn't, however, they leave themselves wide open and the enemy can take advantage of doing critical damage on them.

This system will make combat quick and dangerous but potentially very rewarding. With an optional mechanic to have player characters brought back to life after perishing in battle, DMs can also ensure that roleplay is a major part of the game. When picking characters, players can optionally choose a faction for their character to be a part of. The factions are written to have relationships with one another and with other aspects of the game world, offering plenty of prompts and inspiration for players to roleplay with each other and interact with the world. Within this system are series of mini-games or encouters, such as a masquerade party "Whodunnit", labyrinth mazes, mini-dungeons, puzzles, and more. This will offer new opportunities for players to try different styles of games and break up any monotony. 

Currently, I am writing background information about the factions and world and designing weapons for each faction to use.

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
