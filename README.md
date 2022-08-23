# Phase 1 Project : Basic User Management

<h3>Objectives of this Project:</h3>
<ul>
  <li>Apply the CRUD (create, read, update, delete) concept to the database related function and features to be developed.</li>
  <li>Develop the Frontend and Backend aspect of the basic user management system.</li>
</ul>

<h4>N-Tier Architecture <b>MERN Stack):</b></h4>
<ul>
  <li>MySQL Database</li>
  <li>ExpressJS and NodeJS</li>
<<<<<<< HEAD
  <li>ReactJS</li>
=======
  <li>ReactJS and Bootstrap</li>
>>>>>>> ed1105793675259f387ffa6980beb48638c9234d
</ul>

<h4>Assumptions:</h4>
<ul>
  <li>A user has a unique email and username.</li>
  <li>Username and email cannot have spaces.</li>
  <li>System is built for less than 30 users.</li>
</ul>

<h4>Persona:</h4>
<ul>
  <li>Admin</li>
  <li>Normal User</li>
</ul>
<<<<<<< HEAD

<h4>User Stories:</h4>
<ul>
  <li>Admin (Priiledged User):</li>
  <ul>
    <li>Create Accounts (Username*, Password*, Email, UserGroup(s), isActive)</li>
    <li>Update Accounts (Username*, Password, Email, UserGroup(s), isActive)</li>
    <li>Create a UserGroup <i>(E.g., Admin, Project Lead, Project Manager, Team Member, Software Engineer, etc.)</i></li>
    <li>Add User into UserGroup(s)</li>
    <li>Remove User into UserGroup(s)</li>
  </ul>
  <li>Normal User</li>
  <ul>
    <li>Update Own Credentials (Password or Email)</li>
  </ul>
</ul>

<h4>Password Requirements</h4>
<ul>
  <li>Ensure that the password is not stored in clear text in the database which is a violation to security requirement.
    <i>bcrypt.js</i> was used to store the password. The hashed password will be compared for authentication purposes. 
  </li>
  <li>Password must be between 8 - 10 characters</li>
  <li>Password must comprise alphabets, numbers and special characters</li>
</ul>
=======

<h4>User Stories:</h4>
<ul>
  <li>Admin (Priviledged User):</li>
  <ul>
    <li>Create Accounts (Username*, Password*, Email, UserGroup(s), isActive)</li>
    <i>Note: isActive is a Boolean value. If isActive = false, the specified username will be disabled and unable to login to his/her account.</i>
    <li>Update Accounts (Username*, Password, Email, UserGroup(s), isActive)</li>
    <li>Create a UserGroup <i>(E.g., Admin, Project Lead, Project Manager, Team Member, Software Engineer, etc.)</i></li>
    <li>Add User into UserGroup(s)</li>
    <li>Remove User into UserGroup(s)</li>
  </ul>
  <li>Normal User</li>
  <ul>
    <li>Update Own Credentials (Password or Email)</li>
  </ul>
</ul>

<h4>Password Requirements</h4>
<ul>
  <li>Ensure that the password is not stored in clear text in the database which is a violation to security requirement.
    <i>bcrypt.js</i> was used to store the password. The hashed password will be compared for authentication purposes. 
  </li>
  <li>Password must be between 8 - 10 characters</li>
  <li>Password must comprise alphabets, numbers and special characters</li>
</ul>

<h4>Areas of Improvement</h4>
<ul>
  <li>Implement more advanced React Hooks</li>
  <li>Add state dependencies in useEffect to minimise refreshing of the browser.
    <i>Note: This will be implemented in Phase 2 of the project : Task Management Features</i>
  </li>
</ul>

>>>>>>> ed1105793675259f387ffa6980beb48638c9234d