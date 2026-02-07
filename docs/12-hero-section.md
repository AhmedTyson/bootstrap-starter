<div dir="rtl">

# 12. قسم البطل (Hero Section) &rlm;

القسم الرئيسي أعلى الصفحة مع العنوان والأزرار. &rlm;

## الكود: &rlm;

```html
<header class="section-padding bg-light">
    <div class="container">
        <div class="row align-items-center">
            <!-- العمود الأيسر: النص -->
            <div class="col-lg-6 mb-4 mb-lg-0">
                <h1 class="display-4 fw-bold mb-3">
                    Bootstrap Ready Environment
                </h1>
                <p class="lead text-muted mb-4">
                    A complete, production-ready starter template...
                </p>
                <div class="d-flex flex-wrap gap-3">
                    <a href="#demo" class="btn btn-primary btn-lg px-4">
                        <i class="fas fa-play me-2"></i>Get Started
                    </a>
                    <a href="#features" class="btn btn-outline-secondary btn-lg px-4">
                        <i class="fas fa-info-circle me-2"></i>Learn More
                    </a>
                </div>
            </div>
            
            <!-- العمود الأيمن: البطاقة -->
            <div class="col-lg-6">
                <div class="bg-white p-5 rounded-4 shadow-sm text-center">
                    <i class="fas fa-code fa-4x text-primary mb-3"></i>
                    <h4 class="fw-bold">Ready to Code</h4>
                    <p class="text-muted mb-0">All utilities are pre-configured.</p>
                </div>
            </div>
        </div>
    </div>
</header>
```

## شرح الهيكل: &rlm;

```
header (section-padding bg-light)
└── container
    └── row (align-items-center)
        ├── col-lg-6 (النص)
        │   ├── h1 (العنوان)
        │   ├── p (الوصف)
        │   └── div (الأزرار)
        └── col-lg-6 (البطاقة)
            └── div (المحتوى)
```

## الكلاسات المهمة: &rlm;

| الكلاس | الوظيفة |
|--------|---------|
| `display-4` | حجم عنوان كبير جداً |
| `lead` | نص توضيحي أكبر من العادي |
| `text-muted` | لون رمادي خفيف |
| `btn-lg` | زر كبير |
| `px-4` | padding أفقي (يمين ويسار) |
| `rounded-4` | زوايا دائرية كبيرة |
| `shadow-sm` | ظل خفيف |

## نظام الشبكة (Grid): &rlm;

```
col-lg-6 = يأخذ 6 أعمدة من 12 (نصف العرض) على الشاشات الكبيرة
mb-4 mb-lg-0 = margin-bottom على الموبايل، صفر على lg وما فوق
```

## تخصيص: &rlm;

### تغيير الخلفية: &rlm;
```html
<header class="section-padding bg-primary text-white">
```

### إضافة صورة بدل البطاقة: &rlm;
```html
<div class="col-lg-6">
    <img src="hero-image.png" alt="Hero" class="img-fluid">
</div>
```

</div>
