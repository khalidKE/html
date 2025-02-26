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

![image](https://github.com/user-attachments/assets/939c36c3-f121-4124-a868-1518ce76a38d)
![image](https://github.com/user-attachments/assets/b1d6191c-7d82-483e-b2da-8ebbe578b8b4)
![image](https://github.com/user-attachments/assets/c78cfcb6-9ba7-49be-817d-f2f5aaee5c05)
![image](https://github.com/user-attachments/assets/6687bf6e-68ad-4035-870f-7416b3e6877d)
![image](https://github.com/user-attachments/assets/6f4e4a7a-b770-4d8a-824e-544a9c176860)
![image](https://github.com/user-attachments/assets/b19752fc-5092-4d07-afcb-546ae3ca1092)
![image](https://github.com/user-attachments/assets/0a3c26a3-3a34-4a4c-ab63-07ae0dc08a0c)
![image](https://github.com/user-attachments/assets/55f9d536-9fea-48a0-9f0b-2e5fa3e258ec)
![image](https://github.com/user-attachments/assets/0f8c7550-dd85-42cf-87a6-6ed15ff37bee)






