# Dom Element Type
All the types of nodes in htmlparser2's dom for deno

## Using

```
import * as DomType from 'https://raw.githubusercontent.com/DenoBRComunitty/domelementtype/master/mod.ts';

console.log(DomType.Text);
```
# Available Types

- Text = "text" `//Text`
- Directive = "directive" `//<? ... ?>`
- Comment = "comment" `//<!-- ... -->`
- Script = "script" `//<script> tags`
- Style = "style" `//<style> tags`
- Tag = "tag" `//Any tag`
- CDATA = "cdata" `//<![CDATA[ ... ]]>`
- Doctype = "doctype"

