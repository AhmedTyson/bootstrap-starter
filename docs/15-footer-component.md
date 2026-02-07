<div dir="rtl">

# 15. التذييل (Footer Component) &rlm;

الجزء السفلي من الصفحة مع روابط التواصل. &rlm;

## الكود: &rlm;

```html
<footer class="bg-dark text-white py-4">
    <div class="container">
        <div class="row align-items-center">
            <!-- النص -->
            <div class="col-md-6 text-center text-md-start mb-3 mb-md-0">
                <p class="mb-0 opacity-75">
                    © 2026 Ready Starter • Built with Bootstrap 5
                </p>
            </div>
            
            <!-- روابط التواصل -->
            <div class="col-md-6 text-center text-md-end">
                <a href="#" class="text-white-50 me-3">
                    <i class="fab fa-github fa-lg"></i>
                </a>
                <a href="#" class="text-white-50 me-3">
                    <i class="fab fa-twitter fa-lg"></i>
                </a>
                <a href="#" class="text-white-50">
                    <i class="fab fa-linkedin fa-lg"></i>
                </a>
            </div>
        </div>
    </div>
</footer>
```

## شرح الكلاسات: &rlm;

| الكلاس | الوظيفة |
|--------|---------|
| `bg-dark` | خلفية داكنة |
| `text-white` | نص أبيض |
| `py-4` | padding عمودي (أعلى وأسفل) |
| `opacity-75` | شفافية 75% |
| `text-white-50` | نص أبيض بشفافية 50% |
| `text-center text-md-start` | توسيط على الموبايل، لليسار على md+ |

## أيقونات التواصل: &rlm;

| المنصة | الكلاس |
|--------|--------|
| GitHub | `fab fa-github` |
| Twitter/X | `fab fa-twitter` |
| LinkedIn | `fab fa-linkedin` |
| Facebook | `fab fa-facebook` |
| Instagram | `fab fa-instagram` |
| YouTube | `fab fa-youtube` |
| WhatsApp | `fab fa-whatsapp` |
| Email | `fas fa-envelope` |

## تخصيصات: &rlm;

### تغيير لون الخلفية: &rlm;
```html
<footer class="bg-primary text-white py-4">
```

### إضافة روابط نصية: &rlm;
```html
<a href="#" class="text-white-50 text-decoration-none me-3">Privacy</a>
<a href="#" class="text-white-50 text-decoration-none me-3">Terms</a>
<a href="#" class="text-white-50 text-decoration-none">Contact</a>
```

### تكبير القسم: &rlm;
```html
<footer class="bg-dark text-white py-5">
```

## ملاحظة: &rlm;

`fab` = Font Awesome Brands (للشركات والمنصات) &rlm;
`fas` = Font Awesome Solid (للأيقونات العامة) &rlm;

</div>
