<div dir="rtl">

# 1. متغيرات CSS (CSS Variables) &rlm;

المتغيرات في CSS هي طريقة لتخزين قيم يمكن إعادة استخدامها في أي مكان بالكود. &rlm;

## لماذا نستخدم المتغيرات؟ &rlm;

بدل ما تكتب `#0d6efd` في 50 مكان، تكتبها مرة واحدة وتستخدم المتغير `var(--primary-color)`. &rlm;

## الكود: &rlm;

```css
:root {
    /* ألوان - Colors */
    --primary-color: #0d6efd;      /* اللون الأساسي (أزرق) */
    --primary-hover: #0b5ed7;      /* اللون عند الـ hover */
    --secondary-color: #6c757d;    /* اللون الثانوي (رمادي) */
    --success-color: #198754;      /* لون النجاح (أخضر) */
    --danger-color: #dc3545;       /* لون الخطر (أحمر) */
    --warning-color: #ffc107;      /* لون التحذير (أصفر) */
    --info-color: #0dcaf0;         /* لون المعلومات (سماوي) */
    
    /* خلفيات - Backgrounds */
    --bg-body: #ffffff;
    --bg-light: #f8f9fa;
    --bg-dark: #212529;
    
    /* نصوص - Text */
    --text-primary: #212529;
    --text-muted: #6c757d;
    --text-light: #f8f9fa;
    
    /* مسافات - Spacing */
    --spacer-xs: 0.25rem;   /* 4px */
    --spacer-sm: 0.5rem;    /* 8px */
    --spacer-md: 1rem;      /* 16px */
    --spacer-lg: 1.5rem;    /* 24px */
    --spacer-xl: 3rem;      /* 48px */
    
    /* زوايا - Border Radius */
    --radius-sm: 0.25rem;
    --radius-md: 0.5rem;
    --radius-lg: 1rem;
    --radius-pill: 50rem;   /* دائري تماماً */
    
    /* ظلال - Shadows */
    --shadow-sm: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075);
    --shadow-md: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);
    --shadow-lg: 0 1rem 3rem rgba(0, 0, 0, 0.175);
    
    /* انتقالات - Transitions */
    --transition-fast: 0.15s ease-in-out;
    --transition-base: 0.3s ease-in-out;
}
```

## كيف تستخدمها؟ &rlm;

```css
.my-button {
    background-color: var(--primary-color);
    padding: var(--spacer-md);
    border-radius: var(--radius-md);
    box-shadow: var(--shadow-sm);
    transition: var(--transition-base);
}
```

## فائدة عملية: &rlm;

لو أردت تغيير اللون الأساسي للموقع كله، تغير قيمة `--primary-color` في مكان واحد فقط! &rlm;

</div>
