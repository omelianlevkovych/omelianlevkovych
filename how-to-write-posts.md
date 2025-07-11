# How to Write New Blog Posts in Markdown

Your blog is fully set up to use Markdown! Here's everything you need to know:

## Creating a New Post

1. **Create a new file** in the `_posts/` directory
2. **Name it** with the format: `YYYY-MM-DD-title.md`
   - Example: `2025-01-15-my-awesome-post.md`

3. **Add front matter** at the top:
```yaml
---
layout: post
title: "Your Post Title"
date: 2025-01-15
tags: [tag1, tag2, tag3]
---
```

4. **Write your content** in Markdown below the front matter

## Markdown Features Available

✅ **Basic formatting**: **bold**, *italic*, `code`
✅ **Headings**: # H1, ## H2, ### H3, etc.
✅ **Lists**: ordered, unordered, and task lists
✅ **Links**: [text](url) and reference-style
✅ **Images**: ![alt text](image-url)
✅ **Tables**: with alignment and styling
✅ **Code blocks**: with syntax highlighting
✅ **Blockquotes**: for quotes and callouts
✅ **Footnotes**: for additional information
✅ **Task lists**: with checkboxes
✅ **Horizontal rules**: `---`

## Example Post Structure

```markdown
---
layout: post
title: "My New Post"
date: 2025-01-15
tags: [tech, programming]
---

# Introduction

Your opening paragraph goes here.

## Main Content

### Subsection

Write your content using markdown:

- Point 1
- Point 2
- Point 3

```javascript
// Code example
console.log("Hello, world!");
```

## Conclusion

Wrap up your thoughts here.
```

## Quick Start

The fastest way to create a new post:

```bash
# Create a new post file
touch _posts/$(date +%Y-%m-%d)-my-new-post.md

# Edit it with your favorite editor
code _posts/$(date +%Y-%m-%d)-my-new-post.md
```

## Preview Your Changes

Your Jekyll server should be running at http://localhost:4000 and will automatically reload when you save changes to your markdown files.

Happy writing! 🚀 