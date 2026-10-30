HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic Portfolio & Tech Blog - Alex Morgan</title>
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1>Alex Morgan's Tech Journal</h1>
        <p>Exploring web development, semantic HTML, and modern accessibility standards.</p>
        
        <nav aria-label="Main Navigation">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="semantic-page.html">Articles</a></li>
                <li><a href="college-info.html">College Info</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content Area -->
    <main>
        
        <!-- Primary Content Section -->
        <section>
            <h2>Latest Insights</h2>
            <p>Welcome to my tech articles and development journal. Here I share tutorials, lessons learned, and best practices for writing clean code.</p>

            <!-- Article Element: Self-contained piece of content -->
            <article>
                <h3>Why Semantic HTML Matters for Accessibility</h3>
                <p>Published on October 30, 2026 by <strong>Alex Morgan</strong></p>
                
                <figure>
                    <img src="images/coding-workspace.jpg" alt="A well-organized coding desk showing a screen with clean HTML code and accessible markup guidelines" width="500" height="300">
                    <figcaption>Writing clean, semantic HTML improves screen reader navigation and SEO.</figcaption>
                </figure>

                <p>Using generic <code>&lt;div&gt;</code> tags everywhere can make a webpage difficult for screen readers and search engine crawlers to parse. By replacing them with meaningful semantic elements like <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;article&gt;</code>, and <code>&lt;section&gt;</code>, we provide structural context that benefits all users.</p>
            </article>
        </section>

        <!-- Aside Element: Tangentially related sidebar content -->
        <aside>
            <h2>Quick Facts & Links</h2>
            <h3>Recent Tags</h3>
            <ul>
                <li><a href="#html">#HTML5</a></li>
                <li><a href="#accessibility">#Accessibility</a></li>
                <li><a href="#webdev">#WebDevelopment</a></li>
            </ul>
            
            <h3>Recommended Tools</h3>
            <p>Check out the <a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a> for comprehensive HTML guides.</p>
        </aside>

    </main>

    <!-- Footer Element -->
    <footer>
        <p>&copy; 2026 Alex Morgan. Built with semantic HTML5 and accessibility in mind.</p>
    </footer>

</body>
</html>
Key Improvements Made for This Assignment:
Semantic Structure: Replaced generic layout <div> containers with purpose-built semantic tags (<header>, <nav>, <main>, <section>, <article>, <aside>, and <footer>).

Correct Navigation Scope: Placed navigation links cleanly inside a <nav> tag with an aria-label for screen reader clarity.

Hierarchy & Accessibility: Maintained a strict heading order (<h1> for the page title, <h2> for section headers, and <h3> for article subheadings) and added rich, descriptive alternative text for the image.

Steps to Complete Your Submission:
Save the File: Copy the code above and save it in your project folder as semantic-page.html.

Prepare Screenshots (Before vs. After):

Before: Take a screenshot of an old non-semantic version (or visualize a page packed entirely with <div class="header">, <div class="content">, etc.).

After: Open your newly created semantic-page.html in your web browser and take a screenshot showing how clean and structured it looks.

Final Submission: Submit your updated semantic-page.html file along with your before and after screenshots.