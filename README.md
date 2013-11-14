# Keyboard Maestro Workflow

#### Activate any of your KM hotkeys in Alfred 2

This is a workflow for anyone who uses Keyboard Maestro and wishes it had built-in Alfred support. In Alfred simply type `km` followed by the name of any of your KM hotkey macros.

## Requirements 

Alfred 2 (w/ Powerpack) and Keyboard Maestro 6.3 or greater. If you don't have them, go get them immediately. You will not regret it.

- [Alfred 2](http://www.alfredapp.com/) (Free, but requires £17 Powerpack)
- [Keyboard Maestro](http://www.keyboardmaestro.com/main/) (Free to try. $36/license)

Both well worth the cost.

## Installation

Download the zip file or clone this repo, then double-click the included 'KeyboardMaestro.alfredworkflow' file to install. 

## Usage

Type `km` followed by the name of any of your defined macros. 

![usage example screen](screen.png "Usage Example")

#### Update:

Thanks to Peter Lewis of [Stairways Software][stair], the creator of Keyboard Maestro for adding a feature to KM that greatly increased the power of this workflow. Now Alfred can launch any of your macros, not just the ones with a hotkey!

[stair]: http://www.stairways.com/main/

## Possible Issues 
This runs successfully with PHP 5.5.5 (The latest version as of this writing). The XML used to generate the feedback for Alfred was having some issues on a lower version of PHP (5.3.26) when I tested. If you are getting empty results within Alfred then this may be the issue. 

To figure out what version of PHP you are running you can try the following command in the Terminal: `/usr/bin/php -v`. You can also run `which php` to see which binary is being used for the command line. 

