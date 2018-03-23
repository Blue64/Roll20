# Roll20

I have been inspired by getting everything ready for a neat little organizing session, I've been working on this GitHub Repository for the last 8 Hours, I'm going to first go over a few things really quick, the Macros have some lines such as

```
# Token Action: √
# Macro Bar: X
# Sub-Macro: X
```

The lines that Start like that aren't a part of the Macro, those are the Descriptors, to help you identify the way to use the Macro,

- Token Action denotes that it's using the Variable `@selected|` which requires a selected Token, or something similar, it's going to be looking up a Variable from the attached Character Sheet

- Macro Bar is for the actions not linked to any specific Token features, it's a bit of a Free-Use Macro, such as a Group Skill Check, or the Group AC or the Group HP, these are likely explicit uses, as I have not yet learned how to do such a large scale as a Variable, or it's a simple little Macro, such as the `/talktomyself` command.

Note: the above two tasks can usually be accomplished by setting up a separate Macro in the Macro List, especially the Token Macros, as those allow you to add it to any Token that Player targets, if this is undesirable, simply call the Macro from the Player's Character Sheet.

- Sub-Macro is to note that it's supposed to be called by another Macro, such as the Proficiency Macros.

I was having problems sharing my Codes for Roll20, so here I am once again drawn to GitHub.

This Repository contains the variety of Macros from my Campaign (Dungeon Fantasy)

You'll likely encounter HTML Code for bypassing the Parser

You might also find JavaScript Code, as the site utilizes such things.

Like most Repositories, if you encounter any problems with my Codes, post a Bug Report in the Issues section.

I'm using the MIT License because it sounded the most permissive without it holding myself liable for derivatives of my work, but I do at least ask for credit where Credit is due, some of this stuff I just kinda patchwork stitched together and forced it to function, others I might have been inspired by someone else, or it might have been their idea at some point, but I probably tried to tweak it somewhere along the line and can't guarantee that it's the same as the original.
