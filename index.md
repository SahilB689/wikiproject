<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Flights</title>
    </head>
    <body>
    <h1>All Pages</h1>

    <ul>
        {% for entry in entries %}
            <li>{{ entry }}</li>
        {% endfor %}
    </ul>
    </body>
</html> 
