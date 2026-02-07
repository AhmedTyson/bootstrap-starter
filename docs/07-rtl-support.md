<div dir="rtl">

# 7. دعم RTL والعربية (RTL Support) &rlm;

كلاسات لدعم النصوص العربية واتجاه الكتابة من اليمين لليسار. &rlm;

## الكود: &rlm;

```css
/* للنص العربي */
.arabic-text,
.rtl {
    direction: rtl;        /* اتجاه الكتابة من اليمين */
    text-align: right;     /* محاذاة النص لليمين */
}

/* للنص الإنجليزي */
.ltr {
    direction: ltr;        /* اتجاه الكتابة من اليسار */
    text-align: left;      /* محاذاة النص لليسار */
}
```

## شرح الخصائص: &rlm;

| الخاصية | القيمة | الوظيفة |
|---------|--------|---------|
| `direction` | `rtl` | يغير اتجاه الكتابة لليمين |
| `direction` | `ltr` | يغير اتجاه الكتابة لليسار |
| `text-align` | `right` | يحاذي النص لليمين |
| `text-align` | `left` | يحاذي النص لليسار |

## أمثلة: &rlm;

### نص عربي بسيط: &rlm;
```html
<p class="arabic-text">
    مرحباً بك في موقعنا الإلكتروني
</p>
```

### قسم كامل بالعربي: &rlm;
```html
<section class="rtl">
    <h2>عنوان القسم</h2>
    <p>هذا النص سيكون من اليمين لليسار</p>
    <ul>
        <li>العنصر الأول</li>
        <li>العنصر الثاني</li>
    </ul>
</section>
```

### محتوى ثنائي اللغة: &rlm;
```html
<div class="rtl">
    <h2>مرحباً</h2>
    <p class="ltr">This is English text inside an RTL container</p>
    <p>وهذا نص عربي</p>
</div>
```

## نصيحة: &rlm;

للمواقع العربية الكاملة، أضف `dir="rtl"` على الـ `<html>` مباشرة: &rlm;

```html
<html lang="ar" dir="rtl">
```

</div>
