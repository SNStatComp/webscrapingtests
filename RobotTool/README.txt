Introduction
------------
The scripts in this directory have been used for testing the basic functionality of the robot tool and for testing the ability
to configure new price collection in the tool.
The scripts contain three dynamic web pages, that, each time one visits the page, display the same page with some minor changes.
Each page has a number of prices, that may change (a real price change).
The pages also have a number of prices that do not change, but some word in the surrounding context changes.
You can see the changes easily by repeatedly visiting the pages with a standard browser.

In orde to be able to test the functionality to automatically follow a path through a website, the first page has a link to
the second page which on its turn has a link to the third page.

Use
---
In order to implement the dynamic behavior of the web pages, these pages use the randomizer in PHP.
You can install them on a PHP server in order to repeat the tests.