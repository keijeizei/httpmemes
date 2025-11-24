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

## To-do

- [x] Complete all standard HTTP status codes
- [x] Host in a custom domain
- [ ] Support multiple file extensions
- [ ] Include non-standard HTTP status codes
