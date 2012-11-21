# easy-highlight.el

## Introduction
`easy-highlight.el` is wrapper `hi-lock` for easy to use it.

## Screenshot

![easy-highlight1](https://github.com/syohex/emacs-easy-highlight/raw/master/image/easy-highlight1.png)

![easy-highlight2](https://github.com/syohex/emacs-easy-highlight/raw/master/image/easy-highlight2.png)


## Requirements

* Emacs 23 or higher


## Basic Usage

Highlighted specified regexp. Highlight face is selected automatically.

    M-x easy-highlight:regexp

Highlight words which separated space

    M-x easy-highlight:words

Clear specified highlighted word

    M-x easy-highlight:clear

Clear all highlighted words

    M-x easy-highlight:clear-all


## Customize

Face list for highlighted word

    easy-highlight:face-list


## Sample Configuration

```` elisp
(global-font-lock-mode t)

(require 'easy-highlight)
(setq easy-highlight:face-list '("highlight" "warnings"))

````
