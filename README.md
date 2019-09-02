# code-line-daily

A line of code of the day.

## API

First version of an API is available!

URL: [https:cld.silvestar.codes/.netlify/functions/](https:cld.silvestar.codes/.netlify/functions/)

Methods:
- `/get-random-line`
  - Returns random line
  - Link structure: https://cld.silvestar.codes/get-random-line
- `/get-all-lines`
  - Returns every line
  - Link structure: https://cld.silvestar.codes/get-all-lines
- `/get-lines-by-lang/:lang:`
  - Returns every line by language provided
  - Link structure: https://cld.silvestar.codes/get-lines-by-lang/:lang:
  - Parameter [required, case insensitive]: `:lang:`
  - Languages: `HTML`, `CSS`, `JavaScript`, `PHP`, `Nodejs`
- `/get-line-by-lang/:lang:`
  - Returns latest line by language provided
  - Link structure: https://cld.silvestar.codes/get-line-by-lang/:lang:
  - Parameter [required, case insensitive]: `:lang:`
  - Languages: `HTML`, `CSS`, `JavaScript`, `PHP`, `Nodejs`
- `/get-line-by-date/:date:`
  - Returns latest line to the date provided
  - Link structure: https://cld.silvestar.codes/get-line-by-date/:date:
  - Parameter [required] : `:date:`
  - Date format: `YYYY-MM-DD`

# ToDo

- README
- CONTRIBUTE
- Progressive web app
- Browser extension
- Newsletter
- Sorting
- Categories
