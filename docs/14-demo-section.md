<div dir="rtl">

# 14. قسم العرض التوضيحي (Demo Section) &rlm;

قسم يعرض أمثلة حية على الـ Utility Classes. &rlm;

## الكود: &rlm;

```html
<section id="demo" class="section-padding bg-light">
    <div class="container">
        <!-- العنوان -->
        <div class="text-center mb-5">
            <h2 class="fw-bold">Utility Demo</h2>
            <p class="text-muted">
                Test the custom classes in <code>styles.css</code>
            </p>
        </div>
        
        <!-- الأمثلة -->
        <div class="row g-4">
            <!-- مثال Flex Center -->
            <div class="col-md-6">
                <div class="bg-white p-4 rounded-3 shadow-sm h-100">
                    <h5 class="fw-bold mb-3">.flex-center</h5>
                    <div class="flex-center bg-primary text-white rounded" 
                         style="height: 120px;">
                        Centered Content
                    </div>
                </div>
            </div>
            
            <!-- مثال RTL -->
            <div class="col-md-6">
                <div class="bg-white p-4 rounded-3 shadow-sm h-100">
                    <h5 class="fw-bold mb-3">.arabic-text / .rtl</h5>
                    <div class="arabic-text bg-light p-3 rounded">
                        هذا نص عربي منسق بشكل صحيح
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
```

## هيكل المثال الواحد: &rlm;

```html
<div class="col-md-6">
    <div class="bg-white p-4 rounded-3 shadow-sm h-100">
        <!-- العنوان (اسم الكلاس) -->
        <h5 class="fw-bold mb-3">.class-name</h5>
        
        <!-- المحتوى التوضيحي -->
        <div class="class-name">
            المحتوى هنا
        </div>
    </div>
</div>
```

## أمثلة موجودة: &rlm;

| المثال | الكلاس | الوظيفة |
|--------|--------|---------|
| 1 | `.flex-center` | توسيط أفقي وعمودي |
| 2 | `.arabic-text` | دعم النص العربي RTL |
| 3 | `.ready-card` | بطاقة مع تأثير hover |
| 4 | `.text-gradient` | نص بتدرج لوني |

## كيف تضيف مثال جديد؟ &rlm;

```html
<div class="col-md-6">
    <div class="bg-white p-4 rounded-3 shadow-sm h-100">
        <h5 class="fw-bold mb-3">.your-class</h5>
        <div class="your-class">
            اختبر الكلاس هنا
        </div>
    </div>
</div>
```

## نصيحة: &rlm;

استخدم `<code>` لإظهار أسماء الملفات أو الكلاسات بشكل مميز: &rlm;

```html
<p>Check the <code>styles.css</code> file</p>
```

</div>
