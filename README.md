## **🎓 CSS Basics Assignment**  

### **Assignment Title**  
**"Mastering CSS Basics: Styling Your First Web Page"**  

---

### **📋 Objectives**  
- Understand the use of CSS selectors, properties, and values.  
- Apply inline, internal, and external CSS to style web pages.  
- Utilize basic CSS properties to control colors, fonts, alignment, padding, and margins.  

---

### **📂 Assignment Tasks**  

#### **Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)**  
1. Create an HTML file with at least three different types of elements (e.g., `<h1>`, `<p>`, `<div>`).  
2. Style these elements using:  
   - **Element Selector**: Change the font size of all headings.  
   - **Class Selector**: Apply a background color to specific sections.  
   - **ID Selector**: Add a border to an element with a unique ID.
index.html
   <!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Basics</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <h1>Welcome to CSS Basics</h1>
  <p>This is a paragraph explaining the basics of CSS.</p>
  <div class="highlight">This section is styled using a class selector.</div>
  <div id="unique-section">This section has a unique style applied using an ID selector.</div>
</body>
</html>


style.css/* Element Selector: Change the font size of all headings */
h1 {
  font-size: 32px;
  color: darkblue;
}

/* Class Selector: Apply a background color to specific sections */
.highlight {
  background-color: lightyellow;
  padding: 10px;
  margin: 10px 0;
}

/* ID Selector: Add a border to an element with a unique ID */
#unique-section {
  border: 2px solid darkgreen;
  padding: 10px;
  margin: 10px 0;
}

---

#### **Part 2: Inline, Internal, and External CSS (30 Points)**  
1. Use **inline CSS** to style one element (e.g., change the text color).  
2. Add **internal CSS** in the `<style>` tag within the `<head>` section to style at least three elements.  
3. Create a separate **external CSS file** and link it to your HTML. Use it to:  
   - Change the background color of the webpage.  
   - Style links with hover effects.


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Types</title>
  <!-- Internal CSS -->
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }

    h1 {
      color: navy;
      text-align: center;
    }

    .highlight {
      background-color: lightblue;
      padding: 10px;
      border-radius: 5px;
    }

    #unique-section {
      font-size: 18px;
      border: 1px solid gray;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <!-- Inline CSS -->
  <h1 style="color: darkgreen;">Inline, Internal, and External CSS</h1>

  <p>This paragraph demonstrates the use of CSS in various forms.</p>

  <!-- Element with a class styled using Internal CSS -->
  <div class="highlight">This section is styled using internal CSS (class selector).</div>

  <!-- Element with an ID styled using Internal CSS -->
  <div id="unique-section">This section is styled using internal CSS (ID selector).</div>
</body>
</html>

/* Basic Page Styling */
body {
  font-family: 'Arial', sans-serif;
  background-color: #f0f8ff; /* Light blue background */
  color: #333; /* Dark gray text */
  margin: 0;
  padding: 0;
}

/* Header Styling */
header {
  background-color: #4682b4; /* Steel blue */
  color: white;
  text-align: center;
  padding: 20px 0;
  margin-bottom: 20px;
}

/* Intro Paragraph Styling */
.intro {
  font-size: 18px;
  font-weight: 400;
  text-align: justify;
  margin: 20px;
  padding: 10px;
  background-color: #fdf5e6; /* Light beige */
  border-left: 5px solid #ffa07a; /* Light salmon */
}

/* Content Section Styling */
.content {
  margin: 20px;
  padding: 15px;
  background-color: #e6e6fa; /* Lavender */
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.content h2 {
  font-size: 24px;
  font-weight: bold;
  text-align: left;
  margin-bottom: 10px;
}

.content p {
  font-size: 16px;
  font-weight: 300;
  line-height: 1.6;
  text-align: left;
  margin-bottom: 10px;
}

---

#### **Part 3: Basic Styling Properties (50 Points)**  
1. Apply the following styles:  
   - **Colors**: Set text and background colors for different elements.  
   - **Font Styles**: Change the font family, size, and weight of text.  
   - **Text Alignment**: Center-align, left-align, or justify text in paragraphs.  
   - **Spacing**: Add padding and margin to elements for proper spacing.
  
2. 

3. Create a **simple card component** using these styles:  
   - A heading for the card title.  
   - A paragraph with some description.  
   - Add padding inside the card and a margin around it.  
   - Use a light background color and a subtle border.  
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Card Component</title>
  <link rel="stylesheet" href="card-styles.css">
</head>
<body>
  <div class="card">
    <h3 class="card-title">Card Title</h3>
    <p class="card-description">This is a simple card component. It is styled with padding inside, a light background color, a subtle border, and margin around it to create spacing.</p>
  </div>
</body>
</html>

```

This assignment will solidify your CSS basics while giving you a chance to style your first webpage creatively. Good luck and happy styling! 🎨🚀
