# FoxPro_JSONParser
Parser to JSON text objects.
```
You can use this class to convert JSON text to FoxPro objects.
``` 
## Example
```
set classlib to util.vcx
oParser = createobject("JSONParser")
oPerson = oParser.ConvertToObject('{"nome" : "Graciano"}')
? oPerson.nome
```
