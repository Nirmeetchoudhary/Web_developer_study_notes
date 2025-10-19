
### 1️⃣ How to Apply CSS (3 Ways)

```html
<!-- Inline -->
<h1 style="color: red;">Hello</h1>

<!-- Internal -->
<style>
  h1 { color: blue; }
</style>

<!-- External (Best Way) -->
<link rel="stylesheet" href="style.css">
```

---

### 2️⃣ Selectors (Most Important)

| Selector Type | Example      | Meaning                   |
| ------------- | ------------ | ------------------------- |
| Element       | `p {}`       | All `<p>` tags            |
| Class         | `.box {}`    | Elements with class="box" |
| ID            | `#header {}` | Element with id="header"  |

```css
h1 { color: green; }
.box { background: yellow; }
#header { padding: 20px; }
```

---

### 3️⃣ Colors, Fonts & Text

```css

/* Text color */
p { color: #333; }

/* Background color */
div { background-color: lightyellow; }

/* Gradient background */
body { background: linear-gradient(to right, #ff7e5f, #feb47b); }

/* Background image */
.hero { background-image: url('image.jpg'); }


body { 
  font-family: Arial, sans-serif;
  color: #333;
  background-color: #f8f8f8;
}

h1 {
  font-size: 32px;
  text-align: center;
}
```

---

### 4️⃣ Box Model (Most Important Concept in CSS)

Every element is a box:

```
---------------------------------
|         Margin               |
|  -------------------------   |
|  |       Border          |   |
|  |  ------------------   |   |
|  |  | Padding        |   |   |
|  |  |  Content       |   |   |
|  |  ------------------   |   |
|  -------------------------   |
---------------------------------
```

.card {
  padding: 20px;  /* Space inside */
  margin: 10px;   /* Space outside */
  border: 2px solid black;
}

```css
div {
  padding: 10px;
  border: 1px solid black;
  margin: 20px;
}
```

---

### 5️⃣ Width, Height & Display

```css
.box { width: 200px; height: 100px; display: inline-block; }
```

| Display Type   | Behavior                 |
| -------------- | ------------------------ |
| `block`        | Full-width, new line     |
| `inline`       | In line, no width/height |
| `inline-block` | Inline + allows size     |

---

### 6️⃣ Positioning (For Layouts)

```css
.relative { position: relative; top: 10px; left: 20px; }
.absolute { position: absolute; top: 50px; right: 10px; }
.fixed { position: fixed; bottom: 0; width: 100%; }
```

---

### 7️⃣ Flexbox (The KING of Layouts)

```css
.container {
  display: flex;
  justify-content: center;   /* left / center / space-between */
  align-items: center;       /* vertical alignment */
}
```

---

### 8️⃣ Responsive Design (Mobile-friendly)

```css
@media (max-width: 600px) {
  body { font-size: 14px; }
}
```

---
