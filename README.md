# keycodes
A collection of key code mappings

## How to use
`npm install --save key_codes`

    var keys = require('key_codes');

    switch(evt.keyCode){
      case keys.a:
        console.log('Got an a');
        break;
      case keys.enter:
        console.log('Got an enter');
        break;
    }
    
## FAQ
### Where's a full listing of the keycodes? 
See source for a full list of keycodes.
