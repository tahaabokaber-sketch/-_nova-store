# NOVA STORE — Design Direction

## Three initial approaches

### Theme Name: Quiet Atelier
**Very Brief Intro:** تجربة متجر تحريرية هادئة تجمع بين الفخامة المعاصرة والوضوح العملي، مع إحساس صالة عرض منتقاة لا كتالوج مزدحم.
**Probability:** 0.07

### Theme Name: Studio Utility
**Very Brief Intro:** نظام بصري عملي مستوحى من استوديوهات التصميم، يعتمد على شبكة دقيقة وعلامات فهرسة واضحة وتباين محسوب.
**Probability:** 0.03

### Theme Name: Midnight Signal
**Very Brief Intro:** اتجاه ليلي عالي التباين بلمسات ضوئية دقيقة يوحي بالتقنية والمنتجات الجديدة دون الوقوع في أسلوب سايبربانك صاخب.
**Probability:** 0.08

## Selected Direction: Quiet Atelier

### Design Movement
تحريرية معاصرة Contemporary Editorial Minimalism، مستلهمة من مجلات الموضة الراقية وصالات العرض ذات الإضاءة الطبيعية.

### Core Principles
1. الفخامة تأتي من التباعد والمواد اللونية الهادئة، لا من الزخرفة الزائدة.
2. كل قسم يجب أن يملك وظيفة واضحة ومسار قراءة مريح.
3. الصور كبيرة وهادئة، والنصوص قصيرة ودقيقة.
4. التفاعل محسوس وسريع، لكنه لا ينافس المنتجات على الانتباه.

### Color Philosophy
قاعدة عاجية دافئة تمنح الصفحة إحساس الورق الفاخر، وفحم عميق للنصوص، مع لون نحاسي محروق كإشارة امتلاك للعلامة. يستخدم النحاس في الحالات المهمة فقط: الأسعار المميزة، حالات hover، والشارات، كي يبقى ذا قيمة بصرية.

### Layout Paradigm
تخطيط تحريري غير متماثل: hero بتقسيم 5/7، عناوين محاذاة يسار، شرائط فهرسة أفقية، وشبكات منتجات مرنة تتنفس حول الصور بدل حشرها في بطاقات متساوية.

### Signature Elements
- خط نحاسي رفيع كعلامة فصل وفهرسة.
- أرقام أقسام صغيرة بحروف متباعدة مثل كتالوج معرض.
- زوايا مربعة أو مستديرة بخفة، مع ظلال ورقية ناعمة بدل البطاقات الثقيلة.

### Interaction Philosophy
التفاعل يوضح ولا يبالغ: hover يرفع المنتج بضعة بكسلات ويكشف الإجراء، الأزرار تستجيب بضغط بصري قصير، والنوافذ الجانبية تأتي من نقطة التفاعل.

### Animation
الانتقالات بين 160 و240ms باستخدام ease-out حاد، مع stagger خفيف 40ms لعناصر القوائم. الصور تستخدم scale صغيرًا عند hover، وtoast يظهر من الأسفل بحركة قصيرة. احترام prefers-reduced-motion إلزامي.

### Typography System
عناوين العرض: Cormorant Garamond، وزن 500–600، بحروف كبيرة ومساحات واسعة عند الحاجة. النص والواجهات: DM Sans، أوزان 400–600. التسلسل: H1 كبير ومائل قليلًا، H2 تحريري متوسط، labels صغيرة uppercase، ونصوص وصفية بعرض سطر مريح.

### Brand Essence
NOVA STORE هو متجر انتقائي للمنتجات اليومية المصممة بعناية، لمن يفضل الجودة والوضوح على الضجيج، مع تجربة شراء تبدو كاختيار شخصي لا كبحث عشوائي.
**Personality:** refined، intentional، warm.

### Brand Voice
العناوين قصيرة وواثقة، الدعوات للفعل مباشرة دون ضغط، والmicrocopy إنساني ومحدد.
- “Objects with a point of view.”
- “Find the piece that stays.”

### Wordmark & Logo
رمز نجمي هندسي من أربع شفرات غير متماثلة، يوحي بالمدار والاختيار، بجانب wordmark NOVA STORE بحروف DM Sans متباعدة. الرمز يستخدم منفردًا كfavicon وبصمة للعلامة.

### Signature Brand Color
Burnished Copper — `#B66A4A`، نحاسي دافئ غير لامع يربط بين الحرفية والحداثة ويظهر في التفاصيل لا كخلفية طاغية.

## Style Decisions
- Light editorial storefront; no purple gradients and no neon treatment.
- Use generated hero/brand imagery as focal points, with remote product imagery for mock catalog items.
- Keep all components spacious, tactile, and asymmetric where the content allows.

## Style Decisions
- Product imagery avoids loud marketplace stock cues and visible third-party branding; default to warm natural-light photography, tactile materials, quiet backgrounds, and curated crops.
- Homepage product sections use a breathable editorial rhythm with one selective feature image rather than repeated equal-card density; the practical shop grid remains functional.
- Burnished Copper `#B66A4A` is reserved for thin rules, small labels, badges, key numerals, prices, and action accents; it is not used as a large decorative fill except for the dark announcement strip.
