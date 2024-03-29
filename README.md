# poolpool, a versus tracker

A simple web app for tracking head-to-head results between friends (I hope)

Hosted here: https://danmsto.github.io/poolpool/

## Collector App Unit 2 project at EyUp Coding Academy

This is an individual project

You will be making a web application that allows a user to create a collection of things.

I have made a list of user stories to describe the functionality of the completed project. If you do not manage to complete them all, try to ensure that the stories you attempt are complete. Some stories require that other stories are completed first.

<hr>

### ID: 2-1

As a user ...<br>
... I want to add an item to a collection of things<br>
... so that I have a way to build up a collection

Acceptance criteria:

- Each thing must have 3 properties (e.g. name, power-level etc)
- Each property must have appropriate validation
- At least 1 property must be some numerical value
- 1 property must be unique for each thing (e.g. a unique name), this should be validated.
- User should be able to use a form to enter the properties
<hr>

### ID: 2-2

As a user ..<br>
... I want to see the things with their properties that I have added to the collection<br>
... So that I can see what has been previously added to the collection

Acceptance criteria:

- When an item is added, it is immediately shown on the page
- Each item in the collection must be easily distinguishable using styles
<hr>

### ID: 2-3

As a user ...<br>
... I want my collection to not be lost when the page is refreshed<br>
... So that I don't have to rebuild my collection when I leave the page and come back

Acceptance criteria:

- When the page loads, if there are items in the collection, they should be shown
<hr>

### ID: 2-4

As a user ...<br>
... I want to delete items from my collection<br>
... So that I can remove items that I do not want in my collection anymore

Acceptance criteria:

- Each item should have something I can click on to delete an item from the collection
- It should be clear what I need to click on to delete an item.
<hr>

### ID: 2-5

As a user ...<br>
... I want to upload an image when adding an item that shows or represents that item<br>
... So that I can see what the item looks like

Acceptance criteria:

- I can pick an image from my computer to upload
- The image is shown as part of the item in the collection
- The image is stored with the item so that when I leave the page and come back, it is still shown in the collection
<hr>

### ID: 2-6

As a user ...<br>
... I want to edit the properties of items in my collection<br>
... So that I can change properties of my items if they need changing or are incorrect

Acceptance criteria:

- User can use a form to change an item's properties
- It should be clear what a user has to do to edit an item
- When editing is complete, the item is updated and the updated item is shown in the collection
<hr>

### ID: 2-7

As a user ...<br>
... I want to order/sort my collection by at least 1 of the properties<br>
... So that I can change the order in which the items are displayed

Acceptance criteria:

- User can select at least 1 property to sort by
- It should be clear how the user can do this
- When the sort property is selected, the items are sorted and shown in the new order
