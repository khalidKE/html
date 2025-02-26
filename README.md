# HTML (HyperText Markup Language) 

## What is a "Doctype"?
The "Doctype" is a small line at the beginning of an HTML page that tells the browser how to properly render the page. It’s like a declaration at the start that specifies the type of HTML the page is written in.

Example:
```html
<!DOCTYPE html>
```

## Rendering Modes in Browsers
### Full Standards Mode
The browser renders the page according to modern HTML and CSS standards.

### Almost Standards Mode
The browser uses modern standards but makes minor exceptions to work with older browsers.

### Quirks Mode
The browser renders the page using old methods to mimic how older browsers displayed pages.

## Difference Between HTML and XHTML
- **HTML5**: Case-insensitive, meaning it doesn’t care about uppercase or lowercase letters.
- **XHTML**: Case-sensitive, requiring proper use of uppercase and lowercase letters.

### Issue with Hosting Pages as `application/xhtml+xml`?
Yes, some browsers don’t support this type of page.

## Adding a Multilingual Page
There are several ways to do this:

1. **Using the `lang` attribute**:  
   Example: `<p lang="en">This is English text.</p>`

2. **Setting the primary language in `<html>`**:  
   Example: `<html lang="ar">`

3. **Content Translation**: Provide versions of the text in different languages within the same page.
4. **Translation Files**: Store translations in JSON or XML files and load them based on the user’s language.
5. **Using CMS (Content Management Systems)**: Tools like WordPress make it easy to manage pages with multiple languages.

## Difference Between Cookies, `sessionStorage`, and `localStorage`

| Feature           | Local Storage | Cookies | Session Storage |
|------------------|--------------|---------|----------------|
| **Storage Size** | ~10MB        | ~4KB    | ~5MB          |
| **Persistence**  | Permanent    | Can expire or be session-based | Deleted on tab close |
| **Controlled By** | Browser      | Server & Client | Client only |
| **Use Case**     | Storing long-term data like user settings | Authentication, user preferences | Temporary storage per session |
