# Javascript ES6-Problem

### Problem
- **จงแก้ไขให้โปรแกรมสามารถทำงานได้อย่างถูกต้อง**

> Tips

- Destructuring
- Promise / Async Await
- Arrays Manuipulation

## Installation

- To mock an API you need `json-server` to get started
```shell
$ npm install -g json-server
$ json-server db.json
```
---
**Before Edit**

![Recordit GIF](http://g.recordit.co/aAI4QOJ3Pc.gif)

## Sample of app.js

```javascript
searchInput.addEventListener('input', function (e) {
  const kw = this.value
  products = copyProducts.filter(product => {
    return product.title.toLowerCase().includes(kw.trim().toLowerCase())
  })
  renderProduct()
})

const initializeApplication = async () => {
  const { data } = await axios.get('http://localhost:3000/products')
  products = data
  copyProducts = products
  renderProduct()
}

```

---

**Result**

![Recordit GIF](http://g.recordit.co/4XvT9lFJ4E.gif)

---
### เงื่อนไข

- **สามารถใช้ได้ทุกอย่างจากที่เรียนไป**



