# Get Locale

Gets locale based on HTML lang attribute

## Install

`npm i get--html-locale`

## Usage

```javascript
import getHTMLLocale from 'get-html-locale'

const locale = getHTMLLocale()

console.log(locale)
```

_Output:_

```javascript
{
   code: 'en',
   lang: 'English',
   region: 'United States'
}
```
