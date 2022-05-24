# -=Markdown_exercises=-<a name="up"></a> 

# Level 1 Heading

## Level 2 Heading

### Level 3 Heading

#### Level 4 Heading 

--- 

# Not Recommended 

##### Level 5 Heading

###### Level 6 Heading 

---

## Bold And Italic

_Italic text here_

**Bold text here** 

Testing a line break right  
there^

---

## Lists

1. Item 1
2. Item 2
    1. Sub-Item 1 of Item 2
    2. Sub-Item 2 of Item 2
3. Item 3
4. Item 4
    - Some info from item 4
    - Another info from item 4

- [ ] Day 2 onboarding
            - [x] Learning markdown basics
            - [ ] Further .... 

---

## Links And Images

Check out [Some random link](https://randomuser.me/)

![Random Image](https://picsum.photos/200/300)

---

## Code, Code Blocks And Block Qoutes

`$some_variable`

```markdown
# Code Example
$contribuabil->idUser = Auth::user()->id;
$contribuabil->save(); // lementi idUser infot 
```

```php
public function update(StoreContribuabilForm $request, Contribuabil $contribuabil)
    {
        $request->validated();
        $contribuabil->fill(request()->all());
        $contribuabil->idUser = Auth::user()->id;
        $contribuabil->save();

        return redirect('contribuabil')->with('search', request()->get('nrROL'));
    }
```

> Blockquote.
>> Nested Blockquote

---

<details>
    <summary>Day 1</summary>
    <p>Day 1 onboarding procedure</p>
</details>
    
<details>
     <summary>Day 2</summary>
     <p>Day 2 onboarding procedure</p>
</details>

[GO TO TOP](#up)

:thumbsup:    
    
---
