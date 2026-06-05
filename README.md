Travelling packing App

The Travel Packing App is a simple Android application developed in Kotlin. The app allows users to create and manage a travel packing list by adding items to an inventory. Users can store up to 10 items, view the stored items on a second screen, and exit the application when finished.

 Features

 Screen 1 (MainActivity)

  Add travel items to a packing list.
  Store up to 10 items.
  Display the current number of stored items.
  Prevent additional items from being added once the list reaches capacity.
  Open a second screen to view all stored items.
  Exit the application.

Screen 2 (MainActivity2)

  Receive the packing list from Screen 1.
  Display the stored items in a ListView when the Inventory button is pressed.
  Return to the main screen using the Back button.


MainActivity

The first screen of the application responsible for:

  Accepting user input through an EditText.
  Storing items in a MutableList.
  Tracking the number of stored items.
  Sending the item list to MainActivity2 using an Intent.

MainActivity2

The second screen of the application responsible for:

  Receiving data passed from MainActivity.
  Displaying the packing list in a ListView.
  Returning the user to the previous screen.

How the Application Works

1. The user enters a travel item into the text box.
2. The user clicks the "Add Item" button.
3. The item is added to the packing list.
4. The application updates the storage counter.
5. Once 10 items have been added, the Add button becomes disabled.
6. The user clicks "Open Bag" to navigate to Screen 2.
7. The packing list is transferred using an Intent.
8. The user clicks "Inventory" to display all stored items.
9. The user can return to the main screen using the Back button.
