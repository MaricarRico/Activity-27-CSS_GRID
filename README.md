# Activity-27-CSS_GRID
apply it on 5 pages (ex. list of products,list of employees, list of students, etc) - name your repo CSS_GRID - add documentation on README.md of your repo - Submit github repositories
Deadline: DEC 5

Repository Structure:
plaintext
Copy
CSS_GRID
├── index.html
├── products.html
├── employees.html
├── students.html
├── about.html
└── style.css
index.html (Main Navigation Page):
html
Copy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Grid Examples</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Website</h1>
        <nav>
            <ul>
                <li><a href="products.html">Products</a></li>
                <li><a href="employees.html">Employees</a></li>
                <li><a href="students.html">Students</a></li>
                <li><a href="about.html">About Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Content for the main page -->
        <p>This is the main content area. Each link in the navigation bar will take you to a different page.</p>
    </main>

    <footer>
        <p>&copy; 2023 [Your Company Name]</p>
    </footer>
</body>
</html>


products.html (Product List):
html
Copy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Products</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Our Products</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="employees.html">Employees</a></li>
                <li><a href="students.html">Students</a></li>
                <li><a href="about.html">About Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="products">
            <div class="product">
                <img src="placeholder-product-1.jpg" alt="Product 1">
                <h2>Product 1 Name</h2>
                <p>Description of Product 1.</p>
                <button>Learn More</button>
            </div>
            <div class="product">
                <img src="placeholder-product-2.jpg" alt="Product 2">
                <h2>Product 2 Name</h2>
                <p>Description of Product 2.</p>
                <button>Learn More</button>
            </div>
            <!-- Add more products here -->
        </section>
    </main>

    <footer>
        <p>&copy; 2023 [Your Company Name]</p>
    </footer>
</body>
</html>
employees.html (Employee List):
html
Copy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Employees</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Our Employees</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="students.html">Students</a></li>
                <li><a href="about.html">About Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="employees">
            <div class="employee">
                <img src="placeholder-employee-1.jpg" alt="Employee 1">
                <h2>Employee 1 Name</h2>
                <p>Job Title: [Title]</p>
            </div>
            <div class="employee">
                <img src="placeholder-employee-2.jpg" alt="Employee 2">
                <h2>Employee 2 Name</h2>
                <p>Job Title: [Title]</p>
            </div>
            <!-- Add more employees here -->
        </section>
    </main>

    <footer>
        <p>&copy; 2023 [Your Company Name]</p>
    </footer>
</body>
</html>
students.html (Student List):
html
Copy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Students</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Our Students</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="employees.html">Employees</a></li>
                <li><a href="about.html">About Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="students">
            <div class="student">
                <img src="placeholder-student-1.jpg" alt="Student 1">
                <h2>Student 1 Name</h2>
                <p>Year: [Year] | Major: [Major]</p>
            </div>
            <div class="student">
                <img src="placeholder-student-2.jpg" alt="Student 2">
                <h2>Student 2 Name</h2>
                <p>Year: [Year] | Major: [Major]</p>
            </div>
            <!-- Add more students here -->
        </section>
    </main>

    <footer>
        <p>&copy; 2023 [Your Company Name]</p>
    </footer>
</body>
</html>
about.html (About Us Page):
html
Copy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>About Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="employees.html">Employees</a></li>
                <li><a href="students.html">Students</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="about">
            <!-- Content about your company -->
            <p>This is where you would add information about your company, its mission, history, team, etc.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 [Your Company Name]</p>
    </footer>
</body>
</html>
style.css (CSS Styling):
css
Copy
body {
    font-family: sans-serif;
    margin: 0;
}

header {
    background-color: #f0f0f0;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav li {
    display: inline-block;
    margin: 0 10px;
}

main {
    padding: 20px;
}

/* Products Page */
.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Responsive columns */
    grid-gap: 20px;
}

.product img {
    width: 100%;
    height: auto;
}

.product button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

/* Employees Page */
.employees {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Responsive columns */
    grid-gap: 20px;
}

.employee img {
    width: 100%;
    height: auto;
    border-radius: 50%;
}

/* Students Page */
.students {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Responsive columns */
    grid-gap: 20px;
}

.student img {
    width: 100%;
    height: auto;
    border-radius: 50%;
}

/* About Page */
.about {
    text-align: center;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
    position: fixed;
    bottom: 0;
    width: 100%;
}
Explanation:
HTML Structure:
Each HTML file has a basic structure with a header, navigation, main content area, and footer.
The navigation links connect the pages.
Placeholders are used for images, product details, employee information, and student data.
CSS Styling:
The style.css file provides basic styling for the layout.
The main section has a padding to create some space around the content.
The footer is styled with a dark background and fixed positioning to ensure it stays at the bottom.
CSS Grid Layout:
The products, employees, and students sections use CSS Grid for layout.
display: grid enables Grid layout.
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)) creates responsive columns that adapt to the screen size. The columns will fit as many items as possible, with a minimum width of 250px.
grid-gap: 20px adds spacing between grid items.
To Use:
Create the Repository: Create a new folder named "CSS_GRID".
Create Files: Create the HTML files (index.html, products.html, employees.html, students.html, about.html) and the CSS file (style.css) in the folder.
Add Content: Replace the placeholders with your actual content.
Add Images: Add appropriate image files for the products, employees, and students.
Open in Browser: Open index.html in your web browser to view the pages.
Remember:
Placeholders: Replace the placeholder text and images with your actual content.
Customization: You can customize the CSS styles to match your design preferences.
Responsiveness: The auto-fit and minmax() functions ensure that the layout adapts to different screen sizes.
