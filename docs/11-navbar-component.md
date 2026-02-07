<div dir="rtl">

# 11. شريط التنقل (Navbar Component) &rlm;

شريط تنقل ثابت باستخدام Bootstrap. &rlm;

## الكود: &rlm;

```html
<nav class="navbar navbar-expand-lg navbar-light bg-white border-bottom sticky-top">
    <div class="container">
        <!-- الشعار -->
        <a class="navbar-brand fw-bold" href="#">
            <i class="fas fa-rocket text-primary me-2"></i>Ready Starter
        </a>
        
        <!-- زر الموبايل -->
        <button class="navbar-toggler" type="button" 
                data-bs-toggle="collapse" 
                data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        
        <!-- القائمة -->
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link active" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#features">Features</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#demo">Demo</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
```

## شرح الكلاسات: &rlm;

| الكلاس | الوظيفة |
|--------|---------|
| `navbar` | الكلاس الأساسي للشريط |
| `navbar-expand-lg` | يتحول لقائمة hamburger على الشاشات الأصغر من lg |
| `navbar-light` | ألوان فاتحة للنصوص |
| `bg-white` | خلفية بيضاء |
| `border-bottom` | خط سفلي |
| `sticky-top` | يظل ثابتاً أعلى الصفحة عند التمرير |

## شرح `data-bs-*` &rlm;

| الخاصية | الوظيفة |
|---------|---------|
| `data-bs-toggle="collapse"` | يفعّل خاصية الطي/الفتح |
| `data-bs-target="#navbarNav"` | يحدد العنصر المستهدف |

## الأيقونة: &rlm;

```html
<i class="fas fa-rocket text-primary me-2"></i>
```
- `fas` = Font Awesome Solid
- `fa-rocket` = أيقونة الصاروخ
- `text-primary` = لون أزرق
- `me-2` = margin-end (مسافة يمين)

## كيف تعدّل؟ &rlm;

### تغيير الأيقونة: &rlm;
استبدل `fa-rocket` بأي أيقونة من [fontawesome.com](https://fontawesome.com/icons)

### إضافة رابط جديد: &rlm;
```html
<li class="nav-item">
    <a class="nav-link" href="#contact">Contact</a>
</li>
```

</div>
