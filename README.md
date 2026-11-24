# mtm6302_final_bell0729

Project: Lost and Found Log
Developer: Lucas Bell

The purpose of this app is to allow users to keep track of item they lent or misplaced so they don't get lost permanently.
The app will accomplish this goal by providing a list of lent items which the user can edit the name of and change whether they are currently lent or not.
Users can also remove items at any time by hitting a remove button next to the item.

Confirmed features:
Add an item button which adds an item to the list with the name inputted by the user, the name or place the user lent or left the item and the tag of lent to someone or left somewhere.
Mark as back button which marks an item as back in the user's possession rather than lent out.
Filter the list buttons which filters the list based on away, back, or all items
Remove an item button which removes the item from the list.
Clear all button which makes the user confirm they want to delete all then removes all items from the list.

Extra features if time permits:
A button that clears the items that are returned to the user.
A search bar that finds an item based on a keyword.
An automatically applying date that applies the date to every entry added.

Data the app needs:
Name of the item................................................ D1
Name of the person or place the item was lent or placed......... D2
If an item is lent or left...................................... D3
If item is returned or away..................................... D4

Data types:
D1 const
D2 const
D3 const boolean
D4 const boolean

Data initially:
D1 null
D2 null
D3 true meaning lent
D4 false meaning away

Where data comes from and changes:
D1 comes from user and changes the name of the item
D2 comes from user and changes the name of who the item was lent to or where it was placed last
D3 comes from user and changes whether an item appears as lent to someone or placed somewhere
D4 comes from user and changes the status of the item from away to returned

Saved in local storage:
D1 saved in local storage
D2 saved in local storage
D3 saved in local storage
D4 saved in local storage

Data project specifications:
Storage key: items-left-lent-locations
Startup restoration: restores all items on load and reload
Reset behaviour: erases all items and reset form button to lent to someone and filter set to all

Example:
"Lent to someone" - Bob - Hammer - Item is away
