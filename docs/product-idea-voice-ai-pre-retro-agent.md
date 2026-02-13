# Retro Buddy — Voice AI Pre-Retro Agent

**Pomysł na Nową Aplikację Retrospektywną**

**Data utworzenia:** 2026-02-13
**Status:** Concept / Product Idea
**Źródło:** Sesja brainstormingowa z 6 lutego 2026

---

## 🎯 Elevator Pitch

**"Retro nie zaczyna się NA retro — zaczyna się PRZED."**

Retro Buddy to aplikacja, która prowadzi indywidualną rozmowę (głosową lub tekstową) z każdym uczestnikiem zespołu **24-48h przed retrospektywą**. AI dopytuje o sprint, emocje i wyzwania, a następnie automatycznie generuje przemyślane karteczki retro. Na spotkanie uczestnicy przychodzą przygotowani, karteczki już czekają na tablicy, a zespół od razu przechodzi do konstruktywnej dyskusji.

**Rezultat:** Retro krótsze o 30-40%, bardziej szczere, z lepszym zaangażowaniem intrów i ekstrawertów.

---

## ❗ Problem Który Rozwiązujemy

### Błędne Koło Martwego Retro

Zespoły Agile zmagają się z **5 kluczowymi problemami** retrospektyw:

| # | Problem | Symptomy |
|---|---------|----------|
| **#1** | **⏰ Czas** | Retro trwa za długo (1.5-2h), marnowanie czasu na "pisanie karteczek w ciszy" |
| **#2** | **😶 Cisza/Bierność** | Ludzie gapią się w sufit, czekają aż inni skończą, brak zaangażowania |
| **#4** | **🤐 Brak szczerości** | Ludzie nie mówią prawdy przy całej grupie — strach przed konsekwencjami |
| **#3** | **📋 Akcje giną** | Brak realizacji action items między retrospektywami |
| **#5** | **🔄 Powtarzalność** | Te same tematy wracają sprint po sprincie, zero postępu |

**Błędne koło:**
Brak szczerości → słabe tematy → brak wartościowych akcji → akcje giną → ludzie widzą że retro nic nie daje → mniej zaangażowania → więcej ciszy → **cykl się powtarza**

### Psychologiczne Bariery (Większe Niż Techniczne)

- **Bariera "pustej kartki"** — najtrudniejsza część to ROZPOCZĘCIE myślenia przy grupie
- **Presja społeczna** — introwertcy potrzebują czasu, ekstrawertcy zdominują
- **Brak bezpieczeństwa** — łatwiej powiedzieć AI niż managerowi

---

## 💡 Nasza Innowacja: Voice AI Pre-Retro Agent

### Kluczowa Zmiana Paradygmatu

**PRZESUNIĘCIE:** Przygotowanie do retro z **synchronicznego** (wszyscy razem, cisza, presja) na **asynchroniczne, indywidualne, bezpieczne** (każdy z AI, w swoim czasie, w swoim stylu).

---

## 🛠️ Jak To Działa

### 📅 Timeline: 48h Przed Retro → Retro

#### **Krok 1: Przypomnienie (48h przed)**
- ✉️ SMS/Email/Slack: *"Hej! Retro za 2 dni. Masz 10-15 min na rozmowę z Retro Buddy?"*
- 🔗 Link aktywny przez 48h

#### **Krok 2: Rozmowa z AI (24-48h przed)**

**User wybiera format:**
- 🎙️ **Voice call** — idealne na spacer/drogę do pracy
- ✍️ **Text chat** — dla osób preferujących pisanie
- 🚗 **"Drive mode"** — hands-free w samochodzie

**AI prowadzi rozmowę (10-15 min):**
- Customizable style: bezpośredni/empatyczny/zwięzły/żartobliwy
- Język: polski/angielski/mixed
- **Przykładowe pytania:**
  - "Cześć! Jak minął ten sprint?"
  - "Co działało dobrze?"
  - "Co Cię frustrowało?"
  - "Czy było coś, o czym chcesz porozmawiać na retro?"

**AI dopytuje i drąży głębiej:**
- Rozpoznaje emocje z głosu/tekstu
- **AI Coach w real-time:** Jeśli user mówi destruktywnie (*"Kowalski zepsuł deploy"*), AI podpowiada:
  *"Rozumiem frustrację. Może spróbujmy to ująć bardziej systemowo — co w procesie deployment nie zadziałało?"*

**Po rozmowie:**
- 🔒 Transkrypcja zapisana **ENCRYPTED** — widoczna **TYLKO dla użytkownika**
- 🤖 AI przetwarza w tle i generuje karteczki

#### **Krok 3: Review & Edit (12-24h przed)**

**AI generuje 3-5 karteczek** i wysyła do użytkownika

**🔑 KLUCZOWY KROK — User ma pełną kontrolę:**
- ✅ **Zaakceptować** — "Tak, to dobrze oddaje co chciałem"
- 🔄 **Edytować** — zmienia treść, AI pomaga przeformułować
- 💡 **Poprosić o alternatywy** — "Pokaż 3 inne sposoby sformułowania"
- ❌ **Usunąć** — karteczka nigdy nie trafi na retro
- ➕ **Dodać własne** — napisać dodatkowe ręcznie

**Preview dla Scrum Mastera (anonimowy):**
- SM widzi **tylko tematy** (nie szczegóły, nie autorów):
  *"Na retro będą tematy: deployment, komunikacja, testing, sprint planning"*
- Pomaga SM przygotować się do facylitacji

#### **Krok 4: Retro**

- 📋 **Karteczki już czekają** na tablicy Miro/FigJam
- ➕ **Opcja live add** — ludzie mogą dodać nowe (optional)
- 🏃 **Retro startuje OD RAZU od dyskusji**, nie od "pisania w ciszy"

---

## 🔒 Privacy & Security — Priorytet #1

### Dlaczego To Jest Krytyczne?

User Persona Focus Group wykazał: **bez gwarancji prywatności ficzer zginie**.
*"Kto widzi moje dane?"* to pytanie #1 każdego uczestnika.

### 5 Zasad Prywatności (Transparentne, Jawne)

#### 1. Transkrypcja Rozmowy
- Dostępna **TYLKO dla użytkownika**
- SM/Manager/PO **NIE widzą** transkrypcji
- Encrypted at rest i in transit

#### 2. Wygenerowane Karteczki
- Widoczne dla zespołu **PO zaakceptowaniu** przez usera
- SM widzi finalne karteczki (jak zawsze na retro)
- SM **NIE widzi odrzuconych/usuniętych** karteczek

#### 3. Retention (Przechowywanie)
- Domyślnie: **30 dni**, potem auto-delete
- User może wybrać krótszy okres (**7 dni, 1 dzień**)
- **Full delete option**: w każdej chwili można usunąć wszystko

#### 4. Wykorzystanie Danych
- Dane **NIE mogą być użyte do performance reviews**
- Dane **NIE są udostępniane** poza zespołem retro
- AI uczy się tylko na **zagregowanych, anonimowych** wzorcach (opt-in)

#### 5. Transparency
- Przed pierwszą rozmową: user akceptuje **Privacy Policy** (jasny język)
- W aplikacji: widoczny status *"Kto ma dostęp do moich danych"*

---

## ✅ Co To Rozwiązuje?

| Problem | Jak Voice AI Pre-Retro Agent Rozwiązuje | Impact |
|---------|------------------------------------------|--------|
| **#2: Cisza/Bierność** | Ludzie przychodzą z **gotowymi karteczkami** → łatwiej zacząć rozmawiać | ⭐⭐⭐ |
| **#4: Brak szczerości** | Rozmowa **1:1 z AI** = bezpieczniejsza niż przy grupie | ⭐⭐⭐ |
| **#1: Czas — za długie** | Przygotowanie **async** → **-30-40% czasu** retro | ⭐⭐⭐ |
| **#5: Powtarzalność** | AI **pamięta poprzednie rozmowy**: *"Ostatnio mówiłeś o X, jak teraz?"* | ⭐⭐ |
| **#3: Akcje giną** | AI może **przypomnieć o akcjach** podczas rozmowy | ⭐⭐ |

---

## 🚀 Dlaczego To Jest Game-Changer?

### 1️⃣ Przełom Psychologiczny

- **Usuwa barierę "pustej kartki"** — najtrudniejsza część (rozpoczęcie myślenia) jest async i 1:1
- **Bezpieczeństwo psychologiczne** — łatwiej powiedzieć prawdę AI niż przy grupie
- **Demokratyzacja głosu** — introwertcy mają tyle samo czasu co ekstrawertcy
- **AI jako "konstruktywny translator"** — pomaga przeformułować frustrację na actionable feedback

### 2️⃣ Przełom Czasowy

- Retro **o 30-40% krótsze** bo pomijamy fazę "zbierania karteczek w ciszy"
- Więcej czasu na **dyskusję i akcje**, mniej na "what happened"
- SM może się **przygotować do facylitacji** widząc preview tematów

### 3️⃣ Przełom w Adopcji

- **User control na każdym etapie** — review, edit, delete
- **Flexibility** — voice OR text, różne style AI
- **Privacy by design** — adresuje główną obawę (surveillance)

---

## 🎭 Insights z User Persona Focus Group

### Uczestnicy

- **Kasia** (Junior Scrum Master) — entuzjastyczna
- **Marcin** (Senior Developer, introwertyk) — ostrożnie zainteresowany
- **Ania** (Product Owner, ekstrawertyk) — praktyczne pytania
- **Tomek** (Tester, sceptyk) — krytyczne myślenie o prywatności
- **Magda** (Experienced SM) — mądra ostrożność

### ✅ CO ZESPÓŁ KOCHA

1. **Async preparation** — koniec z ciszą na początku retro
2. **Bezpieczeństwo 1:1** — łatwiej powiedzieć prawdę AI
3. **Pomoc w formułowaniu** — AI pomaga ująć myśli
4. **Skrócenie retro** — więcej czasu na akcje

### ⚠️ TOP OBAWY (Addressed w Designie)

| Obawa | Mitigation | Priorytet |
|-------|------------|-----------|
| **Prywatność danych** | Encryption, RBAC, jasna policy | 🔴 CRITICAL |
| **AI źle interpretuje** | Review & Edit step (MUST-HAVE) | 🔴 CRITICAL |
| **Brak kontroli** | Full edit/delete capability | 🔴 CRITICAL |
| **Niska adopcja** | Reminder system, pokazanie wartości | 🟡 HIGH |
| **Za nachalny AI** | Customizable style | 🟡 HIGH |
| **Accessibility** | Choice: voice OR text | 🟢 MEDIUM |

### 💡 Nowe Feature Requests (z Focus Group)

1. **Review & Edit Step** — PRZED retro: edit/delete karteczek
2. **Choice: Voice OR Text** — nie każdy lubi mówić
3. **Privacy Controls** — jasna polityka + full delete
4. **AI Coach w formułowaniu** — podpowiada konstruktywne przeformułowania
5. **Temat Preview dla SM** — anonimowy podgląd tematów
6. **Reminder System** — przypomnienie 24h przed
7. **"Drive mode"** — hands-free w samochodzie

---

## 🛠️ Technical Requirements (High-Level)

### Komponenty Systemu

#### 1. Voice/Text Interface
- **Voice:** OpenAI Realtime API / ElevenLabs
- **Text:** Standard chat interface
- **Multi-language:** PL/EN

#### 2. AI Conversation Engine
- **LLM:** GPT-4/Claude z custom prompt
- **Contextual memory** — pamięta poprzednie rozmowy
- **Sentiment analysis**
- **Constructive reframing engine**

#### 3. Storage & Security
- **Encrypted database**
- **RBAC** (Role-Based Access Control)
- **Auto-deletion policies**
- **GDPR compliance**

#### 4. Integration Layer
- **Notifications:** email/Slack/SMS
- **Miro/FigJam API**
- **Jira/Azure DevOps** (optional)

#### 5. Review Interface
- **User dashboard**
- **Edit/delete controls**
- **Alternative suggestions generator**

---

## 📊 Success Metrics — Jak Mierzymy Sukces?

### Adoption Metrics
- **Completion rate:** >70% zespołu robi rozmowę
- **Format preference:** Voice vs Text usage
- **Review engagement:** % userów edytujących karteczki

### Quality Metrics
- **Retro duration:** -30% czasu
- **Karteczki na osobę:** +50%
- **Delete rate:** <20% (dobra jakość AI)

### Impact Metrics
- **Team satisfaction (NPS):** +20 punktów
- **Participation (ciche osoby):** +40%
- **Szczerość survey:** >80% "czuję się bezpiecznie"

### Trust Metrics
- **Privacy confidence:** >90%
- **AI accuracy:** >85% "AI dobrze oddało co chciałem"

---

## 🚨 Ryzyka i Mitigation

| Ryzyko | Mitigation Strategy | Owner |
|--------|---------------------|-------|
| **Niska adopcja** | Reminder system + SM encouragement + ROI visibility | Product + SM |
| **Breach prywatności** | Encryption + RBAC + audits | Security Team |
| **AI źle interpretuje** | Review step (MUST-HAVE) + alternatives | AI Team |
| **Brak zaufania** | Transparency + pilot z willing teams | Product + SM |
| **Problemy techniczne** | Fallback: tradycyjne retro | DevOps |

---

## 🎯 Implementation Roadmap

### Phase 1: MVP (3-4 miesiące)

**Scope:** Text-only, basic features, 1 pilot team

**Features:**
- Text chat interface (bez voice)
- Basic conversation flow (5 pytań)
- Generowanie karteczek
- Review & edit step
- Manual integration z Miro (copy-paste)
- Basic encryption

**Success criteria:** 1 zespół używa przez 3 retro, >70% completion rate

---

### Phase 2: Enhanced (2-3 miesiące)

**Scope:** Voice, customization, privacy features

**Features:**
- Voice call option (OpenAI Realtime API)
- Customizable AI style
- Privacy controls (delete, retention settings)
- Auto-integration z Miro API
- Reminder system
- Preview dla SM (anonymous topics)

**Success criteria:** 5 zespołów, NPS >50

---

### Phase 3: Advanced (3-4 miesiące)

**Scope:** AI learning, cross-retro memory, analytics

**Features:**
- AI pamięta poprzednie rozmowy
- Constructive reframing w real-time
- ROI dashboard (pokazuje wartość retro)
- Multi-language support
- Integration z Jira (action items)

**Success criteria:** 20+ zespołów, NPS >70, retro 30% krótsze

---

## 🎨 Key User Stories

**US1:** Jako uczestnik retro chcę dostać przypomnienie 48h przed retro aby nie zapomnieć o rozmowie z AI
**AC:** Email/Slack z linkiem, możliwość snooze na 12h

**US2:** Jako introwertyk chcę mieć rozmowę 1:1 z AI w formie text chat aby czuć się komfortowo
**AC:** Wybór text/voice na początku, możliwość zmiany w trakcie

**US3:** Jako user chcę edytować wygenerowane karteczki PRZED retro aby mieć kontrolę nad tym co idzie na tablicę
**AC:** Dashboard z karteczkami, przyciski edit/delete/accept, AI sugeruje alternatywy

**US4:** Jako sceptyk chcę wiedzieć kto ma dostęp do mojej transkrypcji aby ufać systemowi
**AC:** Strona "Privacy" pokazuje: "Tylko Ty widzisz transkrypcję. Manager/SM NIE mają dostępu"

**US5:** Jako SM chcę zobaczyć (anonimowo) jakie tematy będą na retro aby przygotować facylitację
**AC:** Dashboard SM: "Tematy na następne retro: deployment (4 karteczki), komunikacja (3), testing (2)"

**US6:** Jako user chcę usunąć całą moją rozmowę jeśli zmienię zdanie aby czuć bezpieczeństwo
**AC:** Przycisk "Delete all" → transkrypcja + karteczki usunięte, nie można odzyskać

---

## ❌ Jak NIE Powinno To Działać — Anti-Patterns

### 🚫 Czego UNIKAĆ

1. **AI narzuca karteczki bez review** → MUSI być Review & Edit step
2. **Manager/SM widzi transkrypcje** → Tylko user ma dostęp
3. **Brak opcji usunięcia** → Full delete w każdej chwili
4. **Only voice** → Musi być text option dla accessibility
5. **Agresywny AI** → Customizable style, możliwość wyłączenia
6. **Brak przypomnienia** → Reminder system obowiązkowy
7. **Używanie danych do performance reviews** → Jawny zakaz w Privacy Policy
8. **AI uczy się na danych bez zgody** → Opt-in, agregowane, anonimowe
9. **Karteczki trafiają na retro automatycznie** → User MUSI zaakceptować
10. **Brak fallback na tradycyjne retro** → Jeśli AI nie działa, zespół może retro normalnie

---

## 🌟 Co Jest NAJWAŻNIEJSZE?

### TOP 3 Must-Have Features (Bez Tego Ficzer Zginie)

#### 1️⃣ **Review & Edit Step**
- User MUSI mieć kontrolę nad karteczkami PRZED retro
- Możliwość edit/delete/accept/add own
- AI sugeruje alternatywy ale nie narzuca

**Dlaczego krytyczne:**
*"Jeśli AI źle zinterpretuje co powiedziałem i wygeneruje destruktywną karteczkę, retro może wybuchnąć. Ludzie powiedzą 'ja tego tak nie miałem na myśli!' i zaufanie spadnie."* — Magda (Experienced SM)

#### 2️⃣ **Privacy by Design**
- Transkrypcja TYLKO dla użytkownika
- Encryption
- RBAC — jasno określone kto co widzi
- Full delete option
- Jawna polityka: dane NIE do performance reviews

**Dlaczego krytyczne:**
*"Czy AI może być użyte PRZECIWKO mnie? Czy manager czyta że narzekałem na procesy?"* — Tomek (Tester, sceptyk)

#### 3️⃣ **User Control & Flexibility**
- Choice: Voice OR Text
- Customizable AI style
- Możliwość wyłączenia/pominięcia rozmowy
- Opcja tradycyjnego retro bez AI

**Dlaczego krytyczne:**
*"Nie każdy lubi mówić. Ja potrzebuję czasu żeby sformułować myśli pisząc."* — Marcin (Senior Developer, introwertyk)

---

## 🎁 Dodatkowe Ficzery (Nice-to-Have, Nie MVP)

- **"Drive mode"** — hands-free w samochodzie
- **Multi-language** (PL/EN/DE/ES)
- **Cross-retro memory** — AI pamięta poprzednie rozmowy
- **ROI Dashboard** — pokazuje wartość retro w czasie
- **Jira integration** — action items automatycznie jako stories
- **Sentiment analysis w real-time** — wykrywa frustrację i reaguje
- **Team analytics** — agregowane insights dla SM (anonimowe)

---

## 💼 Business Model (Wstępny)

### Target Market
- **Primary:** Scrum Masterzy, Agile Coaches, zespoły 5-15 osób
- **Secondary:** Product Owners, Team Leads, HR (employee engagement)
- **Geography:** Global (focus: US, EU, PL)

### Pricing (Concept)
- **Free tier:** 1 zespół, 3 retro/miesiąc, text-only
- **Pro:** $49/miesięcznie — unlimited retro, voice, 1 zespół
- **Team:** $199/miesięcznie — 5 zespołów, analytics, integrations
- **Enterprise:** Custom — unlimited teams, SSO, dedicated support

### Revenue Model
- **SaaS subscription** (monthly/yearly)
- **Add-ons:** Premium voice (better quality), extra languages, white-label

---

## 🔮 Wizja Długoterminowa

**Retro Buddy** to nie tylko ficzer — to **zmiana paradygmatu** jak robimy retrospektywy.

**Wizja:** Każda retrospektywa na świecie zaczyna się asynchronicznie, indywidualnie, bezpiecznie — dzięki AI.

**Impact:** Miliony godzin zaoszczędzone, setki tysięcy zespołów bardziej szczerych i zaangażowanych.

**Motto:** *"Retro nie zaczyna się NA retro — zaczyna się PRZED."*

---

## 📚 Źródła i Powiązane Dokumenty

- [brainstorming-session-2026-02-06.md](../_bmad-output/brainstorming/brainstorming-session-2026-02-06.md) — Pełna sesja brainstormingowa
- [brainstorming-session-2026-01-30.md](../_bmad-output/brainstorming/brainstorming-session-2026-01-30.md) — Sesja 1: Identyfikacja problemów

---

**Dokument utworzony:** 2026-02-13
**Wersja:** 1.0
**Autor:** Zespół brainstormingowy (4 osoby) + AI Facilitator
**Metodyka:** BMad Brainstorming Workflow v6.0.0-Beta.7 + Advanced Elicitation (User Persona Focus Group)
