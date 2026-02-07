<div dir="rtl">

# 10. هيكل HTML (HTML Structure) &rlm;

الإعداد الأساسي لملف HTML مع المكتبات الخارجية. &rlm;

## الكود الكامل: &rlm;

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="وصف الموقع للسيو">
    <title>عنوان الصفحة</title>
    
    <!-- Bootstrap 5.3 CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Custom Styles -->
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <!-- المحتوى هنا -->
    
    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## شرح كل جزء: &rlm;

### 1. `<!DOCTYPE html>` &rlm;
يخبر المتصفح أن هذا ملف HTML5. &rlm;

### 2. `<meta charset="UTF-8">` &rlm;
يدعم جميع الأحرف بما فيها العربية. &rlm;

### 3. `<meta name="viewport">` &rlm;
يجعل الصفحة responsive على الموبايل. &rlm;

### 4. `<meta name="description">` &rlm;
وصف الصفحة لمحركات البحث (SEO). &rlm;

## المكتبات المستخدمة: &rlm;

| المكتبة | الوظيفة | الرابط |
|---------|---------|--------|
| Bootstrap 5.3 | إطار العمل الأساسي | cdn.jsdelivr.net |
| Font Awesome 6 | أيقونات جاهزة | cdnjs.cloudflare.com |
| Google Fonts | خط Inter | fonts.googleapis.com |

## ترتيب الملفات: &rlm;

1. Bootstrap CSS (أولاً)
2. المكتبات الإضافية
3. Custom CSS (أخيراً - ليتجاوز Bootstrap)

## ملاحظة مهمة: &rlm;

الـ JavaScript يوضع قبل `</body>` مباشرة لتسريع تحميل الصفحة. &rlm;

</div>
