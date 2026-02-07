<div dir="rtl">

# 4. أدوات المسافات (Spacing Utilities) &rlm;

كلاسات جاهزة للتحكم في الـ margins و paddings. &rlm;

## مسافات الأقسام: &rlm;

```css
/* مسافة قياسية بين الأقسام */
.section-padding {
    padding: 80px 0;
}

/* مسافة أصغر */
.section-padding-sm {
    padding: 40px 0;
}
```

## كلاسات الـ Margin: &rlm;

### Margin Top (mt): &rlm;
```css
.mt-0 { margin-top: 0; }
.mt-1 { margin-top: var(--spacer-xs); }  /* 4px */
.mt-2 { margin-top: var(--spacer-sm); }  /* 8px */
.mt-3 { margin-top: var(--spacer-md); }  /* 16px */
.mt-4 { margin-top: var(--spacer-lg); }  /* 24px */
.mt-5 { margin-top: var(--spacer-xl); }  /* 48px */
```

### Margin Bottom (mb): &rlm;
```css
.mb-0 { margin-bottom: 0; }
.mb-1 { margin-bottom: var(--spacer-xs); }
.mb-2 { margin-bottom: var(--spacer-sm); }
.mb-3 { margin-bottom: var(--spacer-md); }
.mb-4 { margin-bottom: var(--spacer-lg); }
.mb-5 { margin-bottom: var(--spacer-xl); }
```

## جدول المقاسات: &rlm;

| الكلاس | القيمة | بالبكسل |
|--------|--------|---------|
| `-0` | 0 | 0px |
| `-1` | 0.25rem | 4px |
| `-2` | 0.5rem | 8px |
| `-3` | 1rem | 16px |
| `-4` | 1.5rem | 24px |
| `-5` | 3rem | 48px |

## أمثلة: &rlm;

```html
<!-- قسم مع مسافة علوية كبيرة -->
<section class="section-padding mt-5">
    <h2 class="mb-4">عنوان القسم</h2>
    <p class="mb-3">فقرة نصية</p>
</section>
```

</div>
