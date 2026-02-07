<div dir="rtl">

# 5. أدوات النصوص (Typography Utilities) &rlm;

كلاسات للتحكم في شكل وموضع النصوص. &rlm;

## محاذاة النص: &rlm;

```css
.text-center { text-align: center; }
.text-left { text-align: left; }
.text-right { text-align: right; }
```

## ألوان النص: &rlm;

```css
.text-primary { color: var(--primary-color); }    /* أزرق */
.text-secondary { color: var(--secondary-color); }/* رمادي */
.text-success { color: var(--success-color); }    /* أخضر */
.text-danger { color: var(--danger-color); }      /* أحمر */
.text-warning { color: var(--warning-color); }    /* أصفر */
.text-info { color: var(--info-color); }          /* سماوي */
.text-muted { color: var(--text-muted); }         /* رمادي فاتح */
.text-light { color: var(--text-light); }         /* أبيض */
.text-dark { color: var(--dark-color); }          /* أسود */
```

## سُمك الخط (Font Weight): &rlm;

```css
.fw-light { font-weight: 300; }     /* خفيف */
.fw-normal { font-weight: 400; }    /* عادي */
.fw-medium { font-weight: 500; }    /* متوسط */
.fw-semibold { font-weight: 600; }  /* شبه عريض */
.fw-bold { font-weight: 700; }      /* عريض */
```

## حجم الخط (Font Size): &rlm;

```css
.fs-sm { font-size: 0.875rem; }   /* 14px - صغير */
.fs-base { font-size: 1rem; }     /* 16px - عادي */
.fs-lg { font-size: 1.25rem; }    /* 20px - كبير */
.fs-xl { font-size: 1.5rem; }     /* 24px - كبير جداً */
```

## أمثلة: &rlm;

```html
<h1 class="text-center text-primary fw-bold">
    عنوان رئيسي
</h1>

<p class="text-muted fs-sm">
    نص توضيحي صغير باللون الرمادي
</p>

<span class="text-success fw-semibold">
    تم بنجاح!
</span>
```

</div>
