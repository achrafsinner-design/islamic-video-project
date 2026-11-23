# PHASE 10: WORKFLOW & COST CONTROL — مريم وعيسى
*دليل سير العمل الكامل — أدوات متاحة، خيارات مجانية/مدفوعة، تكاليف، خط إنتاج*

---

## 🔍 أدوات التوليد المتاحة — تقييم الواقع

### ما نملكه في البيئة الحالية (Local/Installed)

| الأداة | الحالة | النسخة | ملاحظات |
|---|---|---|---|
| **FFmpeg** | ✅ مثبت | 9.1-full | معالجة فيديو/صوت كاملة |
| **yt-dlp** | ✅ مثبت | 2026.10.26 | تنزيل مراجع، ترجمات |
| **Whisper** | ✅ مثبت | OpenAI Whisper | تفريغ صوتي، سربتايتل |
| **Python** | ✅ مثبت | 3.x | سكريبتات أتمتة |
| **Node.js** | ✅ مثبت | v26.13.1 | أدوات JS، Remotion |
| **Git + GitHub CLI** | ✅ مثبت | أحدث | إدارة النسخ، رفع |
| **DaVinci Resolve** | ❌ غير مثبت | — | محرر مجاني قوي — **يحتاج تثبيت** |
| **Stable Diffusion** | ❌ غير مثبت | — | توليد صور محلي — **اختياري** |
| **ComfyUI** | ❌ غير مثبت | — | واجهة SD متقدمة — **اختياري** |

### أدوات سحابية (Cloud/API) — تحتاج مفاتيح/اشتراك

| الأداة | الوظيفة | التكلفة | جودة عربية | توصية |
|---|---|---|---|---|
| **Midjourney v6** | صور | $10/شهر (Basic) | ⭐⭐⭐⭐⭐ | **الأفضل للصور** |
| **DALL-E 3** (ChatGPT Plus) | صور | $20/شهر | ⭐⭐⭐⭐ | جيد، ضمن GPT |
| **Runway Gen-3** | فيديو | $15/شهر (Standard) | ⭐⭐⭐⭐ | فيديو 5-10ث |
| **Kling AI** | فيديو | مجاني (يوميًا) / $5-10 | ⭐⭐⭐⭐ | منافس قوي |
| **Luma Dream Machine** | فيديو | مجاني (30/شهر) / $10 | ⭐⭐⭐ | جيد للحركة |
| **ElevenLabs** | TTS عربي | $22/شهر (Creator) | ⭐⭐⭐⭐⭐ | **الأفضل للصوت** |
| **Suno AI** | موسيقى | مجاني (50/يوم) / $10 | ⭐⭐⭐ | موسيقى ثيمات |
| **Sora** (OpenAI) | فيديو | غير متاح عام | — | انتظار |

---

## 🆓 استراتيجية "مجاني أولاً" (Free-First Strategy)

### مسار الإنتاج المجاني بالكامل ($0)

```
IMAGES (صور):
├── Bing Image Creator (مجاني، 100/day) → DALL-E 3
├── Stable Diffusion WebUI (محلي، GPU مطلوب) → مجاني غير محدود
├── Leonardo.ai (150 tokens/day مجاني) → جيد للشخصيات
└── Ideogram (مجاني يومي) → جيد للنصوص العربية

VIDEO (فيديو):
├── Kling AI (مجاني: 66 crédits/يوم ≈ 6-10 مقاطع)
├── Luma Dream Machine (30 فيديو/شهر مجاني)
├── Runway Gen-2 (مجاني: 125 credits ≈ 4-5 مقاطع)
├── Stable Video Diffusion (محلي، GPU) → مجاني
└── Pika Labs (مجاني محدود)

AUDIO (صوت):
├── XTTS-v2 (محلي، Coqui TTS) → مجاني، يحتاج GPU
├── Edge TTS (مجاني، Microsoft) → أصوات عربية جيدة
├── Coqui TTS (محلي) → متعدد اللغات
└── ElevenLabs Free Tier (10k chars/شهر) → اختبار فقط

MUSIC (موسيقى):
├── Suno AI Free (50 أغنية/يوم) → ثيمات ليتموتيف
├── YouTube Audio Library (مجاني) → خلفيات
├── Pixabay Music (مجاني) → تنوع
└── Incompetech (مجاني مع نسبة) → Kevin MacLeod

EDITING (تحرير):
├── DaVinci Resolve Free (كامل) → **معيار الصناعة**
├── CapCut Desktop (مجاني) → سهل، تأثيرات
├── Kdenlive (مجاني، مفتوح المصدر) → لينكس/ويندوز
└── Shotcut (مجاني، مفتوح المصدر) → بسيط

SUBTITLES (سربتايتل):
├── Whisper Local (مثبت!) → مجاني، دقيق
├── Whisper.cpp (أسرع، CPU) → مجاني
└── Aegisub (مجاني) → تحرير يدوي
```

---

## 💰 خطة التكلفة الواقعية (Realistic Budget)

### السيناريو المقترح: "هجين ذكي" — جودة عالية، تكلفة منخفضة

| العنصر | الأداة المختارة | التكلفة | الكمية | الإجمالي |
|---|---|---|---|---|
| **صور رئيسية (Characters/Locations)** | Midjourney v6 | $10/شهر | 1 شهر | **$10** |
| **فيديو معجزات رئيسية (8-10 مقاطع)** | Kling AI (Free tier + $5 top-up) | $5 | 10 مقاطع | **$5** |
| **صوت السرد (Voiceover)** | ElevenLabs Creator | $22/شهر | 1 شهر | **$22** |
| **موسيقى ليتموتيف (6 ثيمات)** | Suno AI Free | $0 | 6 | **$0** |
| **تحرير** | DaVinci Resolve Free | $0 | — | **$0** |
| **سربتايتل** | Whisper Local | $0 | — | **$0** |
| **ثامنيلز** | Midjourney (نفس الاشتراك) | مشمول | 3 | **$0** |
| **مصاريف متنوعة** | GPU Cloud (RunPod/Colab) إن احتجت | $10 | — | **$10** |
| **المجموع** | | | | **$47** |

### خطة "الحد الأدنى" (Absolute Minimum) — $15-20

```
صور: Bing Image Creator (مجاني) + Leonardo.ai (مجاني)
فيديو: Kling Free + Luma Free (لا تكلفة)
صوت: Edge TTS / XTTS-v2 Local (مجاني)
موسيقى: Suno Free (مجاني)
تحرير: DaVinci Resolve Free (مجاني)
سربتايتل: Whisper Local (مجاني)
إضافي: $10 GPU cloud للتدريب/التسريع
المجموع: ~$10-15
```

### خطة "أعلى جودة" (Premium Quality) — $80-120

```
Midjourney $30 (Pro) + Runway Gen-3 $35 + ElevenLabs $22 + Suno $10 + GPU $20 = ~$117
```

---

## ⚡ خط الإنتاج اليومي (Daily Production Pipeline)

### اليوم 1-2: الصوت (Voiceover) — **أولوية قصوى**
```
لماذا أولاً؟ لأن كل التحرير يعتمد على توقيت الصوت.

خطوات:
1. [ ] تجهيز السيناريو النهائي مع علامات التوقيت
2. [ ] تسجيل/توليد الصوت كاملاً (WAV 48kHz/24bit)
3. [ ] تقطيع الصوت لكل مشهد (42 ملف VO_SC{XX}.wav)
4. [ ] قياس مدة كل ملف → تحديث التايملاين
5. [ ] مراجعة: هل المجموع 9:45-10:00؟ تعديل إن لزم.
```
**أداة**: ElevenLabs (أفضل جودة) أو XTTS-v2 Local (مجاني)

---

### اليوم 3-5: توليد الصور (Images) — **متوازي مع مراجعة الصوت**

```
استراتيجية "Personas ثابتة" (Character Consistency):
1. [ ] توليد "Base Images" للشخصيات الرئيسية:
     - Maryam طفلة (seed ثابت)
     - Maryam شابة (seed ثابت)
     - Isa رضيع (seed ثابت)
     - Isa نبي (seed ثابت)
     - Zakariya (seed ثابت)
     - Angel/Jibril (seed ثابت)
2. [ ] لكل شخصية: 4-6 زوايا/تعابير (نفس الـ seed، prompt معدّل)
3. [ ] توليد البيئات (Locations) بمفاتيح ألوان الفصول
4. [ ] توليد المشاهد المركبة (Character + Environment)
5. [ ] Upscale لأفضل 2-3 صور لكل مشهد (4K)

Prompts أساسية لكل شخصية (للنسخ واللصق):
```
**Maryam Child**: `young girl age 8-10, pure white hijab covering hair, simple white dress, innocent devout face, large dark eyes, soft golden sunlight, ancient Jerusalem temple mihrab, photorealistic 8K, cinematic lighting --seed 12345`
**Maryam Young**: `young woman age 16-18, pure white hijab, white simple dress, radiant face with divine light, peaceful expression, standing in ancient mihrab, golden glow halo, photorealistic 8K --seed 12346`
**Isa Infant**: `newborn baby wrapped in pure white swaddling cloth, large dark eyes with divine light, peaceful expression, ancient wooden manger, warm candlelight, cinematic chiaroscuro --seed 12347`
**Isa Prophet**: `man age 30, reddish-white complexion, shoulder-length straight hair, light beard, deep compassionate eyes, simple white wool robe, standing on Galilean hillside, olive trees, warm daylight, biblical epic --seed 12348`
**Zakariya**: `elderly man age 70+, long white beard, white turban, dark green robe, kind wise face, standing in ancient temple mihrab, soft daylight, photorealistic 8K --seed 12349`
```

---

### اليوم 6-8: توليد الفيديو (Video Clips) — **المشاهد الرئيسية فقط**

```
قاعدة: لا تولد فيديو لكل مشهد (مكلف، وقت).
اختر 10-12 مشهد "Hero" فقط:

Hero Scenes للفيديو (الباقي Ken Burns/Parallax على الصور):
1. SC01: طفل في المهد يتكلم (FLASH)
2. SC12: ظهور جبريل (FLASH)
3. SC16: مخاض/نخلة — ماء يتفجر (MIRACLE)
4. SC17: تمر تسقط بطيء (MIRACLE)
5. SC21: كلام المهد — ردود فعل (MIRACLE EXPLOSION)
6. SC24: معجزة الطير من الطين (MIRACLE)
7. SC26: إحياء الميت (MIRACLE)
8. SC27: المائدة تنزل (MIRACLE)
9. SC30: رفعة للسماء (DIVINE ASCENT)
10. SC33: نزول على المنارة (DAWN PROMISE)
11. SC38: تداخل المهد/المنارة (OVERLAY)
12. SC41: كعبة/طواف (UNITY)

للمشاهد الباقية: استخدم صوراً مع:
- Ken Burns (slow zoom/pan)
- Parallax 2.5D (فصل طبقات foreground/background)
- Particles خفيفة (grain، dust، light rays)
```

---

### اليوم 9-11: التحرير (Editing in DaVinci Resolve)

```
مراحل التحرير:

1. ROUGH CUT (اليوم 9):
   [ ] استيراد الصوت المقطّع (42 ملف VO)
   [ ] وضعها على التايملاين حسب التايملاين المخطط
   [ ] إضافة صور placeholder (رمادية) مكان كل مشهد
   [ ] ضبط التوقيت: هل المجموع 9:45-10:00؟
   [ ] إضافة Markers للفصول، المشاهد، موسيقى

2. FINE CUT (اليوم 10):
   [ ] استبدال Placeholders بالصور المولدة
   [ ] استبدال 12 Hero Scene بمقاطع الفيديو
   [ ] تطبيق Ken Burns/Parallax على الباقي
   [ ] إضافة الانتقالات حسب Transition Map
   [ ] مزامنة SFX مع الصورة (Foley، Ambience، Impacts)

3. SOUND & COLOR (اليوم 11):
   [ ] استيراد موسيقى (Stems) → وضع على Tracks
   [ ] Sidechain Ducking للموسيقى تحت السرد
   [ ] مكس SFX مستويات
   [ ] Color Grading: تطبيق LUTs فصلية
   [ ] Global Grade: Film grain، Vignette خفيف
   [ ] QC كامل: Loudness، Peak، Sync، Visual QC
```

---

### اليوم 12: التصدير والتسليم (Export & Deliver)

```
[ ] Export Master (ProRes 422 HQ 4K)
[ ] Export YouTube (H.264 4K، -14 LUFS)
[ ] Export Shorts/Reels (7 مقاطع، 9:16، 1080p)
[ ] Generate Subtitles (Whisper → SRT + ASS styled)
[ ] Thumbnails (3 نسخ، 1280×720)
[ ] Description + Chapters + Tags + Sources
[ ] Upload + Schedule
[ ] Backup Project + Assets
```

---

## 🛡️ قائمة التحقق من الامتثال الإسلامي (Islamic Compliance Checklist)

**يجب التحقق قبل كل Export نهائي:**

### تصوير الشخصيات المقدسة
- [ ] **النبي محمد ﷺ**: لم يُصوَّر أبداً (لا وجه، لا جسم، لا ظل، لا صوت)
- [ ] **الأنبياء الآخرون** (عيسى، موسى، إبراهيم، زكريا، يحيى): صور بوقار، لا ملامح مبتدعة
- [ ] **مريم عليها السلام**: حجاب كامل، وقار، لا إظهار جمال/زينة
- [ ] **الصحابة/التابعون**: بوقار، ملابس تاريخية دقيقة

### العقيدة والسرد
- [ ] عيسى موصوف **"عبد الله ورسوله"** في كل موضع
- [ ] **"بإذن الله"** مذكور مع كل معجزة
- [ ] نفي القتل والصلب **صريح وواضح**: "ما قتلوه وما صلبوه"
- [ ] الرفعة إلى الله **مؤكدة**: "بل رفعه الله إليه"
- [ ] لا تجسيم، لا تشبيه، لا نسبة بنوة لله
- [ ] الآيات/الأحاديث **نصها صحيح**، موضوعة في سياقاتها

### اللغة والأسلوب
- [ ] العربية الفصحى سليمة نحوياً وإملائياً
- [ ] أسماء الله الحسنى مكتوبة كاملاً (لا اختصارات)
- [ ] الصلاة على النبي ﷺ عند ذكره (صلى الله عليه وسلم)
- [ ] الرضوان على الصحابة/التابعين (رضي الله عنهم)

### المراجع
- [ ] كل معلفة رئيسية لها مصدر (آية/حديث/تفسير معتبر)
- [ ] قائمة مصادر في الوصف (Description)

---

## 📊 تتبع التكاليف (Cost Tracking Template)

```
MARYAM_ISA_COST_LOG.csv

Date,Category,Tool,Quantity,Unit_Cost,Total_Cost,Notes
2026-11-24,Images,Midjourney,1 month,$10,$10,Basic plan
2026-11-24,Video,Kling AI,top-up,$5,$5,10 hero clips
2026-11-24,Voice,ElevenLabs,1 month,$22,$22,Creator plan
2026-11-24,GPU,RunPod,5 hours,$10,$10,XTTS training
2026-11-25,Images,Midjourney,extra,$0,$0,same sub
...
TOTAL: $47
```

---

## 🚀 نصائح توفير المال (Money-Saving Tips)

1. **استخدم Free Trials بذكاء**: سجل في Runway/Kling/ElevenLabs بحسابات مختلفة للـ Free Tier
2. **Batch Generation**: ولّد كل صور الشخصيات دفعة واحدة (توفير وقت/GPU)
3. **Reuse Assets**: نفس صورة "مريم في المحراب" تصلح لـ 3 مشاهد بتعديلات طفيفة
4. **Ken Burns > Video**: 70% من المشاهد صور + حركة كاميرا، ليس فيديو
5. **Suno Free للموسيقى**: 50 أغنية/يوم = ثيمات لا نهائية مجاناً
6. **Whisper Local للسربتايتل**: دقة 95%+، صفر تكلفة
7. **DaVinci Free**: لا تشتري Premiere/Final Cut
8. **GitHub للنسخ الاحتياطي**: مجاني، غير محدود للكود/السكريبتات

---

## ⚠️ مخاطر وخطط بديلة (Risks & Mitigation)

| المخاطر | الاحتمال | التأثير | خطة التخفيف |
|---|---|---|---|
| **Midjourney يرفض prompts دينية** | متوسط | عالٍ | استخدم Leonardo.ai / Stable Diffusion Local |
| **Kling/Luma لا ينتجان جودة مطلوبة** | متوسط | متوسط | ادمج مقاطع قصيرة + Ken Burns على الصور |
| **ElevenLabs تفتقر صوت مغربي أصيل** | منخفض | متوسط | استخدم XTTS-v2 مع fine-tuning على صوت مغربي |
| **Whisper يخطئ في العربية القرآنية** | متوسط | متوسط | مراجعة يدوية + تصحيح في Aegisub |
| **DaVinci Resolve معقد للتعلم** | متوسط | عالٍ | دروس YouTube محددة (3 ساعات تعلم أساسي) |
| **تجاوز الميزانية** | منخفض | متوسط | تتبع يومي، إيقاف عند $60 |
| **مشاكل حقوق نشر موسيقى/صور** | منخفض | عالٍ | فقط أصول مولدة/مرخصة، توثيق كل prompt |
| **رفض يوتيوب للفيديو (سياسة دينية)** | منخفض | عالٍ | مراجعة Guidelines، تجنب ادعاءات طبية/عجائبية غير موثقة |

---

## ✅ قائمة التشغيل النهائية (Final Checklist قبل النشر)

```
PRE-PUBLISH CHECKLIST:

TECHNICAL:
[ ] Master 4K ProRes HQ موجود
[ ] YouTube 4K H.264 -14 LUFS موجود
[ ] Shorts 7 clips 9:16 موجود
[ ] Subtitles AR/EN/FR (SRT + ASS) موجود
[ ] Thumbnails 3 versions موجود
[ ] Project backup على GitHub + Cloud

CONTENT:
[ ] Islamic Compliance Checklist: كلها ✅
[ ] Sources bibliography في الوصف
[ ] Chapters timestamps دقيقة
[ ] Title/Description محسّن SEO
[ ] Tags (15-20) ذات صلة
[ ] Playlist مُضاف

QUALITY:
[ ] شاهد الفيديو كاملاً على 4K — لا غلطات
[ ] تفقد السربتايتل على يوتيوب — متزامنة
[ ] تفقد الصوت على سماعات/موبايل — واضح
[ ] تفقد الثامنيل على موبايل — مقروء

LEGAL/ETHICAL:
[ ] لا أصول مسروقة — كلها مولدة/مرخصة
[ ] Prompts موثقة للمراجعة
[ ] لا ادعاءات طبية/علمية غير مثبتة
[ ] احترام حقوق النشر للمصادر النصية
```

---

## 📈 ما بعد النشر (Post-Launch)

```
WEEK 1:
[ ] رد على كل تعليق (أول 100)
[ ] ثبت تعليق بمصادر/مراجع
[ ] شارك Shorts يومياً
[ ] راقب Analytics: CTR، AVD، Subs

WEEK 2-4:
[ ] تحليل: أي المشاهد أعلى retention؟
[ ] قص مقاطع إضافية للـ Shorts من نقاط الاحتفاظ
[ ] استطلاعات: "أي قصة تالية تريدون؟"
[ ] بناء Community: Discord/Telegram

MONTH 2+:
[ ] فيديو تالي نفس الـ Pipeline
[ ] تحسين بناءً على Data
[ ] تعاون مع قنوات مشابهة
[ ] Monetization: Patreon/BuyMeCoffee للتمويل الذاتي
```

---

*دليل سير العمل والتكلفة مكتمل. التكلفة المستهدفة: $47. الجودة: سينمائية 4K. قابل للتكرار لفيديوهات قادمة.*