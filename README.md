# HTTP Memes

A collection of meme images for HTTP status codes, inspired by [http.cat](https://http.cat).

## How to use

Simply access the meme image of an HTTP status code by appending the status code and `.jpg` to the base URL:

```
https://httpmemes.netlify.app/{status_code}.jpg
```

### Examples

**Using curl:**

```bash
curl https://httpmemes.netlify.app/404.jpg --output 404.jpg
```

**Direct URL in browser:**

```
https://httpmemes.netlify.app/200.jpg
https://httpmemes.netlify.app/500.jpg
https://httpmemes.netlify.app/418.jpg
```

**In HTML:**

```html
<img src="https://httpmemes.netlify.app/404.jpg" alt="HTTP 404" />
```

Browse all available memes at [httpmemes.netlify.app](https://httpmemes.netlify.app)

## Contribute

You can help keep the memes fresh and relevant!

### Meme Requirements

- Must be an empty meme template or a reaction image (no text overlays except built-in meme text). The meme template itself should convey the meaning and not the meme text.
- Must have a width of **1000px** (height can vary to maintain aspect ratio).
- JPG format only (for now).

### How to Contribute

#### Option 1: Pull Request

1. **Fork the repository** on GitHub
2. **Add your image** to the `images/` directory
   - Replace the image with your new meme (e.g. `404.jpg`)
   - You can replace multiple images in one pull request
3. **Create a pull request** with:
   - A title with the status code(s) you're updating
   - Why you think it's appropriate for that status code

#### Option 2: GitHub Issue

1. **Create a new issue**
2. **Include in your issue**:
   - Link to or attach the meme image
   - Which HTTP status code you think it fits
   - Why you think it's appropriate for that status code

Thank you for contributing!

## To-do

- [x] Complete all HTTP status codes
- [ ] Support multiple file extensions
- [ ] Host in a custom domain
