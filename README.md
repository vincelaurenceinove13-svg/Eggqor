🥚 EGGQOR — Japanese-Style Egg Sandwich Website

卵サンド · Laguna · Est. 2026

A modern, Japanese-style product landing page for EGGQOR, an egg sandwich brand created by students of the IQOR section at Biñan Integrated National High School. Built as a single HTML file — no frameworks, no dependencies, no build tools needed.

🏫 Origin Story
In 2025, Cassandra Cruda, Lyra De Castro, Nassleah Ismael, Vince Inovejas, and James Jordan, along with their IQOR classmates, gathered to brainstorm a product to sell and a brand name to go with it.
They landed on EGGQOR — split into two parts:

"Egg" → the egg sandwich product
"Qor" → IQOR, the name of their section

They spent a day testing 15 bread recipes, sourcing eggs from the local market, and calibrating boiling times to the second. EGGQOR opened in 2026 from a small corner of the gymnasium court at their school — no reservations, just one item on the menu, made with care.

"The most meaningful things are simple ones, made with care."
— Eggcor Team


📁 Project Files
eggqor/
├── eggqor.html      # The entire website — HTML, CSS, and JS all in one file
└── Eggcor.png       # Logo used as the browser favicon

🗂️ Page Sections
SectionNav IDDescriptionNavigation—Fixed top bar with EGGQOR logo, Japanese tagline, and anchor linksHero—Split layout with animated SVG sandwich and Order Now / View Menu CTAsIngredients#ingredients4-column grid listing all 10 ingredients with Japanese namesOur Craft#craftDark section with 3-step process and team quoteMenu#menu / #order3 available sandos + 2 coming soon cardsAbout Us#aboutIllustrated shop scene, brand story, stats, and core valuesFooter—Store location, hours, phone number, and social links

🥪 Menu
Available Now
NameJapanesePriceOriginal Tamagoオリジナルたまご₱25Tamago & Greensたまごと野菜₱30Overload Tamagoオーバーロードたまご₱40
Coming Soon
NameJapaneseTypeSomething New新しいメニューNew MenuSeasonal Drop季節のサンドLimited Edition

The coming soon cards include a "Notify Me" button that shows a confirmation message when clicked.


🧂 The 10 Ingredients
#IngredientJapanese01Toasted Buttered Breadトーストしたバター付きパン02Tamago Eggたまご03Kewpie Mayoマヨネーズ04Parsleyパセリ05Black Pepper Powder黒コショウパウダー06Lettuceレタス07Tomatoトマト08Cheeseチーズ09Mustardマスタード10Cucumberキュウリ

👨‍🍳 The Craft — 3-Step Process
Step漢字DescriptionThe Bread一Toasted in butter and margarine for unmatched softnessThe Egg二Soft-boiled for exactly 7 minutes, ice-bathed, folded with Kewpie mayoThe Assembly三Crusts removed, cut diagonally, wrapped in washi paper, served immediately

📊 Brand Stats
StatValueRecipes tested15+Perfect boil time7 minutesSandwiches served∞

💛 Core Values
一 — Freshness Above All
Every ingredient arrives the morning it is used. Butter bread baked at 7am. Eggs delivered by 6am. Doors open at 10am.
二 — No Shortcuts, Ever
Every egg peeled by hand. Never pre-made. When they run out, they close.
三 — Rooted in Tradition
Inspired by Japanese kissaten culture — the neighborhood café where simplicity and craftsmanship share a table.

👥 The Team
NameRoleCassandra CrudaFounder & Head ChefLyra De CastroCo-founderNassleah IsmaelCo-founderVince InovejasCo-founderJames JordanCo-founderIQOR SectionStudent collaborators

🎨 Design System
Fonts
RoleFontDisplay / HeadingsShippori Mincho (weights 400–800)Body / UIZen Kaku Gothic New (weights 300–500)SecondaryDM Sans (light & regular)
Color Palette
CSS VariableHexUsed For--cream#f5f0e8Page background--warm-white#faf8f3Cards, sections--ink#1a1612Primary text, dark areas--charcoal#2d2926Body text--gold#c9a84cAccents, labels, prices--gold-light#e8d5a3Bread fills, watermarks--rust#b85c38Warm accent (reserved)--moss#5c6b4aSuccess / confirmed state--mist#d4cfc5Muted text, borders

✨ Visual Features

Custom animated cursor — gold dot + trailing ring using requestAnimationFrame
Floating SVG sandwich — hand-drawn hero illustration with looping float + rotate animation
Vertical kana watermark — たまご written in writing-mode: vertical-rl on the hero
Grain texture overlay — SVG feTurbulence noise filter for a premium printed feel
Scroll-reveal animations — fade-up on scroll via IntersectionObserver
Illustrated About scene — custom SVG of a chef holding a sandwich behind a noren curtain
Add to cart feedback — + button turns green with a ✓ checkmark for 1.2 seconds
Notify Me button — confirms with Japanese thank-you text (ありがとう)


📍 Store Info
LocationBiñan, LagunaHoursMonday – Saturday, 10am – 5pmAvailabilityUntil sold outPhone+63 9379-164-1008

🚀 How to Run
No installation needed. Just open the file:
bash# Open directly in your browser
open eggqor.html

# Or serve locally with Python
python3 -m http.server 8000
# then visit http://localhost:8000/eggqor.html

Make sure Eggcor.png is in the same folder as eggqor.html for the favicon to load.


🛠️ Common Edits
Change a price — Search for ₱ and update the number inside .menu-card-price.
Add a menu item — Duplicate any .menu-card block inside .menu-grid and update the tag, name, Japanese text, description, price, and SVG.
Update store hours or contact — Edit the <ul> list under the Visit column in <footer>.
Change the team or story — Edit the <strong> names and <p> paragraphs inside .about-body.

📱 Responsive Layout
ScreenBehavior> 1024px2-column hero, 3-column menu grid, side-by-side process and about sections≤ 1024pxSingle-column stacked layout, nav links hidden, reduced padding

🌐 Browser Notes
The custom cursor, backdrop-filter blur, and mix-blend-mode effects work best in Chromium-based browsers (Chrome, Edge, Brave) and Safari.

© 2026 EGGQOR · Biñan Integrated National High School · IQOR Section
手作り · 毎朝新鮮 · たまごサンド
Handmade · Fresh Every Morning · Egg Sandwich
