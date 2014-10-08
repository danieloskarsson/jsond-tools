# JSOND tools

## json2jsond

`./json2jsond '{"name": "daniel", "age": 1, "student": false, "list": ["a", "b", {"c":"d"}, {"c":"e"}], "None": null, "test": false}'`

```
{
    "name": "string", 
    "age": "integer", 
    "student": "boolean", 
    "list": [
        "string", 
        {
            "c": "string"
        }
    ], 
    "None": null, 
    "test": "boolean"
}
```
