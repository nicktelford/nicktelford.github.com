---
layout: post
title: Pulling the cord
---
As a programmer, I spend the majority of my time typing. Whether it's writing source code, documentation, updating build scripts or grepping a log file; the keyboard is my primary input device.

But whenever I reach for my mouse, there's a noticeable change in my tempo. It breaks your gait; often, simply reaching for the mouse distracts me from the task at hand.

So I've decided to pull the cord on my mouse, metaphorically, and exclusively use the keyboard. Of course, sometimes this may not be possible (especially if I decide to start playing [StarCraft II](http://battle.net/sc2) again), but I will endeavour to stay fixed to my keyboard.

## Mouse vs. keyboard

It's important to remember, when selecting an input device, that they exist to solve very different problems.

The keyboard, with its large number of discrete inputs, excels at providing the user with a highly expressive interface to the computer. But in order to maximise this, there's a lot to remember. The keyboard is often shunned, therefore, as an elitist tool; or simply relegated to a data entry device.

The mouse, conversely, is designed to provide the user with a highly intuitive interface for interacting with the computer interactively. Mouse-based GUIs stave-off complexity by allowing the user to intuitively discover the commands they're looking for.

By choosing to maximise my time on the keyboard, I hope to gain in the long-term from the improved expressiveness, at the short-term cost of a loss in discoverability; I fully expect the first few weeks to be fraught with memorizing a slew of application-specific key-combinations.

## VIM

VIM has been my standard editor for quite some time now, and I've gone to a fair bit of effort to [customise it](https://github.com/nicktelford/dotfiles/tree/master/src/.vimrc) to my needs. Over time, it's helped me understand the expressive nature of keyboard driven input, and convinced me that to drop the mouse altogether. 


## XMonad

I made the decision several weeks ago to switch my window manager to [XMonad](http://xmonad.org). I'm still learning a lot and my [configuration](http://github.com/nicktelford/dotfiles/tree/master/src/.xmonad/) is still changing almost daily. However, I'm starting to get to the point where I'm able to reap the benefits; having a window manager that's been customised to fit my workflow has helped me reduce distractions and stopped me constantly getting lost when switching through a mass of windows.

I'll save my XMonad setup for another (lengthy) post, as I think it warrants some detail. But it's important to stress that a keyboard-driven window manager is one of the most important steps in ditching the mouse; a staggering amount of your time is spent doing window management, most of which is so trivial you give it little thought.

Thankfully, since I've been using XMonad for several weeks, I already have an intuition for the key-bindings, which should reduce my learning curve somewhat.

## Firefox

When I first started to think about this, I considered web-browsing to be one of the major hurdles. How can you browse the web without a mouse? Surely barely any website would be usable... Especially the more powerful web-apps.

I was pleasantly surprised.

Firstly, Firefox has excellent [keyboard navigation support](http://support.mozilla.org/en-US/kb/keyboard-shortcuts-perform-firefox-tasks-quickly), which aligns surprisingly well with the conventional key-bindings in GNOME/GTK+ (e.g. *Ctrl+F* and *Ctrl+G* for "find" and "find next", respectively). Tab navigation uses (by default) the same keys as both GNOME/GTK+ and [VIM](http://vim.org) (*Ctrl+PageUp* and *Ctrl+PageDown* respectively).

Parity with VIM key-bindings will actually be a recurring theme in this post.


