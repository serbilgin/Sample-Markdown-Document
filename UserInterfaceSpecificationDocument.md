# User Management Screen

This screen is used to manage existing users. Via this screen, new users can be added, existing user information can be viewed.

# Content
This screen consist three main components which are **Header**, **User List** and **New User Form**.  **Header** covers the top of the page. **User List** and **New User Form** stand side by side. When the screen first loaded, **New User Form** should not appear.

* ## Header
	Header includes **New User** button, **Hide Disabled User**  checkbox and **Save User** button.  When "New User" button is clicked, "New User Form" appears. This button is located at the left end. Clicking the "Hide Disabled User" checkbox will disappear disabled users in the user list. This checkbox is next to the "New User" button. "Save User" button is on the other side. This button is to save new user information given in the "New User Form".
* ## User List
	"User List" is to show details of existing users. There are 4 columns to be shown. These are **ID** which indicates identity number of the user, **User Name**, **E-mail** and lastly **Enabled**. Each column can be filtered or rows can be moved upwards or downwards.
*  ## New User Form
	This form allows new users to be added. While registering new user, some informations will be required. These are respectively **Username**, **Display Name**, **Phone**, **Email**, **User Roles** and **Enabled**. "Enabled" is boolean value, so checkbox can be useful here. "User Roles" will be listed in list items. Rest is acquired via textbox.


