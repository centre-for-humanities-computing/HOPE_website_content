# Editing content for the HOPE website

Please be careful when editing these files, they follow strict syntactic rules.

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

[Markown convention used](https://markdown-it.github.io/)

caveats: too few or too many whitespace characters?

### JSON files

people.json uses the JSON standard.

[JSON standard](https://www.json.org/json-en.html)

caveats: 
  - comma after the last item in an array?
  - single quotes instead of double quotes?
  - forgot to quote string value?
  - typos?
