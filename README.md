# Global Pre Render for Miva Merchant 5.5

This module allows you to execute some logic before a page starts to be rendered. You can define global or local variables to be
use through out all screens. You can optionally use it in conjuction with other modules such as toolkit as long as it is implemented
as an item and the setting As Item is checked in the module configuration.

You can use this module for lots of reasons. Some of the reasons I have made it:

- Detect if the user is on a mobile device and define a global variable
- Define checkout version global variables
- Define other global variables such as "Free Shipping Over $x" to implement into templates along with any shipping rules/modules

## Installation

Clone this repository and install the module in the dist/ folder. Once you have installed the module you need to enable it for your store.
Go to the System Extension Settings and enable Global Pre Render module. Once enabled, you can configure it and implement some logic in the
Global Pre Render tab.



