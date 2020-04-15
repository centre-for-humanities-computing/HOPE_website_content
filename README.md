# Editing content for the HOPE website

Please be careful when editing these files, they follow strict syntactic rules.


While this website has dedicated pages with fixed content slots, markdown documents from the content repository can be viewed and linked to as individual pages with the following url template:

```
/#/document/:directory/:filename
```


## Procedure: 
Webmaster:
 - edit a file 
 - commit your changes with a concise note with the purpose of your change
 - notify Max to pull your changes
 
 Max:
 - login to the server in AU's VPN 
 - cd into the website directory
 - `git pull origin master`
 - `npm run build`

### Markdown files

markdown is rather forgiving, but its layout depends on whitespace

[Markdown convention used](https://markdown-it.github.io/)

caveats: too few or too many whitespace characters?

### JSON files

people.json uses the JSON standard.

[JSON standard](https://www.json.org/json-en.html)

caveats: 
  - comma after the last item in an array?
  - single quotes instead of double quotes?
  - forgot to quote string value?
  - typos?

