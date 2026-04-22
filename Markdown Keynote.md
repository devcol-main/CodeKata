> ! Currently ! Under Construction!

Mark Down (MD) is a lightweight markup language that you can use to add formatting elements to plaintext text documents.

---
## Table of Contents


---

## Documentations and Useful Links
* [Markdown Guide](https://www.markdownguide.org/)
	* [Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
	* [Basic Syntax](https://www.markdownguide.org/basic-syntax/)

- [John Gruber’s Markdown documentation](https://daringfireball.net/projects/markdown/). The original guide written by the creator of Markdown.
- [Markdown Tutorial](https://www.markdowntutorial.com/). An open source website that allows you to try Markdown in your web browser.
- [Markdown Preview](https://markdownlivepreview.com/): Where you can edit MD in web

## Editors (FREE)
* Obsidian: https://obsidian.md/
* VS Code: https://code.visualstudio.com/



---

Callout: > 
> callout

---

Code Block: **```** 
````
```
insert code
```
````

* you can also put which programming language to use

|   |   |   |   |
|---|---|---|---|
|**Language**|**Markdown**|**Language**|**Markdown**|
|Bash|bash|JSON|json|
|C#|cs|Java|java|
|C++|cpp|JavaScript|javascript|
|CSS|css|PHP|php|
|Diff|diff|Perl|perl|
|HTML, XML|html|Python|python|
|HTTP|http|Ruby|ruby|
|Ini|ini|SQL|sql|


* if using C++
````
```cpp
printf("hello");
```
````

---


Link: `[title](https://www.example.com)`
Image `![alt text](image.jpg)`


## Linking to Heading IDs[](https://www.markdownguide.org/extended-syntax/#linking-to-heading-ids)

You can link to headings with custom IDs in the file by creating a [standard link](https://www.markdownguide.org/basic-syntax/#links) with a number sign (`#`) followed by the custom heading ID. These are commonly referred to as _anchor links_.

|Markdown|HTML|Rendered Output|
|---|---|---|
|`[Heading IDs](#heading-ids)`|`<a href="#heading-ids">Heading IDs</a>`|[Heading IDs](https://www.markdownguide.org/extended-syntax/#heading-ids)|

Other websites can link to the heading by adding the custom heading ID to the full URL of the webpage (e.g, `[Heading IDs](https://www.markdownguide.org/extended-syntax#heading-ids)`).

