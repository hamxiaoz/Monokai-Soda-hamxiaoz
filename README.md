Monokai-Soda-hamxiaoz
=====================
My theme for sublime text 2, based on monokai soda. Inspired from my vim theme.

To install, git clone this repository to your /packages directory.

# Usage (vim + markdown)
- ignore 'Vintage' to enabel vim
- don't ignore 'Markdown'
- install MarkDownExtended and restart
- set syntax as 'markdown extended' by `CTRL+SHIFT+P` or right-click right corner and choose `change all`.
- use monokai_soda_hamxiaoz theme

# Known bugs
1. italic is not recognized well, so I disabled it
If the name is 'c_d' and 'e_f', there should be no italic recognized from d to e.

# Updates
07/24/2014
- fenced code block now has a darker background color (borrowed from [sublime-monokai-extended](https://github.com/jonschlinkert/sublime-monokai-extended/blob/master/Monokai%20Extended%20Bright.tmTheme))
- change markup.bold to red
- changed link title color

# Tests
Copy the following to sublime to test:

----

[link](http://)
- [link](http://)

```coffee
# comment
test = ->
    console.log 's'
```

```js
// comment
function(){
    console.log('s');
}
```

Quote
> sfsfwffw
rr22r2

Code (should be **same** as quote)
`wefwf`

**bold**
__bold__

*italic*
_italic_

**bold and _italic_**

~~strikethrough~~

\\escape?


- sdsdfsdf
x dsfsdff
_ asfsfsf
? sdfsdfsdfsdf

----
