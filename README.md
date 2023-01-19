**This project is no longer active developement, please see [CoolQLCool](https://www.github.com/AppleKevin1106/ja-apis-nodejs) for a similar more active project ([ref]

Using API you can simply generate JSON data from any website.

All the attributes you provide as JSON will be put inside of the value property, and the index property is to be able to track what index it ocurred in the DOM. I nested JSON values into it's own so that you can still have an "index" property returned and not run into issues.

## How it works
Main power of the program is in `services/html_to_json.js`. Start site with `node index` after doing `npm install`.

