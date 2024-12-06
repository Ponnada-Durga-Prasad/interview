** Question 1 **

# debugging question

`

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div style="width: 300px; padding: 20px; border: 10px solid black; box-sizing: border-box;">
        Fix this box model error.
    </div>    
</body>
</html> `

# Output based question

`

   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div >

    </div>

</body>
</html>
 `

`div {
    box-sizing: border-box;
    width: 50vh;
    padding: 10px;
    border: 5px solid red;
    margin: 50vh;
    margin-bottom: 50vh;
    margin-left: auto;
    margin-right: auto;
}
`

# Related question task

`Flex box is used for layout like box model, but flex box is like container with element and also flexbox has two types of style flex container styles and item styles , when we use flex box with box it leads to further customization of the layout, because even though grid provides child properties, but we can style the child using box model`

** Question 2 **

# debugging question

`<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div style="background-color: blue; width: 100px; height: 100px;">
        <div style="position: relative; top: 10px; left: 20px; background-color: red;">
            I should be positioned relative to my parent.
        </div>
    </div>

</body>
</html> `

# Output based question

`

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <ol>
        <li>Home</li>
    <li>Contact</li>
    <li>About Us</li>
    </ol>
    
</body>
</html> `

`\* {
margin: 0;
padding: 0;
box-sizing: border-box;
}

ol {
list-style-type: none;
position: sticky;
display: flex;
font-size: 20px;
justify-content: space-around;
background-color: blue;
color: white;
cursor: pointer;
}`

# Related question task

``

** Question 3 **

# debugging question

` <!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    
</body>
</html>

`

`:root {
    font-size: 16px;
}
.box {
    width: 2rem;
    height: 2rem;
}`

# Output based question

`<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="output.css" />
  </head>
  <body>
    <!-- <div> -->
    <h2>Hello</h2>
    <!-- </div> -->
  </body>
</html>
 `

`/_ div {
width: 100px;
height: 100px;
background-color: red;
} _/

h2 {
font-size: 2vw;
}`

** Question 4 **

# debugging question

`<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body></body>
</html>
 `

`#box {
color: green;
}
div .box {
color: red !important;
}

`

# Output based question

` <!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="card.css" />
  </head>
  <body>
    <div id="cart">
      <h1>Name: Shiva</h1>
      <p>Graduate</p>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam
        consectetur eligendi distinctio pariatur. Quas delectus impedit aut
        dolores ducimus eveniet. Vel magni voluptas fuga voluptates omnis nam
        tempora beatae rem harum accusantium. Suscipit quod, exercitationem
        placeat quaerat officia illum doloremque excepturi enim. Hic
        consequuntur sed, eaque nemo qui quod tempore ut eligendi perferendis
        quis dolorum! Deserunt tempora asperiores voluptatem perferendis,
        consectetur saepe vero nobis ad eos ratione repudiandae? Accusantium
        fugiat fugit, facilis molestiae, qui nisi corrupti aspernatur, beatae id
        possimus nihil aut ullam laudantium laboriosam facere velit minus
        ratione nesciunt blanditiis? Atque incidunt aspernatur cumque reiciendis
        asperiores assumenda dolores fuga!
      </p>
    </div>
  </body>
</html>
`

`\* {
margin: 0;
padding: 0;
box-sizing: border-box;
}
#cart {
border: 2px solid black;
padding: 20px;
width: 500px;
height: 500px;
margin: auto;
background-color: teal;
}

p {
margin: 20px;
}
`
