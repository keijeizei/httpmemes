# HTTP Memes

A collection of meme images for HTTP status codes, inspired by [http.cat](https://http.cat).

## How to use

Simply access the meme image of an HTTP status code by appending the status code and `.jpg` to the base URL:

```
https://httpmemes.com/{status_code}.jpg
```

### Examples

**Using curl:**

```bash
curl https://httpmemes.com/404.jpg --output 404.jpg
```

**Direct URL in browser:**

```
https://httpmemes.com/200.jpg
https://httpmemes.com/500.jpg
https://httpmemes.com/418.jpg
```

**In HTML:**

```html
<img src="https://httpmemes.com/404.jpg" alt="HTTP 404" />
```

Browse all available memes at [httpmemes.com](https://httpmemes.com)

## Contribute

You can help keep the memes fresh and relevant!

### Meme Requirements

- Must be an empty meme template or reaction image (no text overlays except built-in meme text). The meme template itself should convey the meaning and not the meme text.
- Must have a width of **1000px** (height can vary to maintain aspect ratio).
- JPG format only (for now).

### Adding the Status Code Caption

Currently, we don't have a template or an automated way to add the HTTP status code captions to the memes. I used the [esmBot](https://esmbot.net/) Discord bot to add captions to the memes. If you are not able to add a caption, simply create an issue (See Option 2 below) and I will push your image with the meme caption.

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

- [x] Complete all standard HTTP status codes
- [x] Host in a custom domain
- [ ] Support multiple file extensions
- [ ] Include non-standard HTTP status codes
