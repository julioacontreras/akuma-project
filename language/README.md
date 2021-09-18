
## Simple example

Model example with name
``````json
{
  "name": "user"
}
``````

Template example when will get name in model, using function capitalize to 
transform `user` to `User` creating a Alias. This alias content tenmplate `in ♦classController♦Controller`.
``````
## aliases ##
♦classController♦ ← ⟨#capitalize⟩⟨data.name⟩⟨/capitalize⟩

---
⟨#data⟩
class ♦classController♦Controller {
}
⟨/data⟩

```

The engine get model and template and process creating this code.
```
class UserController {
}

```

## Syntaxe

The template is devide in two parts.
`Header` and `Content` separate with this `---`

```
## header ##
---
content
```
