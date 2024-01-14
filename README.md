# Project: Introduction to Object Handling in JavaScript for Beginner's Developers

## Description


This is a simple project create as the objective provide a pratrice introduction to object handling in JavaScript. The project uses an object list to represent personal information, such as name, age, and city, for different individuals.

## Project Structure

The project is composed of an HTML file that incorporates an embedded JavaScript script. This script contains a list of objects to represent people, each with specific properties.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    <script>

      // List of people to understand object handling
        var people = [{
            'name' : 'Lukka',
            'age' : '19',
            'city' : 'Osasco',
        },
        {
            'name' : 'Paola',
            'age' : '22',
            'city' : 'Rio de Janeiro'
        },
        {
            'name' : 'Brenda',
            'age' : '22',
            'city' : 'Berlin',
        }
        ]

        // Example of data access for educational purposes
        alert(people[1].name)

    </script>

</body>
</html>
