#Eddie.vim

A dark pastel colorscheme my friend spent too much time on.

-----

###Compatibility

This colorscheme is compatable in GUI and Terminal Vim. It includes some
modified color highlighting for the following filetypes: HTML, CSS, JavaScript,
HAML, SASS, CoffeeScript, Ruby, ZSH, and a couple others. Also includes better
highlighting for diffing between files in Vim.

-----

###Screenshots


**HTML**  
![HTML](http://f.cl.ly/items/2y1I3j1N0m3p3s1B3X1J/eddie-html.png)

**CSS**  
![CSS](http://f.cl.ly/items/0Q1O1Z1P3X1R0z0c0j2J/eddie-css.png)

**JavaScript**  
![JavaScript](http://f.cl.ly/items/2p0u253d2p3g0u1X1a0m/eddie-js.png)

_font used is [liberation sans mono](https://fedorahosted.org/liberation-fonts/)_

------

###Installation

Add the `eddie.vim` file inside the `colors` directory to your existing
colorschemes in `~/.vim/colors/`

------

###Story

A buddy of mine spent a lot of time on [his Eclipse color
theme](http://www.eclipsecolorthemes.org/?view=theme&id=738) and I was
continually frustrated with most Vim colorschemes so I just ported his but added
some new colors for diffing.

-----

###FAQ

* *The green color in my terminal sucks*

There's no green in the 256 palette that looks like `#93C79F` so I defaulted it
to cterm's greencode 10. One way to get this to look very similar is to
[change your terminal's
green](http://f.cl.ly/items/0l2M2R010d2b3c2a0A0T/Screen%20Shot%202011-12-29%20at%209.28.41%20PM.png)
to that hex code.

* *My JavaScript doesn't look like that*

Sometimes I mess around in syntax files.  They're [on
Github](http://github.com/mattsa/dotfiles/vimbundles) but I won't take any
responsibility for things malfunctioning if you decide to use them.

* *How do I get the highlight group for a word?*

Add [this command](https://gist.github.com/1544768) to your .vimrc and use it
as `:Syn` for the word under the cursor.

* *I don't like what you did for \<insert some tag in some language here\>*  

It's super easy to customize. Just look in the `colors/eddie.vim` file for
whatever you don't like (say, CSS highlighting for pseudo-elements would be
under the CSSgroup as `cssPseudoClass`), find it and change the color to another
one defined at the top of the file or add your own.

Think it's a good change? File a pull request with a screenshot so that people
can give feedback!
