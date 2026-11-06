# understanding.github.io

تلاشی برای فهمیدن و نوشتن

## توسعهٔ محلی

این سایت با [Hugo](https://gohugo.io/) نسخهٔ ۰٫۱۲۸٫۰ (extended) ساخته می‌شود؛ همان نسخه‌ای که در گردش‌کار GitHub Actions استفاده شده است.

```bash
hugo server -D
```

سایت روی <http://localhost:1313/> بالا می‌آید. پرچم `-D` نوشته‌های پیش‌نویس را هم نمایش می‌دهد.

## نوشتن نوشتهٔ تازه

```bash
hugo new content posts/my-post.md
```

سپس فایل ساخته‌شده را در `content/posts/` ویرایش کنید و برای انتشار، `draft` را به `false` تغییر دهید.

## انتشار

با هر push به شاخهٔ `main`، گردش‌کار GitHub Actions سایت را می‌سازد و روی GitHub Pages منتشر می‌کند. خروجی ساخت در `public/` قرار می‌گیرد و در مخزن ذخیره نمی‌شود.
