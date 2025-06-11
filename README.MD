
---

# 🌟 Emmet HTML Cheat Sheet

## 🔹 Basic Boilerplate

```emmet
!
```

➡️ Expands to full HTML5 template.

---

## 🔹 Tags

| Emmet            | Output                                 |
| ---------------- | -------------------------------------- |
| `div`            | `<div></div>`                          |
| `ul>li*3`        | `<ul><li></li><li></li><li></li></ul>` |
| `p{Hello}`       | `<p>Hello</p>`                         |
| `span.red`       | `<span class="red"></span>`            |
| `a:link`         | `<a href=""></a>`                      |
| `input:password` | `<input type="password">`              |

---

## 🔹 Classes and IDs

| Emmet               | Output                                |
| ------------------- | ------------------------------------- |
| `.box`              | `<div class="box"></div>`             |
| `#main`             | `<div id="main"></div>`               |
| `div.container.row` | `<div class="container row"></div>`   |
| `.btn.btn-success`  | `<div class="btn btn-success"></div>` |

---

## 🔹 Text Content

| Emmet           | Output                      |
| --------------- | --------------------------- |
| `h1{Welcome}`   | `<h1>Welcome</h1>`          |
| `a{Click here}` | `<a href="">Click here</a>` |

---

## 🔹 Attributes

| Emmet                      | Output                               |
| -------------------------- | ------------------------------------ |
| `input[type=text]`         | `<input type="text">`                |
| `input:submit[value=Send]` | `<input type="submit" value="Send">` |
| `img[src="logo.png"]`      | `<img src="logo.png" alt="">`        |

---

## 🔹 Nesting & Repetition

| Emmet                 | Output                        |
| --------------------- | ----------------------------- |
| `nav>ul>li*3>a`       | Navigation list with 3 links  |
| `div>section>p{Text}` | Nested content with paragraph |
| `table>tr*2>td*3`     | Table with 2 rows × 3 columns |

---

## 🔹 Bootstrap Examples

| Emmet                                   | Output                                                    |
| --------------------------------------- | --------------------------------------------------------- |
| `div.container`                         | `<div class="container"></div>`                           |
| `div.row>div.col-md-6`                  | Bootstrap 2-column row                                    |
| `button.btn.btn-primary{Click}`         | `<button class="btn btn-primary">Click</button>`          |
| `input:submit.btn.btn-dark[value=Send]` | `<input type="submit" class="btn btn-dark" value="Send">` |

---

## 🔹 Tips for VS Code

* Ensure `"emmet.triggerExpansionOnTab": true` is set in `settings.json`.
* Use `.html` file type for full support.
* For Emmet in plaintext, add:

  ```json
  "emmet.includeLanguages": {
    "plaintext": "html"
  }
  ```

---


