Import a csv into supabase

![office_table](/images/office_table.png)

Set row level secruity [SET AS READ ACCESS ONLY](https://www.youtube.com/watch?si=UxWQEeCwsjXay-Vr&v=WAa3a-HxLVs&feature=youtu.be&ab_channel=NetNinja)

![rowlevel_security](/images/rowlevel_security.png)

Queries SQL syntax usage

<!-- SHOULD DISPLAY LIST OF ALL ACTORS BIRTHDAYS FROM YOUNGEST TO OLDEST -->

SELECT * FROM "office" ORDER BY birth_date Desc

![sql_descending](/images/sql_descending.png)

<!-- SHOULD SHOW ALL M ACTORS -->

SELECT first_name FROM "office" WHERE gender = 'M'

![sql_male](/images/sql_male.png)

Make 4 queries of the API end point with Postman

<!-- GET with API KEY ENABLED USE THIS ENTIRE LINK IN POSTMAN TO ACCESS DATA -->

![first_name](/images/first_name.png)

GET
curl 'https://wxvtnddwjkxjaddrfgif.supabase.co/rest/v1/office?select=first_name' \
-H "apikey: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Ind4dnRuZGR3amt4amFkZHJmZ2lmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MDExODQwMDcsImV4cCI6MjAxNjc2MDAwN30.Z7rIaeeU5hNaFO93_xR38zCE4OoctnUS4ohe9dGp-W4" \
-H "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Ind4dnRuZGR3amt4amFkZHJmZ2lmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MDExODQwMDcsImV4cCI6MjAxNjc2MDAwN30.Z7rIaeeU5hNaFO93_xR38zCE4OoctnUS4ohe9dGp-W4"

![last_name](/images/last_name.png)
GET
curl 'https://wxvtnddwjkxjaddrfgif.supabase.co/rest/v1/office?select=last_name' \
-H "apikey: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Ind4dnRuZGR3amt4amFkZHJmZ2lmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MDExODQwMDcsImV4cCI6MjAxNjc2MDAwN30.Z7rIaeeU5hNaFO93_xR38zCE4OoctnUS4ohe9dGp-W4" \
-H "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Ind4dnRuZGR3amt4amFkZHJmZ2lmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MDExODQwMDcsImV4cCI6MjAxNjc2MDAwN30.Z7rIaeeU5hNaFO93_xR38zCE4OoctnUS4ohe9dGp-W4"

![birth_date](/images/birth_date.png)
GET
curl 'https://wxvtnddwjkxjaddrfgif.supabase.co/rest/v1/office?select=birth_date' \
-H "apikey: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Ind4dnRuZGR3amt4amFkZHJmZ2lmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MDExODQwMDcsImV4cCI6MjAxNjc2MDAwN30.Z7rIaeeU5hNaFO93_xR38zCE4OoctnUS4ohe9dGp-W4" \
-H "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Ind4dnRuZGR3amt4amFkZHJmZ2lmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MDExODQwMDcsImV4cCI6MjAxNjc2MDAwN30.Z7rIaeeU5hNaFO93_xR38zCE4OoctnUS4ohe9dGp-W4"

![read_rows](/images/read_rows.png)
GET
curl 'https://wxvtnddwjkxjaddrfgif.supabase.co/rest/v1/office?select=*' \
-H "apikey: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Ind4dnRuZGR3amt4amFkZHJmZ2lmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MDExODQwMDcsImV4cCI6MjAxNjc2MDAwN30.Z7rIaeeU5hNaFO93_xR38zCE4OoctnUS4ohe9dGp-W4" \
-H "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Ind4dnRuZGR3amt4amFkZHJmZ2lmIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MDExODQwMDcsImV4cCI6MjAxNjc2MDAwN30.Z7rIaeeU5hNaFO93_xR38zCE4OoctnUS4ohe9dGp-W4"

# cpnt200-a2
