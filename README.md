# Awesome Readme
Summary of what you can add on your redame pages to make it more attractive


## Insert Image

```html
<p align="center">
  <img width="180" height="160" src="img/final.png">
</p>
```

Example: 
<p align="center">
  <img width="180" height="160" src="img/Professortocat_v2.png">
</p>


## Links and Urls
```bash
[GitHub Emoticones](https://gist.github.com/rxaviers/7360908)
```
Example:

[Complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908)

## Emoticones
You can copy paste from the here: [Complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908)
```bash
:blush: :sweat_drops: :innocent: :turtle:
```
Result:
:blush: :sweat_drops: :innocent: :turtle:

## Code

```bash
#bash  
    ```bash
    echo "Hello World!"
    ``` 
```
```bash 
# Python
    ```python
     print("Hello, World!")
    ```
```
```bash
# Html
    ```html   
        <img src="images/firefox-icon.png" alt="My test image">
    ```
```
Result:

```bash
echo "Hello World!"
```   
```python
print("Hello, World!")
```
```html   
<img src="images/firefox-icon.png" alt="My test image">
```


## List
```bash
- One
- Two
- Three
  - Three one
  - Three two
```
Result
- One
- Two
- Three
  - Three one
  - Three two


## Tables

```bash
| Value    | Description |
|--------- |-------------|
| 1        | Meli        |
| 2        | Aline       |
| 3        | Elian       |
```

Result:

| Value    | Description |
|--------- |-------------|
| 1        | Meli        |
| 2        | Aline       |
| 3        | Elian       |

## Mermaid diagrams


```mermaid
flowchart LR
A[Start]-->|Text| B(Round)
B-->C{Decision}
C-->|One| D[Result 1]
C-->|Two| E[Result 2]
```

```mermaid
flowchart TD
A[start]-->|Text| B(Round)
B-->C{Decision}
C-->|One| D[Result 1]
C-->|Two| E[Result 2]
```

```mermaid
pie
"Dogs":386
"Cats":85
"Rats":15
```

```mermaid
graph TD
A-->B
A-->C
B-->D
C-->D
```