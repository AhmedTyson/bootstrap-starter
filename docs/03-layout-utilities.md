<div dir="rtl">

# 3. أدوات التخطيط (Layout Utilities) &rlm;

هذه كلاسات جاهزة للتوسيط والترتيب باستخدام Flexbox. &rlm;

## كلاسات التوسيط: &rlm;

```css
/* توسيط أفقي وعمودي */
.flex-center {
    display: flex;
    justify-content: center;  /* توسيط أفقي */
    align-items: center;      /* توسيط عمودي */
}

/* توسيط عمودي (العناصر فوق بعض) */
.flex-center-col {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

/* توزيع العناصر على الجانبين */
.flex-between {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

/* محاذاة للبداية */
.flex-start {
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

/* محاذاة للنهاية */
.flex-end {
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

/* السماح بالالتفاف */
.flex-wrap {
    flex-wrap: wrap;
}
```

## كلاسات الفجوات (Gap): &rlm;

```css
.gap-1 { gap: var(--spacer-xs); }  /* 4px */
.gap-2 { gap: var(--spacer-sm); }  /* 8px */
.gap-3 { gap: var(--spacer-md); }  /* 16px */
.gap-4 { gap: var(--spacer-lg); }  /* 24px */
.gap-5 { gap: var(--spacer-xl); }  /* 48px */
```

## أمثلة عملية: &rlm;

### توسيط محتوى في منتصف الصفحة: &rlm;
```html
<div class="flex-center" style="height: 100vh;">
    <h1>مرحباً بالعالم</h1>
</div>
```

### شريط تنقل مع عناصر على الجانبين: &rlm;
```html
<nav class="flex-between">
    <div class="logo">الشعار</div>
    <div class="menu">القائمة</div>
</nav>
```

### بطاقات متعددة مع فجوات: &rlm;
```html
<div class="flex-center flex-wrap gap-4">
    <div class="card">بطاقة 1</div>
    <div class="card">بطاقة 2</div>
    <div class="card">بطاقة 3</div>
</div>
```

</div>
