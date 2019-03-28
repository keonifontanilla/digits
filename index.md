<img src="doc/landing.png">
Digits is an application that allows users to:
<ul>
  <li>Register and account.</li>
  <li>Create and manage a set of contacts.</li>
  <li>Add a set of timestamped notes regarding their interactions with each contact.</li>
</ul>

**Installation**

<ol>
  <li>Install <a href="https://www.meteor.com/install">Meteor.</a></li>
  <li><a href="https://github.com/keonifontanilla/digits">Download a copy of Digits.</a> 
  Digits is a private repo so you must ask for permission to gain access.</li>
  <li> Change directory into the app directory and install the required libaries with
    <pre>
      meteor npm install
    </pre>
    Then run the app with 
    <pre>
      meteor npm run start
    </pre>
  </li>
</ol>

<h2>User Interface Walkthrough</h2> <br/>
**Landing page**<br/>
Provides an introduction on the features of Digits. You can login as an existing user or sign
up as a new user. After logging in, you will see the home page with list contact and add
contact in the Navbar as well as your user name.

<img src="doc/landing2.png">

**Add contact**<br/>
Clicking on the add contact link brings up a page that allows the user to add a new contact.

<img src="doc/addcontacts.png">

**List contact**<br/>
Clicking on the list contact list brings up a page that lists all the contacts associated
with the user logged in. This page also allows the user to add timestamped notes to each
contact.

<img src="doc/listcontacts.png">

**Edit contact**<br/>
From the list contact page the user is able to click the "Edit" link associated with any 
contact to bring up a page that allows contact details to be edited.

<img src="doc/editcontacts.png">

**Admin mode**<br/>
There is an admin page accessible only by a user with access to an Admin role. A special link
on the Navbar named "Admin" brings up a page with all contacts associated with all users.

<img src="doc/admin.png">

