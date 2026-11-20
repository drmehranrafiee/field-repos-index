# فهرست ریپوهای گیت‌هابِ حوزه تو — طبقه‌بندی‌شده

**تاریخ فهرست:** ۲۰ نوامبر ۲۰۲۶
**منبع:** همه لینک‌هایی که تا امروز فرستادی + همه بریف‌هایی که برایت ساختم (your_files، فایل‌های دایجست، و MEMORY). فقط ریپوهایی آمده که **ریپوی واقعی گیت‌هاب** دارند؛ ابزارهای بدون ریپوی عمومی (مثل Bango و Collie) جداگانه در انتهای هر بخش آمده‌اند.
**نکته ستاره‌ها:** عدد ستاره، همان عددی است که در روز بررسی هر بریف از GitHub API خوانده شد — امروز دوباره چک نشده، مگر PaperOrchestra که ۲۰ نوامبر چک شد. پس ستاره‌ها «تاریخ‌دار» اند، نه لحظه‌ای.
**وضعیت:** ✓ = مستقیم از GitHub API یا صفحه ریپو بررسی شده · ⚠ = نام/کارکرد از اسلاید پست نقل شده و ریپو تک‌تک باز نشده · ✗ = ریپوی عمومی ندارد

---

## ۱. بیوانفورماتیک و کشف دارو — هسته کارت

| ریپو | ستاره (تاریخ بررسی) | لایسنس | چیست و به چه کارت می‌آید |
|---|---|---|---|
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) ✓ | ۵۷٬۶۲۶ (۱۸ نوامبر) | MIT | **مهم‌ترین ریپوی این فهرست برای تو.** ۱۷۷ اسکیل علمی + دسترسی به ۱۰۰+ دیتابیس؛ README صراحتاً Antigravity را پشتیبانی می‌کند. نگاشت به پروژه‌هایت: بیوانفورماتیک و ژنومیکس ۳۲ اسکیل، شیمی‌انفورماتیک و کشف دارو ۱۱ اسکیل (rdkit، diffdock، datamol)، پژوهش بالینی و شواهد ۸ اسکیل (مرور HFpEF)، مولتی‌اومیکس ۵ اسکیل (شبکه MDD، نگاشت چاقی–افسردگی). مثال آماده README دقیقاً الگوی AdipoTarget Scout است (ChEMBL + RDKit + DiffDock روی ساختار AlphaFold). قید: هر ۱۷۷ اسکیل را یک‌جا نصب نکن؛ اول SKILL.md هر کدام را بخوان. ویندوز: WSL2 + Python 3.13. |
| [openscientist-io/openscientist](https://github.com/openscientist-io/openscientist) ✓ | ۹۸ (۱۸ نوامبر) | Apache-2.0 | همکار علمی ایجنتی متن‌باز (دانشگاه واشنگتن در سنت‌لوئیس، Broad، برکلی)، مقاله Nature Medicine ۱۶ نوامبر ۲۰۲۶. روی کتابخانه K-Dense سوار است؛ با Claude Code ساخته شده و در مقاله از Claude Sonnet 4.5 استفاده شده. قید: خودهاستی رایگان نیست (Docker + اعتبار ارائه‌دهنده مدل)؛ ارزیابی فقط ۵ مطالعه موردیِ خود تیم است، بدون اعتبارسنجی مستقل. |
| [nrflynn2/ml-drug-discovery](https://github.com/nrflynn2/ml-drug-discovery) ✓ | — (همراه کتاب) | — | کد همراه کتاب *Machine Learning for Drug Discovery* — کتاب شماره ۱ فهرست ۵۰ کتاب ۲۰۲۵–۲۰۲۶ تو (امتیاز ۹۴). |
| Arc Institute — antiGen و Germinal Multi ✓ (ابزار) | — | — | دو ابزار ۱۷ نوامبر ۲۰۲۶: antiGen پیش‌بینی جهش‌های آینده ویروس از درخت فیلوژنتیک؛ Germinal Multi طراحی یک آنتی‌بادی علیه چند واریانت. هر دو رایگان روی GitHub با دو پیش‌چاپ bioRxiv. **مسیر دقیق ریپو در بریف ثبت نشده** — از صفحه رسمی شروع کن: arcinstitute.org/news/antigen-and-germinal-multi. قید: پیش‌چاپ‌اند، نه داوری‌شده. |

**بدون ریپوی عمومی، ولی در همین حوزه:** دیتابیس‌های رایگان AlphaFold DB، ClinVar، gnomAD v4، TCGA (GDC)، CDC WONDER و PhysioNet سرویس وب‌اند، نه ریپو — بریفشان: `free-medical-research-databases-brief-fa.md`.

---

## ۲. پژوهش علمی، نوشتن مقاله، مرور سیستماتیک

| ریپو | ستاره (تاریخ بررسی) | لایسنس | چیست و به چه کارت می‌آید |
|---|---|---|---|
| [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) ✓ | ۵٬۱۱۱ / ۶۴۱ فورک (۲۰ نوامبر) | Apache-2.0 | فریم‌ورک ۵ ایجنت گوگل (Google Cloud AI Research) که ایده + لاگ آزمایش را به دست‌نوشته LaTeX تبدیل می‌کند؛ نکته جدیدش **رجیستری ارجاع تاییدشده با Semantic Scholar API** است — دقیقاً الگویی که در مرور HFpEF لازم داری. مقاله arXiv:2604.05018. قید: فقط ۸ کامیت، ۰ ریلیز، دیتاست در ریپو نیست، کلید API (Gemini/Vertex یا OpenAI) می‌خواهد، و «محصول رسمی گوگل» نیست. |
| [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) ✓ | ۵۶٬۴۵۷ (۱۱ نوامبر) | ⚠ تعارض لایسنس — README می‌گوید CC BY-NC 4.0 ولی متادیتای گیت‌هاب NOASSERTION؛ پیش از استفاده فراتر از شخصی، LICENSE را چک کن | سوئیت پژوهش آکادمیک: Deep Research (۸ حالت، از جمله مرور سیستماتیک/PRISMA)، Academic Paper (۱۱ حالت، APA/IEEE/…/LaTeX)، Academic Paper Reviewer (۶ حالت)، Academic Pipeline (ارکستراتور ۱۰ مرحله‌ای) + **SR-Screener v1.0.0** — گزینه سوم غربال مرور سیستماتیک برای HFpEF، کنار Bango و Collie. قید: نصب Antigravity تایید نشده؛ هزینه توکن سنگین (یک ران کامل Pipeline می‌تواند بالای ۲۰۰K ورودی + ۱۰۰K خروجی توکن باشد). |
| [Aukexecutivedepartment5152/PaperOrchestra](https://github.com/Aukexecutivedepartment5152/PaperOrchestra) ⚠ | — | — | **اسکیل‌پک ثالث (مال گوگل نیست)** که پرامپت‌های PaperOrchestra را به اسکیل ایجنتی برای Claude Code / Cursor / Antigravity تبدیل می‌کند؛ بدون کلید API داخلی. تست نشده. |

**بدون ریپوی عمومی، ولی در همین بخش:**
- **Bango** — غربال AI مرور سیستماتیک، لوکال‌فرست، رایگان، Apache 2.0، دسکتاپ ویندوز/macOS/لینوکس؛ سایت bango.boncode.net؛ MCP/API/CLI ندارد، ارزشش بالادست با خروجی فایل است.
- **Collie** — پلتفرم PICO→PRISMA 2020 با MCP agent kit (۱۳ اسکیل، ۸ ایجنت، ۴ هوک)؛ ابری، پلن رایگان بدون کارت؛ نصب Antigravity تایید نشده؛ رابط انگلیسی/پرتغالی/اسپانیایی، بدون فارسی.
- مقایسه سه‌طرفه آماده و ارسال‌نشده: `hfpef-screening-3way-comparison-fa.md` — هر وقت سراغ مرور HFpEF رفتی، همان را باز کن.
- **Deep Review** — اسکیل محلی خودت (نه ریپوی گیت‌هاب) که متد Google Deep Review را بازسازی می‌کند: `deep-review-skill/SKILL.md`.

**کتاب‌های همراه با ریپو:**
- [peremartra/rearchitecting-llms](https://github.com/peremartra/rearchitecting-llms) — کد کتاب *Build a Reasoning Model From Scratch* (کتاب شماره ۲ فهرستت، امتیاز ۹۲).
- [natolambert/rlhf-book](https://github.com/natolambert/rlhf-book) — کد کتاب RLHF.

---

## ۳. Antigravity، ایجنت‌های کدنویسی و ارکستراسیون

| ریپو | ستاره (تاریخ بررسی) | لایسنس | چیست |
|---|---|---|---|
| [google/elephant-goldfish-model](https://github.com/google/elephant-goldfish-model) ✓ | ~۱۵٬۲۰۰ (۹ نوامبر) | Apache-2.0 | پلاگین گوگل: «فیل» با کانتکست عمیق طرح می‌نویسد، «گولدفیش»‌های صفرکانتکست قبل از نوشتن کد بازبینی می‌کنند. نصب در Antigravity: `agy plugin install https://github.com/google/elephant-goldfish-model`. قید: v0.1، بدون شواهد کنترل‌شده از بهبود، و بدون ساب‌ایجنت تازه‌کانتکست، بازبینی متوقف می‌شود. |
| [open-gsd/gsd-core](https://github.com/open-gsd/gsd-core) ✓ | ~۸٬۸۰۰ | MIT | ادامه‌دهنده رسمی GSD (ریپوی اصلی GSD در ۲۶ ژوئن ۲۰۲۶ آرشیو شد)؛ نصب: `npx @opengsd/gsd-core@latest`. |
| [toonight/get-shit-done-for-antigravity](https://github.com/toonight/get-shit-done-for-antigravity) ✓ | — | — | پورت جامعه GSD برای Antigravity. |
| [RooCodeInc/Roo-Code](https://github.com/RooCodeInc/Roo-Code) ✓ | — | — | Roo Code — فقط در Antigravity IDE، نه در اپ دسکتاپ ۲٫۰. |
| [ghuntley/how-to-ralph-wiggum](https://github.com/ghuntley/how-to-ralph-wiggum) ✓ | — | — | مرجع اصلی Ralph Loop — یک الگو است، نه پلاگین. |
| [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot) ✓ | ۲۵٬۷۱۲ (۱۹ نوامبر) | Apache-2.0 (به‌جز پوشه `enterprise/`) | MausBot (نه MouseBot): اپ چت که هر بات یک ایجنت CLI واقعی است (Claude Code، Codex، Grok، Gemini از طریق Antigravity با ACP رسمی، Ollama لوکال). نخ‌های موازی: ۱ نخ به ازای هر ۲ گیگ رم، ۳ تا ۱۶ به‌صورت لوکال. اینستالر ویندوز هست ولی امضا نشده (هشدار SmartScreen). اپ رایگان، مصرف AI با خودت؛ Cloud اختیاری از ۱۵ دلار/ماه. |
| [upstash/context7](https://github.com/upstash/context7) ✓ | ۶۳٬۶۰۰ | MIT | داک به‌روز کتابخانه‌ها برای ایجنت — یکی از ۴ اینتگریشن Antigravity. |
| [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) ✓ | ۵۴٬۰۰۰ | Apache-2.0 | کنترل و دیباگ Chrome زنده؛ داک رسمی صراحتاً Antigravity را پشتیبانی می‌کند. |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) ✓ | ۳۸٬۶۰۰ | Apache-2.0 | اتوماسیون مرورگر با Playwright برای ایجنت. |
| [github/github-mcp-server](https://github.com/github/github-mcp-server) ✓ | ۳۳٬۹۰۰ | MIT | MCP سرور رسمی گیت‌هاب. |
| [google-antigravity/antigravity-sdk-python](https://github.com/google-antigravity/antigravity-sdk-python) ✓ | — | — | SDK رسمی پایتون Antigravity. |

---

## ۴. ویدیوی کد-محور و انیمیشن علمی — استک pure-code video

| ریپو | ستاره (تاریخ بررسی) | لایسنس | چیست |
|---|---|---|---|
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) ✓ | ~۶۰–۷۰ هزار (اکتبر) | Apache-2.0 | فریم‌ورک HeyGen: «HTML بنویس، ویدیو رندر بگیر» — رندر قطعی با headless Chrome + FFmpeg، ۲۱ اسکیل، Node 22+. ستون اصلی استک pure-code video تو. |
| [remotion-dev/remotion](https://github.com/remotion-dev/remotion) ✓ | — | — | Remotion — موتور رندر ویدیو با React؛ همراه HyperFrames. |
| [ManimCommunity/manim](https://github.com/ManimCommunity/manim) ✓ | — | — | Manim CE — انیمیشن برداری توضیحی به سبک 3Blue1Brown؛ اسکریپت تست EC50 تو با همین ساخته شد. |
| [adithya-s-k/manim_skill](https://github.com/adithya-s-k/manim_skill) ✓ | — | — | اسکیل ایجنتی Manim. |
| [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) ✓ | ۱۴٬۷۵۶ (۱۱ نوامبر) | MIT | Opuscar — ۶۶ استایل (فرمول‌های استایل برای Opus 5.5 تنظیم شده‌اند). |
| [yihui-dev/awesome-opus5-5-videos](https://github.com/yihui-dev/awesome-opus5-5-videos) ✓ | ۱۴٬۸۵۰ (۱۱ نوامبر) | MIT | مجموعه ~۷۰۳ پرامپت ویدیوی Opus 5.5 (Prompt-Motion). |
| [mromidev/claude-animated-shorts](https://github.com/mromidev/claude-animated-shorts) ✓ | ۳٬۲۴۸ (۱۴ نوامبر) | MIT | شورت داستانی ۵۵–۷۰ ثانیه‌ای؛ three.js داخل Remotion. خیلی تازه (۱ نوامبر) و تک‌کامیت. |
| [alexgreensh/anidoodle](https://github.com/alexgreensh/anidoodle) ✓ | ~۱٬۲۰۹ | Apache-2.0 | انیمیشن doodle/وایت‌برد. |
| [JohnHeibel/ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase) ✓ | ~۱٬۶۷۳ | MIT | بیس انیمیشن Claude. |
| [Leonxlnx/cinetic](https://github.com/Leonxlnx/cinetic) ✓ | — | MIT | ابزار ویدیوی سینمایی با کد. |
| [nateherkai/scroll-craft](https://github.com/nateherkai/scroll-craft) ✓ | ~۱٫۶–۴٫۴ هزار | MIT | اسکرول‌انیمیشن. |
| [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) ✓ | — | MIT | ۳۲ ایجنت تخصصی و ۳۱+ اسکیل برای Claude Code. |
| [mutonby/openshorts](https://github.com/mutonby/openshorts) ✓ | ۹٬۰۰۸ (۱۸ نوامبر) | MIT | کلیپ‌ساز AI از ویدیوی بلند: faster-whisper → PySceneDetect → Gemini 3.1 Flash-Lite → FFmpeg + MediaPipe/YOLOv8 ری‌فریم ۹:۱۶. MCP سرور داخلی با ۸ ابزار؛ Windows = Docker Desktop + WSL2. قید: کلید Gemini لازم دارد؛ امتیازدهی فارسی و رندر RTL تایید نشده. |
| [hkuds/videorag](https://github.com/hkuds/videorag) ✓ | ۳٬۵۲۰ (۱۰ نوامبر) | ⚠ NOASSERTION | VideoRAG (HKUDS، مقاله KDD 2026): از ویدیو سوال بپرس، جواب با ارجاع تایم‌استمپ بگیر؛ Vimo Desktop اپ دسکتاپی روی همین فریم‌ورک است. |
| [zhuyansen/awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills) ✓ | — | — | فهرست ۱۸۰ ریپوی اسکیل ویدیویی Claude (در زمان پست؛ از آن موقع بزرگ‌تر شده). |

**بدون ریپوی گیت‌هاب در این بخش:** manimvox (پکیج PyPI 0.5.0، MIT — یازده اسکیل ایجنتی، صدای پیش‌فرض Kokoro فارسی ندارد)؛ Skillry و Prompt-Motion (~۲۳۰ پرامپت) و Claude Animation Base در بریف‌های ویدیو آمده‌اند — Skillry و Prompt-Motion منبع پرامپت‌اند، نه ریپوی گیت‌هاب.

**قید مسیر:** Ghost Editor، Claude Shorts و MotionClone در بریف ویدیو-ادیتور فقط از اسلاید نقل شده‌اند و ریپوی دقیقشان تک‌تک باز نشده — پیش از نصب چکشان کن.

---

## ۵. صدا، موسیقی و روایت

| ریپو | ستاره (تاریخ بررسی) | لایسنس | چیست |
|---|---|---|---|
| [nota-daw/nota](https://github.com/nota-daw/nota) ✓ | ۴۵۱ (۱۴ نوامبر) | AGPL-3.0 | Nota — DAW رایگان، بدون حساب، ~۳۵ ساز/افکت داخلی، VST3، کنترل با موبایل از طریق QR، اینستالر ویندوز x64. سرور MCP داخلی (loopback، پیش‌فرض خاموش) برای کنترل با ایجنت. خیلی تازه (اوت ۲۰۲۶، نسخه 0.60.1). |
| [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio) ✓ | — | — | VoiceStudio — ژنراتور صدای AI رایگان با کلون صدا (از ریل @saeedkhorsandi0). |
| [boson-ai/higgs-audio](https://github.com/boson-ai/higgs-audio) ✓ | — | — | Higgs Audio v3 — TTS مکالمه‌ای Boson AI؛ فارسی در بالاترین سطح کیفی (خطا زیر ۵٪)؛ Creator Use Grant برای استفاده درآمدزا با ذکر منبع. از دایجست ۱۴ نوامبر. |

---

## ۶. اسکیل‌های عمومی Claude و دیزاین — ۱۰ اسکیل اکتبر + ۴ تازه

همه مستقیم از GitHub API بررسی شده‌اند (۱۰ و ۱۴ نوامبر ۲۰۲۶). **۶ تا در هر دو بریف تکراری‌اند** و اینجا یک‌بار آمده‌اند:

| ریپو | ستاره | لایسنس | چیست |
|---|---|---|---|
| [mattpocock/skills](https://github.com/mattpocock/skills) | ۳۲۰٬۷۹۵ | MIT | مجموعه اسکیل‌های کوچک Matt Pocock، از جمله handoff. |
| [obra/superpowers](https://github.com/obra/superpowers) | ۳۱۵٬۶۹۷ | MIT | متدولوژی توسعه: طوفان فکری، پلن، TDD، بازبینی. |
| [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | ۱۹۰٬۵۷۱ | MIT | Claude Code کد خیلی کمتری می‌نویسد؛ نیاز به SessionStart hook. |
| [morluto/rea](https://github.com/morluto/rea) | ۴۵۸٬۵۹۶ | MIT | Reverse Engineer Anything — از رفتار اپ تا باینری نیتیو. کمترین ربط به کارت. |
| [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) | ۱۴۷٬۴۵۳ | Apache-2.0 | کدبیس را به گراف دانش قابل‌پرس‌وجو تبدیل می‌کند — برای کدبیس Go بازی منچ. نصب PyPI با `graphifyy` (دو y). |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | ۱۱۵٬۲۹۲ | MIT | وب‌سایت‌هایی که شبیه ساخته AI نیستند. |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | ۱۰۹٬۸۷۳ | Apache-2.0 | واژگان دیزاین برای ایجنت؛ صراحتاً Antigravity را پشتیبانی می‌کند. انتخاب اول برای سایت پورتفولیو. |
| [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | ۶۹٬۱۳۳ | MIT | ممیزی امنیتی شش‌مرحله‌ای. قید: issue باز #۱۱ می‌گوید Antigravity ساب‌ایجنت‌ها را می‌کشد. |
| [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | ۶۷٬۶۰۷ | MIT | تحقیق ۳۰ روز اخیر در Reddit/X/YouTube/HN/Polymarket + وب. |
| [blader/humanizer](https://github.com/blader/humanizer) | ۶۸٬۹۹۲ | MIT | حذف نشانه‌های نوشتار AI از متن — فقط انگلیسی. |
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | ۶۶٬۹۵۴ | MIT | دیاگرام ادیتوریال تمیز — **انتخاب اول برای فیگورهای مکانیسم دارو و شبکه MDD**. |
| [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | ۵۴٬۷۱۸ | MIT | ۵۰ تم + کف کیفی سخت ضد AI-slop. |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | ۲۶٬۴۸۳ | MIT | ایده را به ماشین ایزومتریک تعاملی تبدیل می‌کند؛ README صراحتاً Antigravity را پشتیبانی می‌کند. یک فیگور ~۲ ساعت زمان ایجنت می‌برد. |
| [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) | ۱۰۲٬۶۵۰ | BSD-3-Clause | اسکرپینگ وب. |

**اولویت‌بندی برای تو (از بریف‌ها):** Diagram Design اول برای فیگورهای علمی؛ از سه‌تای Impeccable/Hallmark/Taste فقط یکی را بردار؛ Graphify برای کدبیس منچ.

---

## ۷. اینستاگرام، محتوا و ابزارهای جانبی

| ریپو | ستاره (تاریخ بررسی) | لایسنس | چیست |
|---|---|---|---|
| [Jakeschincariol/instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill) ✓ | ۳٬۰۸۱ (۲۶ اکتبر) | MIT | اسکیل ایجنتی اینستاگرام؛ بدون ثبت‌نام، بدون API key، بدون اتصال به حساب. |
| [Mahanaicoach/google-maps-scraper-kit](https://github.com/Mahanaicoach/google-maps-scraper-kit) ✓ | ۲٬۳۰۴ | MIT | اسکرپر Google Maps؛ سقف ~۱۲۰ نتیجه برای هر جستجو (سقف گوگل). |

---

## ۸. موبایل، بازی و ساخت اپ

| ریپو | ستاره (تاریخ بررسی) | لایسنس | چیست |
|---|---|---|---|
| [android/nowinandroid](https://github.com/android/nowinandroid) ✓ | ۲۲٬۰۶۸ (۱۰ نوامبر) | Apache-2.0 | اپ مرجع رسمی تیم اندروید گوگل — الگوی معماری برای اپ منچ. |
| [skydoves/nowinandroid-kmp](https://github.com/skydoves/nowinandroid-kmp) ✓ | — | — | پورت Kotlin Multiplatform همان اپ (کار جامعه، نه گوگل): یک کدبیس، اندروید/iOS/دسکتاپ/وب. |
| [xtool-org/xtool](https://github.com/xtool-org/xtool) ✓ | ~۱۴٬۰۰۰ | MIT | ساخت اپ iOS با Swift بدون مک — Swift CLI که SwiftPM را به اپ امضاشده تبدیل می‌کند و با USB روی آیفون نصب می‌کند. قید: دانلود یک‌باره Xcode.xip برای SDK لازم است؛ ویندوز یعنی WSL + USBIPD، نه نیتیو؛ اپ با Apple ID رایگان بعد از ۷ روز منقضی می‌شود؛ بدون App Store. |

---

## ۹. تولید ویدیوی AI با API — خلاف جهت کد-محور، فقط اگر تبلیغ لازم شد

| ریپو | ستاره (تاریخ بررسی) | لایسنس | چیست |
|---|---|---|---|
| [anil-matcha/Open-Generative-AI](https://github.com/anil-matcha/Open-Generative-AI) ✓ | ۳۴٬۱۸۶ (۱۲ نوامبر) | MIT | استودیوی متن‌باز ۶۰۰+ مدل؛ تولید پولی است (MuAPI، pay-as-you-go). عدد «~۳۲ هزار ستاره» در ریل‌ها مال همین ریپو است. |
| [Autom8AI/Open-Higgsfield-AI](https://github.com/Autom8AI/Open-Higgsfield-AI) ✓ | ۲٬۸۵۸ | ⚠ هیچ لایسنسی ثبت نشده (README ادعای MIT می‌کند) | فورک ریپوی بالایی؛ برای استفاده تجاری به anil-matcha تکیه کن، نه این. |
| [wide-trace/open-higgsfield](https://github.com/wide-trace/open-higgsfield) ✓ | ۵٬۷۲۷ | ⚠ لایسنس ندارد | به API پولی خود Higgsfield وصل می‌شود؛ آخرین کامیت ۱۷ سپتامبر ۲۰۲۶. |

---

## ۱۰. دایجست هفتگی Antigravity — فهرست جداگانه، اینجا تکرار نشده

دایجست‌های هفتگی (۷ و ۱۴ نوامبر) در مجموع **~۱۱۰ ابزار تاییدشده** دارند — وب‌دیزاین، مدل‌سازی سه‌بعدی، ویدیو/صدا، ورک‌فلو و اتوماسیون — که بیشترشان ابزار عمومی‌اند، نه حوزه تو. فایل‌هایشان اینجاست:

- `~/workspace/your_files/antigravity-digest/2026-11-07-*.md`
- `~/workspace/your_files/antigravity-digest/2026-11-14-*.md`

در کل فایل‌های کاری‌ات **۳۶۵ ریپوی یکتا** اسم برده شده (بیشترشان از همین دایجست‌ها)؛ آن‌هایی که به حوزه‌ات مربوط‌اند، در بخش‌های ۱ تا ۹ بالا آمده‌اند. اگر خواستی، همان ۱۱۰ ابزار دایجست را هم می‌توانم با همین فرمت طبقه‌بندی کنم.

---

## سه‌تای اول برای تو (اگر فقط سه‌تا را باز کنی)

1. **[K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)** — مستقیم‌ترین ربط به پروژه‌های بیوانفورماتیک و کشف داروت؛ ولی فقط زیرمجموعه مربوط را نصب کن.
2. **[google-research/paper-orchestra](https://github.com/google-research/paper-orchestra)** — الگوی ارجاع تاییدشده برای نوشتن مرور HFpEF.
3. **[cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)** — فیگورهای مکانیسم دارو و شبکه MDD برای پورتفولیو.
