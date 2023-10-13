## **Modern Landing Page Tutorial**

### **Step 1: Basic HTML Setup**

Start by creating an HTML file named `landing-page.html`.

Inside the file, lay down the basic structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Metadata for character encoding and viewport -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Title of the webpage -->
    <title>Landing Page</title>

    <!-- Link to Bootstrap CSS for styling and FontAwesome icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

</body>
</html>
```

🔍 **Preview:** A blank webpage.

### **Step 2: Navigation Bar**

Inside the `<body>` tag, add the navigation bar. Place this code just after the opening `<body>` tag:

```html
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand" href="#">MyBrand</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Features</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
```

🔍 **Preview:** A dark navigation bar with the brand name and menu items centered due to the container.

### **Step 3: Hero Section with Background Image**

Below the navigation bar (still within the `<body>` tag), insert the hero section:

```html
<section class="hero text-white text-center d-flex justify-content-center align-items-center" style="background-image: url('https://source.unsplash.com/random/1920x1080'); background-size: cover; background-position: center; height: 100vh;">
    <div class="container">
        <h1>Welcome to MyBrand</h1>
        <p>Experience the best products and services.</p>
        <button class="btn btn-light">Learn More</button>
    </div>
</section>
```

🔍 **Preview:** The hero section will now display a random image from `Unsplash` as its background, spanning the entire viewport height. The text and button remain centered and are displayed on top of the image.

### **Step 4: Features Section**

Next, right after the closing `</section>` tag of the hero section, insert the features section:

```html
<section class="features py-5">
    <div class="container">
        <!-- Add your feature items here -->
    </div>
</section>
```

🔍 **Preview:** Space for three columns each with an icon, a heading, and some text describing features.

### **Step 5: Call to Action & Footer**

After the features section, add the call-to-action (CTA) section and the footer:

```html
<section class="cta bg-dark text-white text-center py-5">
    <div class="container">
        <!-- Add your CTA content here -->
    </div>
</section>

<footer class="text-center py-3">
    <div class="container">
        <!-- Add your footer content here -->
    </div>
</footer>
```

🔍 **Preview:** A dark-colored CTA section followed by a footer at the very bottom, both centered with the help of containers.

### **Step 6: JavaScript**

At the very end, just before the closing `</body>` tag, insert the Bootstrap JavaScript bundle:

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
```

---

After following these steps, you'll have a foundation for a modern landing page. Each section has been detailed with where to place it in the file. Adjust the content, styles, and images as per your needs.
