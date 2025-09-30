### Patch Request Syntax Examples

The following examples specify diffrent syntax for performing a patch operation on a complex attribute:

 ```json
   {
      "op": "replace",
      "path": "name.givenName",
      "value": "Laila"
   }
 ```

 ```json
  {
      "op": "replace",
      "value": {
        "name": {
          "givenName": "Laila"
        }
      }
  }
 ```

```json
{
      "op": "replace",
      "value": {
        "name.givenName": "Obie"
        }
}
```
