<div dir="rtl">

# 13. قسم المميزات (Features Section) &rlm;

شبكة بطاقات تعرض مميزات المشروع. &rlm;

## الكود: &rlm;

```html
<section id="features" class="section-padding">
    <div class="container">
        <!-- العنوان -->
        <div class="text-center mb-5">
            <h2 class="fw-bold">What's Included</h2>
            <p class="text-muted">Everything you need to start building</p>
        </div>
        
        <!-- شبكة البطاقات -->
        <div class="row g-4">
            <div class="col-md-4">
                <div class="ready-card h-100 text-center">
                    <i class="fas fa-palette fa-2x text-primary mb-3"></i>
                    <h5 class="fw-bold">CSS Variables</h5>
                    <p class="text-muted small mb-0">
                        Complete color palette using CSS custom properties.
                    </p>
                </div>
            </div>
            <!-- المزيد من البطاقات... -->
        </div>
    </div>
</section>
```

## هيكل الشبكة: &rlm;

```
section
└── container
    ├── div (العنوان - text-center mb-5)
    │   ├── h2
    │   └── p
    └── row (g-4 = gap بين البطاقات)
        ├── col-md-4 (بطاقة 1)
        ├── col-md-4 (بطاقة 2)
        ├── col-md-4 (بطاقة 3)
        ├── col-md-4 (بطاقة 4)
        ├── col-md-4 (بطاقة 5)
        └── col-md-4 (بطاقة 6)
```

## شرح `col-md-4`: &rlm;

| الشاشة | السلوك |
|--------|--------|
| < 768px | كل بطاقة تأخذ 12 عمود (عرض كامل) |
| ≥ 768px | كل بطاقة تأخذ 4 أعمدة (3 بطاقات في الصف) |

## شرح `g-4`: &rlm;

الـ `g` تعني **gutter** وهي المسافة بين الأعمدة والصفوف.
- `g-1` = 0.25rem
- `g-2` = 0.5rem
- `g-3` = 1rem
- `g-4` = 1.5rem
- `g-5` = 3rem

## هيكل البطاقة الواحدة: &rlm;

```html
<div class="col-md-4">
    <div class="ready-card h-100 text-center">
        <i class="fas fa-icon fa-2x text-primary mb-3"></i>
        <h5 class="fw-bold">العنوان</h5>
        <p class="text-muted small mb-0">الوصف</p>
    </div>
</div>
```

| الكلاس | الوظيفة |
|--------|---------|
| `h-100` | ارتفاع 100% (كل البطاقات بنفس الارتفاع) |
| `fa-2x` | حجم الأيقونة ضعف العادي |
| `small` | نص أصغر |
| `mb-0` | بدون margin سفلي |

## أيقونات مقترحة: &rlm;

| الميزة | الأيقونة |
|--------|---------|
| ألوان | `fa-palette` |
| سرعة | `fa-bolt` |
| أمان | `fa-shield-alt` |
| تخصيص | `fa-cog` |
| دعم | `fa-headset` |
| موبايل | `fa-mobile-alt` |

</div>
