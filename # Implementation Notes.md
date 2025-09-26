# Implementation Notes

## What is Semantic HTML?

Semantic HTML uses meaningful tags instead of just `<div>` tags everywhere.

## Basic Semantic Tags

### Page Structure
- `<header>` - Top of the page (logo, navigation)
- `<main>` - Main content area
- `<footer>` - Bottom of the page (copyright, contact)

### Content Tags
- `<article>` - A complete piece of content (blog post, news article)
- `<section>` - A section within an article
- `<aside>` - Side content (sidebar, related links)
- `<nav>` - Navigation menu

### Text Tags
- `<h1>` to `<h6>` - Headings (use in order)
- `<p>` - Paragraphs
- `<time>` - Dates and times

## Simple Example

```html
<header>
  <h1>My Website</h1>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
    </ul>
  </nav>
</header>

<main>
  <article>
    <h2>My Blog Post</h2>
    <time datetime="2024-01-15">January 15, 2024</time>
    <p>This is my blog post content...</p>
  </article>
</main>

<footer>
  <p>&copy; 2025 My Website</p>
</footer>