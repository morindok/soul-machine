# Soul Machine by Morindok — ماشینِ روح

**Read online / مطالعهٔ آنلاین:** https://morindok.github.io/soul-machine/
**About & table of contents / دربارهٔ کتاب و فهرست:** https://morindok.github.io/soul-machine/about.html
**Repository / مخزن:** https://github.com/morindok/soul-machine

---

## English

**Soul Machine** — presented inside the work under its inner title **The Spirit Machine** — is an interactive, bilingual (English/Persian) digital codex by **Morindok**. It takes the form of **101 illuminated plates**: an "anatomical cartography of the soul" that dissects, in poetic and symbolic language, the imagined architecture connecting human being, cosmos, and the mechanism that binds them.

### What is inside

- **101 plates** built from **20 recurring themes** (The Tree of Life, Chakric Ladder, Merkaba Engine, The Flower of Life, Metatron's Cube, Kundalini Serpent, The Neural Cosmos, and more). Plates are generated procedurally, so illustrations are always crisp SVG at any resolution.
- **Click-to-reveal hotspots** on every illustration, unlocking short esoteric commentaries (Tree of Life, chakras, kundalini, Platonic solids, golden ratio, Orch-OR, and other symbolic motifs).
- **Bilingual interface** — the entire reader switches between English and Persian (full RTL support) with one click.
- **Keyboard-friendly navigation** — arrows to turn pages, folio jump box (I–CI), Esc to close.
- A stylized **passphrase gate** as part of the experience (see below).

### How to read

1. Open https://morindok.github.io/soul-machine/
2. Enter the passphrase when prompted: it is the author's name in lowercase (`morindok`). This gate is a stylistic ritual, **not** a security mechanism — the passphrase is visible in the public page source, and direct access is also possible via `?access=spirit-machine-2024`.
3. Turn pages with the buttons, the folio box, or arrow keys; click the glowing sigils to reveal hidden commentary; switch language with the FA/EN buttons.

### Run locally

The book is a single self-contained HTML file. Serve it with any static server:

```bash
python -m http.server 8000
# then open http://localhost:8000/
```

(Opening `index.html` directly from disk also works in most browsers.)

### Technology

- One dependency-light HTML file: `index.html`
- Illustrations are **procedurally generated SVG** in the browser (no image assets)
- Styling: Tailwind CSS via CDN + Google Fonts (Cinzel, Cormorant Garamond, Vazirmatn, MedievalSharp)
- `about.html` is a static, fully crawlable description and table of contents

### SEO notes (honest scope)

Implemented: descriptive `<title>`, meta description, canonical URLs, Open Graph + Twitter cards, JSON-LD structured data (`Book`/`WebSite`), `sitemap.xml`, `robots.txt`, `favicon.svg`, a crawlable static `about.html` with the full table of contents, and bilingual metadata. Limits to be aware of: the passphrase gate hides the reader content from crawlers and no-JS visitors (kept intentionally, per the author's choice — only `about.html` is fully indexable); GitHub Pages serves `robots.txt` at the **origin** level (`morindok.github.io/robots.txt`), so the file in this repository may not be used for this site; real search ranking depends on things outside this repository (search-console registration, backlinks, age, and so on) and is not guaranteed by anything here.

### Content disclaimer

This work is an **artistic and literary** exploration of esoteric and mythological themes. Plates and commentaries are symbolic fiction — not medical, psychological, or scientific advice.

### Rights

© Morindok, MMXXIV. **All rights reserved.** The text, generated artwork, and design are the property of the author; no open-source license is granted. The repository exists to host the public reading experience.

---

## فارسی

**ماشینِ روح** (Soul Machine) کتابی تعاملی و دوزبانه (فارسی/انگلیسی) اثر **موریندوک** است؛ کدکسی دیجیتال شامل **۱۰۱ لوح مصور** که با زبانی شاعرانه و نمادین، «نقشه‌برداری کالبدشکافانه‌ای از روح» ارائه می‌کند: معماریِ پنهانِ انسان، کیهان، و مکانیزم پیوندشان.

### محتوای کتاب

- **۱۰۱ لوح** بر پایهٔ **۲۰ مضمون تکرارشونده** (درخت زندگی، نردبان چاکرایی، موتور مرکابا، گل زندگی، مکعب متاترون، مار کندالینی، کیهانِ عصبی و…)؛ تصاویر به‌صورت رویه‌ای تولید می‌شوند و همیشه واضح‌اند.
- **نقاط درخشان** روی هر تصویر که با کلیک، شروح کوتاه عرفانی را آشکار می‌کنند.
- **رابط دوزبانه** — جابه‌جایی کامل میان فارسی و انگلیسی (با پشتیبانی کامل راست‌به‌چپ) با یک کلیک.
- **ناوبری با کیبورد** — جهت‌نما برای ورق‌زدن، پرش به هر شمارهٔ لوح (I تا CI)، Esc برای بستن.
- **دروازهٔ رمز** نمایشی به‌عنوان بخشی از تجربه (توضیح در ادامه).

### نحوهٔ مطالعه

1. https://morindok.github.io/soul-machine/ را باز کنید.
2. در دروازهٔ ورود، رمز عبور را وارد کنید: نام نویسنده با حروف کوچک انگلیسی (`morindok`). این دروازه بخشی از آیین و حال‌وهوای کتاب است و **وسیلهٔ حفاظت نیست** — رمز در سورس عمومی صفحه دیده می‌شود و ورود مستقیم با `?access=spirit-machine-2024` هم ممکن است.
3. با دکمه‌ها، کادر شمارهٔ لوح یا کلیدهای جهت‌نما صفحه بچرخانید؛ روی نمادهای درخشان کلیک کنید تا شروح پنهان آشکار شود؛ با دکمه‌های FA/EN زبان را عوض کنید.

### اجرای محلی

کتاب یک فایل HTML خودکفاست؛ با هر سرور استاتیک اجرا کنید:

```bash
python -m http.server 8000
# سپس http://localhost:8000/ را باز کنید
```

(بازکردن مستقیم `index.html` هم در بیشتر مرورگرها کار می‌کند.)

### فناوری

- یک فایل HTML کم‌نیازمندی: `index.html`
- تصویرسازی **SVG تولیدشده رویه‌ای** در مرورگر (بدون فایل تصویر)
- استایل: Tailwind CSS از CDN و فونت‌های گوگل (Cinzel، Cormorant Garamond، Vazirmatn، MedievalSharp)
- `about.html` صفحهٔ ایستا، کامل و قابل‌ایندکس برای توضیحات و فهرست الواح است

### نکات سئو (با صداقت دربارهٔ محدوده)

انجام‌شده: عنوان و توضیحات متا، آدرس canonical، کارت‌های Open Graph و توییتر، دادهٔ ساخت‌یافتهٔ JSON-LD (`Book`/`WebSite`)، `sitemap.xml`، `robots.txt`، `favicon.svg` و صفحهٔ ایستا و قابل‌ایندکس `about.html` با فهرست کامل الواح و متادیتای دوزبانه. محدودیت‌ها: دروازهٔ رمز، محتوای کتاب را از دید خزنده‌ها و بازدیدکنندگان بدون جاوااسکریپت پنهان می‌کند (به انتخاب نویسنده حفظ شده — فقط `about.html` کامل ایندکس می‌شود)؛ `robots.txt` در GitHub Pages در **سطح دامنه** سرو می‌شود و ممکن است فایل این مخزن برای این سایت به کار نرود؛ رتبهٔ واقعی در جست‌وجو به عوامل بیرون از این مخزن وابسته است (ثبت در Search Console، بک‌لینک، عمر دامنه و…) و هیچ‌چیز در اینجا آن را تضمین نمی‌کند.

### سلب مسئولیت محتوا

این اثر کنکاشی **هنری و ادبی** در مضمون‌های عرفانی و اسطوره‌ای است. الواح و شروح، داستانی نمادین‌اند — نه توصیهٔ پزشکی، روان‌شناختی یا علمی.

### حقوق

© موریندوک، ۱۴۰۳ / MMXXIV. **تمامی حقوق محفوظ است.** متن، تصویرسازی و طراحی، ملکیت نویسنده است و مجوز متن‌باز داده نمی‌شود؛ این مخزن صرفاً میزبان تجربهٔ مطالعهٔ عمومی است.
