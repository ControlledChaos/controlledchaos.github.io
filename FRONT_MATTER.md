# Front Matter Guide

Front matter is metadata assigned to a file, in the context of Jekyll. There are core matter tags, such as "title", but this website/theme uses many custom tags.

This guide describes how the tags are used and in which files.

## Posts

Posts are the core pages for the blog feature.

- **subtitle**
  This should be a brief, introductory statement regarding the post.
  
  The subtitle is used in various templates, immediately following the post title. It is also used in the `<head>` for description meta tags.
  
  **Type:** string
  **Accepts:** General text, no HTML or other markup.
  
  **Used in:**
  - `_includes/head.html`
  - `_includes/posts-preview.html`
  - `_includes/posts-full.html`
  - `_includes/featured-posts-grid.html`
  - `_includes/related-posts.html`
  - `_layouts/post.html`
  - `_layouts/default.html`

- **post_image**
  This is the featured image of the post.
  
  The post image is used in post archive pages, in single post pages, and in posts grid components. It is also used in the `<head>` for image meta tags.
  
  **Type:** string
  **Accepts:** filename + extension (e.g. "my-photo.jpg")
  
  This theme uses a custom directory structure for post images.
  
  **Used in:**
  - `_includes/head.html`
  - `_includes/posts-preview.html`
  - `_includes/posts-full.html`
  - `_includes/featured-posts-grid.html`
  - `_includes/related-posts.html`
  - `_layouts/post.html`
  