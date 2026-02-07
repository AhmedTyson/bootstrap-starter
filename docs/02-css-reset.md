<div dir="rtl">

# 2. إعادة تعيين CSS الحديثة (Modern CSS Reset) &rlm;

الـ Reset هو كود نكتبه في البداية لإزالة التنسيقات الافتراضية للمتصفح. &rlm;

## لماذا نحتاج Reset؟ &rlm;

كل متصفح له تنسيقات افتراضية مختلفة (margins, paddings, fonts). &rlm;
الـ Reset يوحّد السلوك عبر جميع المتصفحات. &rlm;

## الكود: &rlm;

```css
/* إعادة تعيين كل العناصر */
*,
*::before,
*::after {
    margin: 0;          /* إزالة المسافات الخارجية */
    padding: 0;         /* إزالة المسافات الداخلية */
    box-sizing: border-box;  /* الـ padding يُحسب داخل العرض */
}

/* تمرير سلس */
html {
    scroll-behavior: smooth;
}

/* إعدادات الـ body */
body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    font-size: 1rem;
    line-height: 1.6;
    color: var(--text-primary);
    background-color: var(--bg-body);
}

/* الصور responsive */
img {
    max-width: 100%;
    height: auto;
    display: block;
}

/* الروابط */
a {
    text-decoration: none;
    color: var(--primary-color);
    transition: color var(--transition-fast);
}

a:hover {
    color: var(--primary-hover);
}

/* القوائم */
ul, ol {
    list-style: none;
}
```

## شرح `box-sizing: border-box` &rlm;

| الخاصية | السلوك |
|---------|--------|
| `content-box` (افتراضي) | الـ padding يُضاف على العرض |
| `border-box` | الـ padding يُحسب داخل العرض |

### مثال: &rlm;
```css
.box {
    width: 200px;
    padding: 20px;
}
/* مع content-box: العرض الفعلي = 240px */
/* مع border-box: العرض الفعلي = 200px ✓ */
```

</div>
