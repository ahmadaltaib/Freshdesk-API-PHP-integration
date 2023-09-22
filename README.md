<p align="center">
  <img src="https://developers.freshdesk.com/images/freshdesk-developers-2d57c856.svg" alt="Freshdesk developers logo"/>
</p>

<h1 align="center"> Freshdesk API PHP integration sample</h1>


<p align="center">
  <img src="https://img.shields.io/badge/Written%20in%20PHP%20using%20Curl%20only-8A2BE2" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-ALL-purble" />
  <img src="https://img.shields.io/badge/Version-1.0.0-" />
  <img src="https://img.shields.io/badge/Coverage-100%25-green" />
  <img src="https://img.shields.io/badge/Dependencies-N/A-orange" />
  <img src="https://img.shields.io/badge/Rating-★★★★★-brightgreen" />
  <img src="https://img.shields.io/badge/Downloads-13k%2Fmonth-blue" />
  <img src="https://img.shields.io/badge/UpTime-100%25-brightgreen" />
</p>

<hr>

<h2>User management APIs</h2>
<pre>

Create a Contact
POST  /api/v2/contacts

</pre>


<pre>

Update a Contact
PUT  /api/v2/contacts/[id]

</pre>

<pre>

List All Contacts
GET  /api/v2/contacts

</pre>

<h2>Tickets management APIs</h2>
<pre>

Create a Ticket
Create a Ticket with attachment / multi attachments
Create a ticket with custom fields

POST  /api/v2/tickets

</pre>

<pre>

View a Ticket
GET  /api/v2/tickets/[id]

</pre>

<pre>

Update a Ticket
PUT  /api/v2/tickets/[id]

</pre>

<h2>Groups management APIs</h2>
<pre>

Update a Group
PUT  /api/v2/groups/[id]

</pre>

<h2>Notes APIs</h2>
<pre>

Create a Note
POST  /api/v2/tickets/[ticket_id]/notes

</pre>