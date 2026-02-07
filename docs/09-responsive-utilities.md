<div dir="rtl">

# 9. أدوات الاستجابة (Responsive Utilities) &rlm;

كلاسات للتحكم في العرض على الشاشات المختلفة. &rlm;

## الكود: &rlm;

```css
/* للشاشات الصغيرة (موبايل) */
@media (max-width: 768px) {
    .section-padding {
        padding: 50px 0;  /* تقليل المسافات */
    }
    
    .hide-mobile {
        display: none !important;  /* إخفاء على الموبايل */
    }
}

/* للشاشات الكبيرة (ديسكتوب) */
@media (min-width: 769px) {
    .hide-desktop {
        display: none !important;  /* إخفاء على الديسكتوب */
    }
}
```

## شرح الـ Media Queries: &rlm;

| الاستعلام | المعنى |
|-----------|--------|
| `@media (max-width: 768px)` | الشاشات الأصغر من 768px (موبايل) |
| `@media (min-width: 769px)` | الشاشات الأكبر من 769px (تابلت/ديسكتوب) |

## كلاسات الإظهار/الإخفاء: &rlm;

| الكلاس | الموبايل | الديسكتوب |
|--------|----------|-----------|
| `.hide-mobile` | ❌ مخفي | ✅ ظاهر |
| `.hide-desktop` | ✅ ظاهر | ❌ مخفي |

## أمثلة عملية: &rlm;

### قائمة تظهر فقط على الموبايل: &rlm;
```html
<button class="hide-desktop">
    ☰ القائمة
</button>
```

### محتوى يظهر فقط على الديسكتوب: &rlm;
```html
<aside class="hide-mobile">
    الشريط الجانبي
</aside>
```

### تغيير المسافات على الموبايل: &rlm;
```html
<section class="section-padding">
    <!-- على الديسكتوب: 80px -->
    <!-- على الموبايل: 50px (تلقائياً) -->
</section>
```

## نقاط التوقف (Breakpoints) الشائعة: &rlm;

| النوع | العرض |
|-------|-------|
| موبايل صغير | < 576px |
| موبايل | < 768px |
| تابلت | 768px - 991px |
| ديسكتوب | 992px - 1199px |
| ديسكتوب كبير | ≥ 1200px |

</div>
