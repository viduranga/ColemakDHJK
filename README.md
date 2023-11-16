# Colemak DHJK

##  Why?
Colemak DHJK is a sensible variation of the Colemak DH layout which makes two key changes.

1. The original Colemak DH layout places J key on the top row and K key on the bottom row. While this is completely fine for regular use, when you are a vim user, this feels very counter intuitive. It makes much more sense to have J key (which is line down key in vim) on the bottom row; and to have K key (which is the line up key in vim) on the top row. Colemak DHJK does exactly this by swapping the J and K keys on Colemak DH layout

![image](https://github.com/viduranga/ColemakDHJK/assets/8828757/46bab2ad-6cc1-4a10-ab98-4857f0ae827d)

2. Most developers favour snake_case_variable_names over kebab-case-variable-names. Because of thes, `_` character is much more utilized than `-` character. So Colemak DHJK swapps these two key invocations. `_` will be triggered on a normal keypress and `-` will be triggered when `Shift` + `_` is pressed. This has the added benifit of `+` key and `-` key being on the same `Shift` + layer.

![image](https://github.com/viduranga/ColemakDHJK/assets/8828757/4805a362-4691-4be7-a754-1716d1d4c9a5)

![image](https://github.com/viduranga/ColemakDHJK/assets/8828757/90b2668f-dc1f-4e36-abe6-376e8d612f7a)

## Why not?

### Why not change the keybindings in Vim instead of inventing a new layout?
It's not just Vim, lot more power user apps like LazyGit, LazyDocker, NNN uses JKLH keybinding for navigations. It becomes a real hassle and in some situations impossible to change all these app configs

### Why not change a lot more and bring JKLH keys back to the home row?
If we change the layout a lot, it will lose all the things that make Colemak DH such a perfect layout.

## How to install?

1. Download the `Colemak DHJK.bundle` file from the repository
2. Copy the file to `/Library/Keyboard Layouts` directory
3. Open `System Preferences` -> `Language and Region`. Click the `Keyboard Preferences` button at the bottom.
    - Click the `Input Sources` tab at the top.
    - Click the `+` (plus) sign at the bottom left to ‘add a keyboard layout’.
    - Find the `Colemak DHJK` layout from the right hand side and click add.
    - The layout is now ready to use.
4. To access the layout, click on the flag icon in your menubar. Select the `Colemak DHJK` layout from the list.
