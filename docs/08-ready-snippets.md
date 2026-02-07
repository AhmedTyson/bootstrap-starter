<div dir="rtl">

# 8. القوالب الجاهزة (Ready Snippets) &rlm;

أكواد CSS جاهزة لمكونات شائعة الاستخدام. &rlm;

## 1. البطاقة الجاهزة (Ready Card): &rlm;

```css
.ready-card {
    background-color: #fff;
    border-radius: var(--radius-md);           /* زوايا دائرية */
    border: 1px solid rgba(0, 0, 0, 0.1);      /* حدود خفيفة */
    padding: var(--spacer-lg);                 /* مسافة داخلية */
    transition: transform var(--transition-base), 
                box-shadow var(--transition-base);
}

.ready-card:hover {
    transform: translateY(-5px);               /* رفع للأعلى */
    box-shadow: var(--shadow-md);              /* ظل */
}
```

### استخدام: &rlm;
```html
<div class="ready-card">
    <h3>عنوان البطاقة</h3>
    <p>محتوى البطاقة</p>
</div>
```

---

## 2. حاويات المحتوى: &rlm;

```css
/* حاوية ضيقة للنصوص */
.content-narrow {
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
}

/* حاوية واسعة للمحتوى */
.content-wide {
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;
}
```

### استخدام: &rlm;
```html
<article class="content-narrow">
    <h1>عنوان المقال</h1>
    <p>محتوى المقال الذي سيكون بعرض مريح للقراءة</p>
</article>
```

---

## 3. الفاصل (Divider): &rlm;

```css
.divider {
    height: 1px;
    background-color: rgba(0, 0, 0, 0.1);
    margin: var(--spacer-lg) 0;
}
```

### استخدام: &rlm;
```html
<p>القسم الأول</p>
<div class="divider"></div>
<p>القسم الثاني</p>
```

---

## 4. النص المتدرج (Text Gradient): &rlm;

```css
.text-gradient {
    background: linear-gradient(45deg, var(--primary-color), var(--info-color));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}
```

### استخدام: &rlm;
```html
<h1 class="text-gradient">عنوان بتدرج لوني جميل</h1>
```

---

## 5. الزر الدائري: &rlm;

```css
.btn-rounded {
    border-radius: var(--radius-pill);
}
```

### استخدام: &rlm;
```html
<button class="btn btn-primary btn-rounded">زر دائري</button>
```

</div>
