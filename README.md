# Advanced HTML5 Elements and Forms
HTML5 has introduced several new elements and attributes that can be used to create more advanced and interactive forms. Some of the most commonly used HTML5 elements and attributes for forms include:

1. `<input>` element: The `<input>` element is used to create input fields in a form. HTML5 has introduced several new input types, such as `email`, `date`, `time`, and `range`, that can be used to create specific types of input fields.
2. `<label>` element: The `<label>` element is used to associate a text label with an input field is especially useful when the input field is a checkbox or radio button, as it helps users understand what the input field is for.
3. `<select>` element: The `<select>` element is used to create a dropdown list of options for the user to choose from.
4. `<textarea>` element: The `<textarea>` element is used to create a multi-line input field for the user to enter text.
5. `<fieldset>` and `<legend>` elements: The `<fieldset>` element is used to group related input fields together, while the `<legend>` element is used to provide a caption for the group of input fields.
6. `<input type="submit"` and `<input type="reset">` elements: These elements are used to create a submit button and a reset button for the form, respectively.

Overall, HTML5 provides several new elements and attributes that can be used to create more advanced and interactive forms, making it easier for developers to create complex and user-friendly forms.


## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
>Here is an example of an `index.html` file that includes an ordered list with roman numerals, an external image from pexels.com, a table of 5 contacts with name, address, mobile, and emails, and a registration form with the specified requirements:
```php
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <ol>
      <li>I. Introduction</li>
      <li>II. Services</li>
      <li>III. Products</li>
      <li>IV. About Us</li>
      <li>V. Contact Us</li>
    </ol>
    <img src="https://www.pexels.com/photo/person-holding-laptop-1174475/" alt="Person holding laptop">
    <h2>Contacts</h2>
    <table>
      <tr>
        <th>Name</th>
        <th>Address</th>
        <th>Mobile</th>
        <th>Email</th>
      </tr>
      <tr>
        <td>John Doe</td>
        <td>123 Main St, Anytown, USA 12345</td>
        <td>555-555-1212</td>
        <td>[johndoe@example.com](mailto:johndoe@example.com)</td>
      </tr>
      <tr>
        <td>Jane Smith</td>
        <td>456 Park Ave, Anytown, USA 67890</td>
        <td>555-555-1213</td>
        <td>[janesmith@example.com](mailto:janesmith@example.com)</td>
      </tr>
      <tr>
        <td>Bob Johnson</td>
        <td>789 Oak St, Anytown, USA 34567</td>
        <td>555-555-1214</td>
        <td>[bobjohnson@example.com](mailto:bobjohnson@example.com)</td>
      </tr>
      <tr>
        <td>Emily Brown</td>
        <td>321 Maple Ave, Anytown, USA 43210</td>
        <td>555-555-1215</td>
        <td>[emilybrown@example.com](mailto:emilybrown@example.com)</td>
      </tr>
    </table>
    <h2>Registration Form</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>
      <label for="date">Date:</label>
      <input type="date" id="date" name="date" required>
      <label for="dropdown">Dropdown:</label>
      <select id="dropdown" name="dropdown">
        <option value="option1">Option 1</option>
        <option value="option2">Option 2</option>
        <option value="option3">Option 3</option>
      </select>
      <label for="radio">Radio Buttons:</label>
      <input type="radio" id="radio1" name="radio" value="radio1">
      <input type="radio" id="radio2" name="radio" value="radio2">
      <input type="radio" id="radio3" name="radio" value="radio3">
      <label for="checkbox">Checkboxes:</label>
      <input type="checkbox" id="checkbox1" name="checkbox" value="checkbox1">
      <input type="checkbox" id="checkbox2" name="checkbox" value="checkbox2">
      <input type="checkbox" id="checkbox3" name="checkbox" value="checkbox3">
      <input type="submit" value="Submit">
    </form>
  </body>
</html>
```
In this , the `<!DOCTYPE>` declaration is used to specify the document type as HTML5. The `<html>` element contains the entire webpage, and the `<head>` element contains metadata about the webpage, such as the title and any linked stylesheets or scripts.

The `<body>` element contains the visible content of the webpage, which includes an ordered list with roman numerals, an external image from pexels.com, a table of 5 contacts with name, address, mobile, and emails, and a registration form with the specified requirements.

The registration form includes input fields for name, email, password, and date, as well as a dropdown
    
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
Here is astructured HTML5 document that ensures semantic correctness:
```php
<!DOCTYPE html>
<html>
  <head>
    <title>My Webpage</title>
  </head>
  <body>
    <header>
      <h1>Welcome to My Webpage</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="about">
        <h2>About Us</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam in tellus sapien. Etiam sit amet tellus vel eros tincidunt sodales id id eros. Donec auctor, libero vel tempus mollis, velit velit interdum dolor, vel volutpat nisl lorem at massa.</p>
      </section>
      <section id="services">
        <h2>Our Services</h2>
        <ul>
          <li>Service 1</li>
          <li>Service 2</li>
          <li>Service 3</li>
        </ul>
      </section>
      <section id="contact">
        <h2>Contact Us</h2>
        <form>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required>
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" required>
          <input type="submit" value="Send">
        </form>
      </section>
    </main>
    <footer>
      <p>&copy; 2021 My Webpage. All rights reserved.</p>
    </footer>
  </body>
</html>
```
In this example, the document starts with a `<!DOCTYPE>` declaration, followed by an `<html>` element that contains the entire webpage. The `<head>` element contains metadata about the webpage, such as the title and any linked stylesheets or scripts. The `<body>` element contains the visible content of the webpage.

The `<header>` element is used to define the header section of the webpage, which typically contains the main navigation menu. The `<main>` element is used to define the main content of the webpage, which in this case is a series of `<section>` elements. Finally, the `<footer>` element is used to define the footer section of the webpage, which typically contains copyright information or other information about the website.

Overall, this example demonstrates how to use HTML5 elements to create a well-structured and semantically correct webpage.
