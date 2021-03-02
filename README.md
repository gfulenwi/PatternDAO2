# patternDAOv2
The DAO Example from the repository patternDAO with the delete function added.

In this example, we start with the DAO Example in the repository patternDAO which included the implementation of the Create (Add Contact) and Read (Display Contacts) from the four basic CRUD operations.  In this example, we will add the implementation of the Delete (Delete Contact) to the application.  To do this we will perform the following steps:

1. Modify the **index.php** page to incorporate multiple *submit* buttons that can be used to perform different processing on the form submission based on the button pressed.  The form will include a radio button (with the row's contactID assigned to the value) to select the row to delete. The form will submit to the index.php page using a HTTP Get method.  From there we will determine the processing and next view based on the value of the **submit** button.
2. Implement the Delete in the **ContactDAO.php** by adding a *deleteContact()* function to delete a record from the table based on the contactid.
3. Add the Confirm Deletion Page.
