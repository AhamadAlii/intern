
# HTML Uniform Resource Locators

A URL is another word for a web address.

A URL can be composed of words (e.g. `w3schools.com`), or an Internet Protocol (IP) address (e.g. `192.68.20.50`).

Most people enter the name when surfing, because names are easier to remember than numbers.

## URL - Uniform Resource Locator

Web browsers request pages from web servers by using a URL.

A Uniform Resource Locator (URL) is used to address a document (or other data) on the web.

A web address like `https://www.w3schools.com/html/default.asp` follows these syntax rules:

```
scheme://prefix.domain:port/path/filename
```

### Explanation:

- **scheme** - defines the type of Internet service (most common is http or https)
- **prefix** - defines a domain prefix (default for http is www)
- **domain** - defines the Internet domain name (like w3schools.com)
- **port** - defines the port number at the host (default for http is 80)
- **path** - defines a path at the server (If omitted: the root directory of the site)
- **filename** - defines the name of a document or resource

## Common URL Schemes

| Scheme | Short for                          | Used for                          |
|--------|------------------------------------|-----------------------------------|
| http   | HyperText Transfer Protocol        | Common web pages. Not encrypted   |
| https  | Secure HyperText Transfer Protocol | Secure web pages. Encrypted       |
| ftp    | File Transfer Protocol             | Downloading or uploading files    |
| file   |                                    | A file on your computer           |

## URL Encoding

URLs can only be sent over the Internet using the ASCII character-set. If a URL contains characters outside the ASCII set, the URL has to be converted.

URL encoding converts non-ASCII characters into a format that can be transmitted over the Internet.

URL encoding replaces non-ASCII characters with a `%` followed by hexadecimal digits.

URLs cannot contain spaces. URL encoding normally replaces a space with a plus (+) sign, or `%20`.

### Try It Yourself

Example: `Hello Günter`

If you click "Submit", the browser will URL encode the input before it is sent to the server.

A page at the server will display the received input.

Try some other input and click Submit again.

## ASCII Encoding Examples

Your browser will encode input, according to the character-set used in your page.

The default character-set in HTML5 is UTF-8.

| Character | From Windows-1252 | From UTF-8 |
|-----------|-------------------|------------|
| €         | %80               | %E2%82%AC  |
| £         | %A3               | %C2%A3     |
| ©         | %A9               | %C2%A9     |
| ®         | %AE               | %C2%AE     |
| À         | %C0               | %C3%80     |
| Á         | %C1               | %C3%81     |
| Â         | %C2               | %C3%82     |
| Ã         | %C3               | %C3%83     |
| Ä         | %C4               | %C3%84     |
| Å         | %C5               | %C3%85     |
