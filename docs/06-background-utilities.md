<div dir="rtl">

# 6. أدوات الخلفيات (Background Utilities) &rlm;

كلاسات لتغيير لون خلفية أي عنصر بسرعة. &rlm;

## الكود: &rlm;

```css
.bg-primary { background-color: var(--primary-color); }   /* أزرق */
.bg-secondary { background-color: var(--secondary-color); } /* رمادي */
.bg-success { background-color: var(--success-color); }   /* أخضر */
.bg-danger { background-color: var(--danger-color); }     /* أحمر */
.bg-warning { background-color: var(--warning-color); }   /* أصفر */
.bg-info { background-color: var(--info-color); }         /* سماوي */
.bg-light { background-color: var(--bg-light); }          /* رمادي فاتح */
.bg-dark { background-color: var(--bg-dark); }            /* أسود */
.bg-white { background-color: #ffffff; }                  /* أبيض */
```

## جدول الألوان: &rlm;

| الكلاس | اللون | الكود |
|--------|-------|-------|
| `.bg-primary` | 🔵 أزرق | #0d6efd |
| `.bg-secondary` | ⚫ رمادي | #6c757d |
| `.bg-success` | 🟢 أخضر | #198754 |
| `.bg-danger` | 🔴 أحمر | #dc3545 |
| `.bg-warning` | 🟡 أصفر | #ffc107 |
| `.bg-info` | 🔵 سماوي | #0dcaf0 |
| `.bg-light` | ⚪ فاتح | #f8f9fa |
| `.bg-dark` | ⬛ داكن | #212529 |

## أمثلة: &rlm;

```html
<!-- قسم بخلفية فاتحة -->
<section class="bg-light section-padding">
    <div class="container">
        محتوى القسم
    </div>
</section>

<!-- زر تحذير -->
<button class="bg-warning text-dark">
    تحذير!
</button>

<!-- بطاقة ناجحة -->
<div class="bg-success text-light p-3">
    تمت العملية بنجاح
</div>
```

## ملاحظة مهمة: &rlm;

عند استخدام خلفية داكنة، استخدم `.text-light` أو `.text-white` لجعل النص مقروءاً. &rlm;

</div>
