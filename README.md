Pixel Saver
===========

Pixel Saver is an extension for Gnome Shell that merge the activity bar and the title bar of maximized window. It is especially interesting for small screens, but MOAR pixels for your apps is always good !

The extension has no configuration. Its behavior is made to mimic the one of the title bar and settings affecting the title bar should reflect in Pixel Saver. It **Just Works** !

<table>
	<tr>
		<td><img src="https://raw.github.com/deadalnix/pixel-saver/master/title.png" /></td>
		<td><img src="https://raw.github.com/deadalnix/pixel-saver/master/icons.png" /></td>
	</tr>
	<tr>
		<td colspan="2">The title bar is completely gone and integrated to the activity bar.</td>
	</tr>
</table>

It is largely inspired by [bios and mathematicalcoffee's Window Buttons Extension](https://github.com/mathematicalcoffee/Gnome-Shell-Window-Buttons-Extension) and [mathematicalcoffee's maximus extension](https://bitbucket.org/mathematicalcoffee/maximus-gnome-shell-extension) and some code come from there. You may want to check theses out, especially if you want something more configurable.

Installation
------------

Simply follow the instructions and everything should be fine :

    git clone https://github.com/deadalnix/pixel-saver.git
    cd pixel-saver
    # Get the last released version
	git checkout 1.9
    # copy to extensions directory
    cp -r pixel-saver@deadalnix.me -t ~/.local/share/gnome-shell/extensions
    # activate
    gnome-shell-extension-tool -e pixel-saver@deadalnix.me

### Dependencies

Pixel Saver depends on Xorg's xprop utility.

Configuration
-------------

Don't be silly !

Support for older versions of gnome shell
-----------

If you use an older version of gnome shell, here are the versions of pixel saver that you should use.

| Gnome Shell | Latest version of pixel saver supporting it                          |
|-------------|----------------------------------------------------------------------|
| 3.12        | [1.3](https://github.com/deadalnix/pixel-saver/releases/tag/1.3)     |
| 3.14        | [1.5.1](https://github.com/deadalnix/pixel-saver/releases/tag/1.5.1) |
| 3.15        | [1.10](https://github.com/deadalnix/pixel-saver/releases/tag/1.10)   |

Screenshots
-----------

If you want to see what the full desktop look like with this extension, you can check out what a [unmaximized window](https://raw.github.com/deadalnix/pixel-saver/master/unmax.png) looks like, as well as a [maximized one](https://raw.github.com/deadalnix/pixel-saver/master/max.png).

