# Web Page Prompt — منصة المكتب الفني الذكية للمقاولات والمناقصات

## Page Goal & Primary CTA
الهدف من الصفحة هو تحويل اهتمام فرق المناقصات والمكاتب الفنية في شركات المقاولات السعودية إلى إجراء واضح: **حجز عرض توضيحي (Request Demo)** أو **بدء تجربة تجريبية (Start Pilot)**، عبر عرض قيمة المنصة كحل مساعد ومحكوم يختصر وقت إعداد المخرجات الفنية بنسبة 60–80% مع تتبّع واضح للمصادر والمراجعات البشرية.

## Information Architecture (Site Sections Order)
1. Global Header (Logo, language toggle, top CTA)
2. Hero (positioning, proof points, primary + secondary CTAs)
3. Pain-to-Value Proof Strip (current pain vs platform impact)
4. How It Works (5 stages workflow)
5. Outputs (grouped deliverables)
6. Smart Agents Orchestra (12 agents + expandable details)
7. App Dashboard Preview (static mock of modules)
8. For Who (role-based value mapping)
9. Security & Governance
10. Tech Architecture Summary
11. MVP Roadmap (Phase 1/2/3)
12. Testimonials / Proof Placeholder
13. Final CTA + Lead Form
14. Footer (quick links, legal placeholders, language switch)

---

## Wireframe-Level Section Specs

### 1) Global Header (AR / EN)
**Section Title (AR / EN):**
- العربية: **رأس الصفحة والتنقّل**
- English: **Global Header & Navigation**

**Objective**
- تقديم هوية احترافية سريعة وإتاحة الوصول الفوري للتحويل (Demo/Pilot) وتبديل اللغة RTL/LTR.

**Key UI Components**
- Logo (wordmark + optional icon)
- Navigation links: الحل | آلية العمل | المخرجات | الوكلاء | الأمان | خارطة MVP | تواصل
- Language toggle (AR / EN)
- CTA buttons: Request Demo (primary), Start Pilot (secondary)
- Sticky header on scroll

**Arabic Copy**
- Headline: **منصة المكتب الفني الذكية للمقاولات والمناقصات**
- Subheadline: **مساعد ذكي ومحكوم لإنتاج مستندات المناقصات بسرعة ودقة أعلى.**
- CTA labels:
  - **اطلب عرضًا توضيحيًا**
  - **ابدأ تجربة تجريبية**

**English Copy**
- Headline: **TenderForge AI — Smart Technical Office Platform**
- Subheadline: **A governed AI assistant for faster, higher-quality bid documentation.**
- CTA labels:
  - **Request Demo**
  - **Start Pilot**

**Interactions/States**
- Sticky + subtle shadow after scroll threshold
- Active nav highlight by section intersection observer
- Language toggle switches dir + typographic scale

---

### 2) Hero (AR / EN)
**Section Title (AR / EN):**
- العربية: **القيمة الأساسية للمنصة**
- English: **Hero — Positioning & Conversion**

**Objective**
- الإجابة على سؤال المشتري: *ما هي المنصة ولماذا الآن؟* مع عرض دليل القيمة بسرعة.

**Key UI Components**
- H1 + supportive paragraph
- Primary/secondary CTA pair
- 3–4 quick proof chips
- Right-side enterprise visual (dashboard mock or process visualization)

**Arabic Copy**
- Headline: **حوّل إعداد مستندات المناقصات من عبء يدوي إلى سير عمل ذكي قابل للتدقيق.**
- Subheadline: **منصة ثنائية اللغة تساعد فريقك على قراءة كراسة الشروط، استخراج المتطلبات، توليد المخرجات الفنية والمالية، ومراجعتها قبل التسليم — مع تقليل الوقت بنسبة 60–80%.**
- Bullets:
  - **خفض وقت التجهيز من أسابيع إلى أيام.**
  - **تقليل أخطاء السهو والتعارضات قبل التسليم.**
  - **تتبّع مصدر كل فقرة عبر الاستشهادات.**
  - **مراجعة بشرية إلزامية قبل الاعتماد النهائي.**
- CTA labels:
  - **اطلب عرضًا توضيحيًا**
  - **ابدأ تجربة تجريبية**

**English Copy**
- Headline: **Turn bid preparation from manual effort into a governed intelligent workflow.**
- Subheadline: **A bilingual platform that reads tender documents, extracts requirements, generates technical/financial outputs, and routes them for human review — with 60–80% cycle-time reduction.**
- Bullets:
  - **Cut preparation cycles from weeks to days.**
  - **Reduce omission and conflict risks pre-submission.**
  - **Trace every generated statement to source citations.**
  - **Enforce human approval before final delivery.**
- CTA labels:
  - **Request Demo**
  - **Start Pilot**

**Interactions/States**
- CTA hover/press states
- Optional animated counter (time reduction range)
- “Processing sample project” micro-animation (lightweight)

---

### 3) Pain-to-Value Proof Strip (AR / EN)
**Section Title (AR / EN):**
- العربية: **من التحدّي إلى الأثر**
- English: **Pain-to-Value Proof Strip**

**Objective**
- تأكيد الإلحاح التجاري عبر مقابلة “المشكلة الحالية” مع “الأثر التشغيلي”.

**Key UI Components**
- 5-column card strip (pain → impact)
- Simple before/after badges

**Arabic Copy**
- Headline: **التحديات اليومية في المناقصات... وحلّها داخل المنصة**
- Bullets:
  - **قراءة يدوية مرهقة** → **تحليل ذكي سريع للمجلدات والملفات**
  - **إعادة كتابة متكررة** → **قوالب توليد موحّدة قابلة للتخصيص**
  - **تفاوت الجودة بين الفرق** → **حوكمة مخرجات ومعايير اعتماد**
  - **تعقيد عربي/إنجليزي** → **تنسيق ثنائي اللغة متّسق**
  - **فوات متطلبات إلزامية** → **تنبيهات فجوات وتعارضات تلقائية**

**English Copy**
- Headline: **Daily bid pain points, mapped to measurable platform impact**
- Bullets:
  - **Manual reading overload** → **Fast AI parsing across large document sets**
  - **Repeated rewriting** → **Standardized generation templates**
  - **Inconsistent team quality** → **Governed review and approval gates**
  - **Bilingual formatting friction** → **Consistent Arabic/English output structure**
  - **Missed mandatory requirements** → **Gap and conflict detection alerts**

**Interactions/States**
- Optional horizontal scroll for mobile cards

---

### 4) How It Works (5 Phases) (AR / EN)
**Section Title (AR / EN):**
- العربية: **كيف تعمل المنصة؟ (5 مراحل)**
- English: **How It Works (5 Stages)**

**Objective**
- تبسيط آلية العمل إلى تدفّق واضح قابل للفهم خلال أقل من 30 ثانية.

**Key UI Components**
- Numbered stepper/timeline with icons
- Expandable detail per stage

**Arabic Copy**
- Headline: **مسار عمل واضح من الرفع إلى الاعتماد**
- Stages:
  1. **رفع الملفات:** رفع كراسة الشروط، المواصفات، الجداول، ورسومات المشروع.
  2. **الفهم والتحليل:** OCR + Parsing + استخراج المتطلبات والكيانات الرئيسية.
  3. **اختيار نوع المخرجات:** فني/مالي/خطابات/تقارير تنفيذية.
  4. **تشغيل أوركسترا الوكلاء:** توزيع المهام على الوكلاء المتخصصين.
  5. **مراجعة بشرية وتصدير:** مراجعة، اعتماد، ثم تصدير Word/PDF/Excel.
- CTA label: **شاهد تدفّق العمل بالتفصيل**

**English Copy**
- Headline: **A clear workflow from upload to approved submission**
- Stages:
  1. **Upload:** Tender docs, specs, BoQ sheets, and supporting files.
  2. **Understand:** OCR, parsing, requirement extraction, entity mapping.
  3. **Choose Output:** Technical, financial, letters, executive packages.
  4. **Run Agents:** Specialized agent orchestration by output type.
  5. **Human Review & Export:** Validate, approve, export to Word/PDF/Excel.
- CTA label: **View Detailed Workflow**

**Interactions/States**
- Step states: idle / active / completed
- Loading state: “جارٍ تحليل الملفات…” / “Analyzing documents…”

---

### 5) Outputs Section (AR / EN)
**Section Title (AR / EN):**
- العربية: **المخرجات التي تنتجها المنصة**
- English: **Outputs Generated by the Platform**

**Objective**
- عرض ناتج ملموس يجيب: *ماذا سأحصل عليه فعليًا؟*

**Key UI Components**
- 4 grouped output cards
- File-type tags (DOCX/PDF/XLSX)

**Arabic Copy**
- Headline: **مخرجات جاهزة للتدقيق والتسليم**
- Groups:
  - **تمهيدية:** خطاب تقديم، ملخص تنفيذي، خطاب استفسارات.
  - **فنية:** المنهجية، خطة التنفيذ، خطة الجودة، خطة HSE، تحليل المخاطر.
  - **مالية/تعاقدية:** الجداول المالية، الافتراضات، الاستثناءات، الردود التعاقدية.
  - **إدارية/تنفيذية:** مصفوفة المتطلبات، تقرير فجوات، خطة التسليمات.
- CTA label: **استعرض أمثلة المخرجات**

**English Copy**
- Headline: **Submission-ready outputs with built-in traceability**
- Groups:
  - **Introductory:** Cover letter, executive brief, clarification letter.
  - **Technical:** Method statement, execution plan, QA/QC plan, HSE plan, risk analysis.
  - **Financial/Contractual:** Pricing schedules, assumptions, exclusions, contractual responses.
  - **Executive/Deliverables:** Requirement matrix, gap report, deliverables schedule.
- CTA label: **Explore Output Samples**

**Interactions/States**
- Card expansion for sample snippets
- Export success toast: “تم تجهيز الملف للتنزيل” / “Export package ready”

---

### 6) Smart Agents Orchestra (12 Agents) (AR / EN)
**Section Title (AR / EN):**
- العربية: **أوركسترا الوكلاء الذكية (12 وكيلًا)**
- English: **Smart Agents Orchestra (12 Agents)**

**Objective**
- تقديم الذكاء الاصطناعي بشكل موثوق ومفهوم: *وكلاء متخصصون + حوكمة + مراجعة بشرية*.

**Key UI Components**
- Grid of 12 agent cards
- Accordion for “role + generated output”
- Governance disclaimer banner

**Arabic Copy**
- Headline: **وكلاء متخصصون يعملون بتنسيق واحد تحت إشراف بشري**
- Subheadline: **كل وكيل مسؤول عن مهمة محددة ومخرجات قابلة للتدقيق والاستشهاد.**
- Agents list:
  1. **وكيل الاستيعاب الوثائقي:** يفهرس المستندات ويبني خريطة المحتوى.
  2. **وكيل استخراج المتطلبات:** يستخرج الإلزاميات والشروط المرجعية.
  3. **وكيل كشف الفجوات:** يحدد المتطلبات غير المغطاة.
  4. **وكيل كشف التعارضات:** يرصد التعارض بين المواصفات والجداول.
  5. **وكيل الربط BoQ/Specs:** يربط البنود بالكود والمواصفات.
  6. **وكيل التوليد الفني:** ينتج المنهجية والخطط الفنية.
  7. **وكيل الجودة QA/QC:** يراجع توافق خطط الجودة.
  8. **وكيل HSE:** يكوّن خطة السلامة والصحة والبيئة.
  9. **وكيل الجدولة والتخطيط:** يبني منطق خطة التنفيذ والتسلسل.
  10. **وكيل التكلفة والتسعير:** يدعم الاتساق المالي والافتراضات.
  11. **وكيل الخطابات والعروض:** يولّد الخطابات الرسمية والمراسلات.
  12. **وكيل المراجعة والامتثال:** يمنح درجة ثقة ويولّد سجل التدقيق.
- CTA label: **عرض مهام كل وكيل**

**English Copy**
- Headline: **Twelve specialized agents, orchestrated under human control**
- Subheadline: **Each agent owns a defined responsibility and auditable output.**
- Agents list:
  1. **Document Intelligence Agent:** Indexes documents and maps structure.
  2. **Requirements Extraction Agent:** Captures mandatory clauses and criteria.
  3. **Gap Detection Agent:** Flags uncovered requirements.
  4. **Conflict Detection Agent:** Detects inconsistencies across files.
  5. **BoQ-Spec Linking Agent:** Connects line items to spec references.
  6. **Technical Drafting Agent:** Generates methodologies and technical plans.
  7. **QA/QC Agent:** Verifies quality-plan completeness.
  8. **HSE Agent:** Drafts safety and environmental documentation.
  9. **Planning Agent:** Builds execution sequence and timeline logic.
  10. **Costing Agent:** Supports financial consistency and assumptions.
  11. **Letters Agent:** Produces formal bid letters and correspondence.
  12. **Compliance Review Agent:** Assigns confidence score and audit record.
- CTA label: **View Agent Responsibilities**

**Interactions/States**
- Accordion open/close for each agent
- Confidence badge levels: High / Medium / Needs Review

---

### 7) App Dashboard Preview (Static Mock) (AR / EN)
**Section Title (AR / EN):**
- العربية: **معاينة واجهة التطبيق**
- English: **App-Style Dashboard Preview**

**Objective**
- نقل المستخدم من “مفهوم تسويقي” إلى “تصوّر منتج عملي” بواجهة SaaS واقعية.

**Key UI Components**
- Mock browser frame
- Sidebar modules:
  - Dashboard
  - Project Page
  - Documents
  - Agents
  - Reports
  - Letters
  - Admin
- Main panel widgets: project health, pending approvals, requirement coverage, export queue

**Arabic Copy**
- Headline: **لوحة تحكم موحدة لإدارة دورة المناقصة كاملة**
- Bullets:
  - **متابعة نسبة تغطية المتطلبات لحظيًا.**
  - **دردشة ذكية مع المشروع ونتائج موثقة بالمصدر.**
  - **تاريخ إصدارات واضح لكل مستند ومخرج.**

**English Copy**
- Headline: **Unified workspace for end-to-end tender operations**
- Bullets:
  - **Track requirement coverage in real time.**
  - **Chat with project context and source-grounded answers.**
  - **Maintain clear version history for every output.**

**Interactions/States**
- Tab switching between modules
- Empty state for new projects
- Processing overlay for agent run

---

### 8) For Who (Role Mapping) (AR / EN)
**Section Title (AR / EN):**
- العربية: **لمن صُممت المنصة؟**
- English: **Who Is It For?**

**Objective**
- مطابقة القيمة مع الأدوار المؤثرة في قرار الشراء والتنفيذ.

**Key UI Components**
- Role-value cards

**Arabic Copy**
- Headline: **قيمة متخصصة لكل دور في فريق المناقصة**
- Roles:
  - **مدير المكتب الفني:** حوكمة الجودة وتسريع الاعتماد.
  - **مهندس مناقصات:** استخراج المتطلبات وتوليد المسودات بسرعة.
  - **QA/QC:** مراجعة اتساق الجودة وقابلية التدقيق.
  - **HSE:** تجهيز خطط السلامة وفق سياق المشروع.
  - **التخطيط:** بناء التسلسل التنفيذي والافتراضات الزمنية.
  - **التكلفة:** دعم الردود المالية وضبط الافتراضات.
  - **الإدارة التنفيذية:** رؤية تنفيذية ومؤشرات جاهزية العرض.

**English Copy**
- Headline: **Role-specific value across the bidding organization**
- Roles:
  - **Technical Manager:** Governance, consistency, faster approvals.
  - **Tender Engineer:** Faster requirement extraction and draft generation.
  - **QA/QC:** Traceable quality checks and compliance support.
  - **HSE Lead:** Context-aware safety and environmental plans.
  - **Planning Engineer:** Execution sequencing and timeline foundations.
  - **Cost Engineer:** Financial consistency and assumption control.
  - **Executives:** Readiness visibility and risk-informed decisions.

---

### 9) Security & Governance (AR / EN)
**Section Title (AR / EN):**
- العربية: **الأمن والحوكمة**
- English: **Security & Governance**

**Objective**
- معالجة سؤال الثقة: *هل يمكن الاعتماد على المنصة في بيئة مؤسسية حساسة؟*

**Key UI Components**
- Governance checklist cards
- Policy-compatible disclaimer

**Arabic Copy**
- Headline: **ذكاء اصطناعي مساعد ضمن ضوابط تشغيل مؤسسية**
- Bullets:
  - **Human-in-the-loop:** لا اعتماد نهائي دون مراجعة بشرية.
  - **الاستشهادات:** ربط كل مخرج بمصدره في المستندات.
  - **درجة الثقة:** عرض confidence score لكل جزء مولّد.
  - **إدارة الإصدارات:** تتبّع نسخ وتغييرات المستندات.
  - **سجل تدقيق:** توثيق من فعل ماذا ومتى.
  - **قفل القوالب:** منع التعديلات غير المصرّح بها.
  - **خصوصية البيانات:** معالجة بيانات حساسة بسياسات تشغيل داخلية.
  - **صياغة حيادية:** **قابل للتوافق مع سياسات الشركة**.

**English Copy**
- Headline: **Assistive AI with enterprise governance controls**
- Bullets:
  - **Human-in-the-loop:** No final submission without human approval.
  - **Citations:** Every generated section is source-traceable.
  - **Confidence Score:** Visibility per generated block.
  - **Version Control:** Document and output history tracking.
  - **Audit Trail:** User action logs by time and artifact.
  - **Template Locking:** Controlled editing rights for core templates.
  - **Data Sensitivity:** Designed for confidential tender workflows.
  - **Neutral compliance wording:** **Configurable to internal policy requirements**.

**Interactions/States**
- Tooltip definitions for governance terms

---

### 10) Tech Architecture Summary (AR / EN)
**Section Title (AR / EN):**
- العربية: **ملخص البنية التقنية**
- English: **Technology Architecture Summary**

**Objective**
- طمأنة الفرق التقنية بأن المنصة قابلة للتنفيذ والتوسّع والتكامل.

**Key UI Components**
- Layered architecture diagram (simple)
- Accordion for “stack details”

**Arabic Copy**
- Headline: **بنية حديثة قابلة للتوسع والتشغيل المؤسسي**
- Bullets:
  - **الواجهة:** Next.js + Tailwind + دعم RTL/LTR.
  - **الخدمات الخلفية:** FastAPI أو Node.js (خدمات معيارية).
  - **قاعدة البيانات:** PostgreSQL.
  - **التخزين:** Object Storage للملفات والمرفقات.
  - **الفهرسة الذكية:** Vector DB للبحث الدلالي.
  - **نماذج الذكاء:** OpenAI + Gemini وفق نوع المهمة.
  - **المهام غير المتزامنة:** Queue/Workers لتشغيل الوكلاء.

**English Copy**
- Headline: **Modern, modular architecture for scale and governance**
- Bullets:
  - **Frontend:** Next.js + Tailwind with RTL/LTR support.
  - **Backend:** FastAPI or Node.js service layer.
  - **Database:** PostgreSQL.
  - **Storage:** Object storage for document artifacts.
  - **Semantic Retrieval:** Vector database for smart search.
  - **AI Models:** OpenAI + Gemini by workload profile.
  - **Async Processing:** Queue/worker orchestration for agents.

---

### 11) MVP Roadmap (Phase 1/2/3) (AR / EN)
**Section Title (AR / EN):**
- العربية: **خارطة طريق MVP**
- English: **MVP Roadmap**

**Objective**
- مواءمة توقعات العملاء عبر مراحل تطوير واضحة.

**Key UI Components**
- 3-phase timeline cards

**Arabic Copy**
- Headline: **تدرّج عملي من الأساس إلى الأتمتة المتقدمة**
- Phases:
  - **المرحلة 1 (الأساس):** رفع الملفات، OCR/Parsing، استخراج المتطلبات، مخرجات تمهيدية.
  - **المرحلة 2 (التخصص):** أوركسترا الوكلاء، المخرجات الفنية/المالية، تتبّع الاستشهادات.
  - **المرحلة 3 (التحسين):** كشف التعارضات المتقدم، تقارير تنفيذية ذكية، تكاملات مؤسسية.

**English Copy**
- Headline: **Structured progression from core value to advanced automation**
- Phases:
  - **Phase 1 (Foundation):** Upload, OCR/parsing, requirement extraction, core outputs.
  - **Phase 2 (Specialization):** Agent orchestration, technical/financial outputs, citation tracing.
  - **Phase 3 (Optimization):** Advanced conflict detection, executive analytics, enterprise integrations.

---

### 12) Testimonials / Proof Placeholder (AR / EN)
**Section Title (AR / EN):**
- العربية: **مؤشرات أثر وتجارب تشغيل**
- English: **Proof & Testimonial Placeholder**

**Objective**
- دعم المصداقية بدون ادعاءات غير موثقة أو شعارات عملاء غير مصرح بها.

**Key UI Components**
- Metrics cards
- Text testimonial placeholders

**Arabic Copy**
- Headline: **نتائج متوقعة قابلة للقياس ضمن بيئة تشغيل حقيقية**
- Bullets:
  - **خفض وقت إعداد المستندات بنسبة 60–80% (وفق حالة الاستخدام).**
  - **تقليل التعديلات المتأخرة قبل التسليم.**
  - **تحسين الاتساق بين المخرجات الفنية والإدارية.**
  - **صياغة محايدة للامتثال: “جاهز للتكيّف مع متطلبات الحوكمة الداخلية”.**

**English Copy**
- Headline: **Measurable outcomes, presented with compliance-safe wording**
- Bullets:
  - **60–80% reduction in document preparation cycle time (use-case dependent).**
  - **Fewer late-stage revisions before submission.**
  - **Higher consistency across technical and executive outputs.**
  - **Neutral wording: “Adaptable to internal governance requirements.”**

---

### 13) Final CTA + Lead Form (AR / EN)
**Section Title (AR / EN):**
- العربية: **ابدأ الآن**
- English: **Final Conversion Block**

**Objective**
- تحويل الزائر المهتم إلى فرصة مبيعات مؤهلة.

**Key UI Components**
- High-contrast CTA panel
- Demo request form
- Secondary contact options (email/phone placeholder)

**Arabic Copy**
- Headline: **جاهزون لعرض عملي على ملفاتكم الفعلية؟**
- Subheadline: **احجز جلسة تعريفية مخصصة لفريقك، أو ابدأ Pilot محدودًا لقياس الأثر خلال أسابيع.**
- CTA labels:
  - **اطلب عرضًا توضيحيًا**
  - **ابدأ Pilot الآن**

**English Copy**
- Headline: **Ready to see it on your real tender workflow?**
- Subheadline: **Book a tailored demo or launch a focused pilot to measure value within weeks.**
- CTA labels:
  - **Request Demo**
  - **Start Pilot Now**

**Interactions/States**
- Form states: default / validation error / submitting / success
- Success message:
  - AR: **تم استلام طلبكم بنجاح، وسيتواصل فريقنا معكم قريبًا.**
  - EN: **Your request has been received. Our team will contact you shortly.**

---

### 14) Footer (AR / EN)
**Section Title (AR / EN):**
- العربية: **تذييل الصفحة**
- English: **Enterprise Footer**

**Objective**
- توفير روابط سريعة ومحتوى قانوني احترافي.

**Key UI Components**
- Quick links
- Language switch duplicate
- Legal placeholders

**Arabic Copy**
- Links: **عن المنصة | الحلول | الأمان | طلب عرض | تواصل**
- Legal placeholders: **سياسة الخصوصية | الشروط والأحكام | إشعار قانوني**

**English Copy**
- Links: **About | Solutions | Security | Request Demo | Contact**
- Legal placeholders: **Privacy Policy | Terms of Use | Legal Notice**

---

## Design System Notes
- **Visual tone:** Enterprise SaaS, clean, low-noise, trust-first.
- **Color suggestions:**
  - Primary: Deep blue (#0F3D91)
  - Secondary: Teal accent (#0E7490)
  - Neutral background: #F8FAFC
  - Success: #059669 / Warning: #D97706 / Error: #DC2626
- **Typography:**
  - Arabic: IBM Plex Sans Arabic or Cairo (14–18 body, 28–44 heading)
  - English: Inter or Source Sans 3
- **Grid & spacing:** 12-column desktop grid, 8pt spacing system, section vertical padding 72–120px.
- **RTL/LTR rules:**
  - Mirror layout containers and icon directions.
  - Keep numerals and technical tokens LTR where needed.
  - Ensure bilingual line-height tuning for Arabic legibility.
- **Icon style:** outline enterprise icons, consistent 1.5–2px stroke.
- **Motion:** subtle 150–250ms transitions, no heavy parallax.
- **Accessibility:**
  - WCAG contrast targets (AA+)
  - Minimum body text 16px equivalent for Arabic readability
  - Keyboard navigable menus, accordions, form fields
  - ARIA labels for language switch and accordion controls

## Next.js Implementation Notes
- **Suggested structure (App Router):**
  - `app/[locale]/(marketing)/page.tsx`
  - `components/sections/*` (Hero, Workflow, Outputs, Agents, etc.)
  - `components/layout/Header.tsx`, `Footer.tsx`
  - `components/ui/*` for shared cards/buttons/badges
- **Routing:** locale segment (`/ar`, `/en`) with middleware locale detection.
- **i18n approach:**
  - Use dictionary JSON per locale (`content/ar.json`, `content/en.json`).
  - Keep section IDs synchronized between languages.
- **Content model (example fields):**
  - `sectionKey`, `headline`, `subheadline`, `bullets[]`, `ctaPrimary`, `ctaSecondary`
  - `agents[]` with `name`, `role`, `output`
  - `workflowStages[]` with `title`, `description`, `status`
- **State model for UX:**
  - `processingState`: idle | uploading | parsing | runningAgents | reviewReady
  - `confidenceScore`: number (0–100) + band label
  - `alerts[]`: missing requirement / conflict / export status
- **Performance notes:**
  - Lazy-load dashboard preview imagery and architecture diagram.
  - Use optimized SVG icons and Next/Image.
  - Defer non-critical animations.

## Lead Form Fields & Validation (AR/EN)
1. **الاسم الكامل / Full Name** — required, min 3 chars
2. **المسمى الوظيفي / Job Title** — required
3. **اسم الشركة / Company Name** — required
4. **البريد الإلكتروني للعمل / Work Email** — required, business email format
5. **رقم الجوال / Mobile Number** — required, Saudi format support
6. **حجم فريق المناقصات / Tender Team Size** — select (1–5, 6–15, 16+)
7. **نوع المشاريع / Project Type** — select (حكومي/خاص/مختلط)
8. **الرسالة / Notes** — optional, max 500 chars
9. **الموافقة على التواصل / Consent Checkbox** — required

**Validation & UX copy**
- AR error example: **يرجى إدخال بريد إلكتروني مهني صحيح.**
- EN error example: **Please enter a valid business email address.**

## UX Interaction States to Include
- Upload progress bar with file validation feedback.
- Processing state for OCR/parsing and agent run queue.
- Requirement gap alert card with severity tags.
- Conflict detection panel with side-by-side source references.
- Confidence score badges on generated sections.
- Export completion state (Word/PDF/Excel) with timestamp.

## Do/Don’t Checklist for Final QA
**Do**
- Verify complete RTL mirror behavior in Arabic layout.
- Keep Arabic copy first, then English, section by section.
- Repeat CTAs at Hero, mid-page, and final block.
- Use trust-forward language: assistive AI + human oversight.
- Keep claims measurable and neutral (no unverified certifications).
- Ensure keyboard and screen-reader support for toggles/accordions.
- Optimize image payload and lazy-load heavy mock visuals.

**Don’t**
- Don’t present AI as autonomous replacement for expert staff.
- Don’t use long text walls; keep scannable headings and bullets.
- Don’t invent client logos, certifications, or compliance badges.
- Don’t break bilingual consistency in terminology.
- Don’t rely on animation to explain core value.
