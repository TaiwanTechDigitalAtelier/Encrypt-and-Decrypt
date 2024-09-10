# Encrypt-and-Decrypt
simple encrypt and decrypt method using js, mainly for creating static HTML password protected pages.

encrypted string would be included in the static page as a js variable
```js
let enc = "BO5kWuXcdozO857XAYiM2rLHFrrIQ8pWustD5a0vGKQXwzu28jIqjmAHytDdnJfAmbTog2U6zNAC8ZcNk8ynkGM76vbUJmrdoxYALgD7yfpLexa22pY1cpXklkdFQsP+7PtO1kEYpyy3xv5F1ME9isp/kmjA1nUxs7Ero0ExS2JXpI/ekDcLqlAmRuEjnlqcMhHkwSikTLDIhDEH6OZ82OPPk7hcZORXvB3r9U+5dYcyjTFOzroEEWYScwGQoNOp9VSPl77qqM0vPAhB3OqqRUKMKpRjSub7aUVcX1KcOUmxG2hWlFYgQATxNoayRlvYD3NVuWqYM8JajJCMjh/LLYWisBI63yUNU9JMjPpgFriRII0A3eQlbq/JBRQx8hsF7D3npy9Vj+n8DWWjTuVprWQDc+y8h5EGDoUy7l0/6V7dgAemn/2pvb/ZHU+xqxq0Opud2MTmCtE=:WqegOzp99tAug2l6";
```

have a text/password input field on the page somewhere with a submit button.
then have an empty div or span where the decrypted html can be inserted
on submit run the decrypt function, but instead of 
```js
document.getElementById('decryptedOutput').value = decryptedText;
```
do something like
```js
document.getElementById('decryptedOutput').innerHTML = decryptedText;
```