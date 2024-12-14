# scribbles
Sandbox repo to learn and practise GitHub Pages.

## Obsidian as editor
I have now cloned this repo to my computer. Then opened the folder as a vault in Obsidian, where I can edit the files. I have added a Git plugin to Obsidian so I can pull/push changes from/to the repo from within Obsidian. This way I can quickly publish changes directly from Obsidian to the live GitHub Pages site.

## Structure and formatting
Let's just try some basic markdown features like **bold** and *italic* text.

### Lists
Here is a numbered list. The 2nd item has a second level. The 3rd item has a bullet list 

1. This is the 1st item in a numbered list.
2. This 2nd item has another level ov numbered items in it.
	1. This is item 2.1 or 2-a if you will.
	2. This is item 2.2 or 2-b.
3. This 3rd item contains a bullet list.
	- Bullet item.
	- Another bullet item.
		- A bullet sub-item.
		- Ok, enough bullet item now.

### Checkboxes
Now something a bit more difficult. Here is an Obsidian style task list, which should display as checkboxes.

- [ ] Checkable item number one.
- [x] Second item. This one is checked.
- [/] Third item. This one is semi-checked, which may be less supported.

## Internal links
Here is a link to [[Second page]], created in Obsidian. Will it work?
The answer is no. Wiki style links in Obsidian are not automatically translated into working URL anchors. This is not surprising.

To make this work we need to advance from just static markdown pages to using [[Jekyll]].

## Images
Let's try to embed an image. Remember that this is all done in Obsidian, this will probably not translate into a working `img` in the webpage.

To increase the chance of success I have set *link format* in Obsidian to `Relative path to file`. I have also set the filename of this particular image to only *lower case* and *no spaces*.

![[media/avbild_obsidian_editor.png]]
*Screenshot of editing this very file in Obsidian.*

