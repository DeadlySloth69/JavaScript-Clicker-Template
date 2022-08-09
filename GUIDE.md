# Guide to the Template.
This file may be deleted if you publish the game.


title - The "title" tag stores the name shown in the tab on the page.

.centerSqr - This is a class for the item in the middle of the game, which will be the object to be clicked.

.hide - The class given to all objects to be hidden at any given point.

.shop1 - This class stores CSS information for the yellow square in the bottom left corner which is a shop to buy Upgrades (this one adds one to your power).

var - This declares a variable in JavaScript.

init() - A function programmed to show anything hidden at the start and initiate the game.

addPoints() - The function that adds points when the item is clicked.

shop1() - The function that subtracts 10 points when you buy the upgrade from shop 1 which adds 1 power to your click.

onclick="init()" - When put in the button tag, makes the game initiate and start when you click it.

onclick = "addPoints()" - Makes the "addPoints()" function run when the item is clicked.

onclick = "shop1()" - Executes "shop1()" when shop is clicked.

document.getElementById() - Every element in this game has an id. What this script does is retrieves a selected parameter from an element with a matching id.
