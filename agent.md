# Agent Notes

## Blog Images

- When adding user-provided photos to blog posts, copy publishable assets into `public/images/notes/`.
- Strip EXIF metadata before publishing, especially GPS/location data.
- Preserve the original image composition in the article: do not crop, force a fixed aspect ratio, or use `object-fit: cover`.
- Show article photos at their natural ratio with `width: 100%` and `height: auto`.
- Do not place multiple personal photos together as a gallery unless explicitly requested. Prefer one image at one relevant point in the article.
- Place photos inside the article body near the paragraph they support, not directly under the title/lead by default.
- Use the user's requested captions as the source of truth, with only light punctuation cleanup.
