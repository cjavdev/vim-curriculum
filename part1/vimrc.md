# `.vimrc`

Vim is extremely configurable. Now that you're especially interested in
productivity, you'll want to configure your editor with everything you
need to [shred][shred] as fast as possible with vim.

**Do not!** just copy lines from another vimrc into yours without
knowing what that is doing.  **Now is a good time to blowaway your
existing `.vimrc` and start from scratch.**

## Plugins

As you craft your vim environment, one of the most powerful features
will be taking advantage of existing plugins. There are a couple plugin
management systems that exist (pathogen and [vundle][vundle] are the most
common). I've tried both pathogen and [vundle][vundle] and you **must** use
[vundle][vundle].

Using vundle makes adding and instlaling plugins to use with vim much
like adding gems to a `Gemfile`.

Follow [these instructions][vundle-quick-start] and get vundle installed
and running with your `.vimrc`.

Then read through [A good vimrc][a-good-vimrc] learn about some good
settings to consider for your `.vimrc`.

[a-good-vimrc]: http://dougblack.io/words/a-good-vimrc.html
[shred]: http://www.urbandictionary.com/define.php?term=shred
[vundle]: https://github.com/gmarik/Vundle.vim
[vundle-quick-start]: https://github.com/gmarik/Vundle.vim#quick-start
