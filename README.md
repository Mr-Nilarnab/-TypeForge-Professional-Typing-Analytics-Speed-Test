
<h1>⚡ TypeForge</h1>
Professional Typing Analytics & Speed Test Engine

TypeForge is a zero-dependency, offline-first, production-grade typing analytics engine designed for high-performance front-end portfolios and serious engineering demonstrations.

Built using pure HTML, CSS, and Vanilla JavaScript, TypeForge delivers real-time diagnostics, hardened anti-cheat protection, and precision typing metrics—all inside a single standalone file.

No frameworks. No APIs. No build tools.
Just clean, deterministic engineering.

<h1>🖥️ Interface Preview</h1>

<h2>🌙 Dark Mode</h2>
<img width="1919" height="1004" alt="Dark Mode" src="https://github.com/user-attachments/assets/af152aca-452f-43b3-9372-b2d1dd21d571" />

<h2>☀️ Light Mode</h2>
<img width="1918" height="981" alt="Light Mode" src="https://github.com/user-attachments/assets/24550e9a-fca1-421d-a477-b4bebaaf355f" />

<h2>📊 Results & Analytics</h2>
<img width="1919" height="984" alt="Results" src="https://github.com/user-attachments/assets/153c8392-3f6e-496e-938e-ed2946f8ed94" />


🚀 Core Capabilities

🧠 Typing Engine (Low-Latency Core)
Atomic Real-Time Detection
Character-by-character validation using indexed string matrices and deterministic evaluation loops.
Visual Caret Intelligence

✅ Correct input → Green highlight

❌ Incorrect input → Red feedback with soft alert
⌖ Active index → Animated caret underline
Anti-Abuse & Cheat Shielding
Clipboard blocking (Copy / Paste / Select All)
Context menu isolation
Programmatic input bypass prevention

📊 Advanced Typing Analytics
True Net WPM
(Total Characters ÷ 5) ÷ Time (minutes)
Gross CPM
Absolute keystroke throughput measurement.
Live Accuracy Rating
Real-time precision calculation against active error count.
Extended Diagnostics
Error tracking
Backspace behavior logging
Retroactive correction detection

🎨 Premium UI / UX Architecture
Adaptive Theme Engine

☀️ Light Mode & 🌙 Dark Mode
Persisted using localStorage
Instant toggle with zero reload cost
Fluid Motion System
Sub-second easing curves
Soft elevation cards
Linear gradient accent layers
Telemetry Virtual Keyboard

Real-time key-press visualization mapped directly to user input.
🛠️ Engineering Architecture
1️⃣ Zero-Asset Audio System (Web Audio API)

No external sound files. No base64 bloat.

Audio feedback is generated dynamically using native Web Audio API oscillators:

✅ Correct Keystroke
High-frequency sine wave with short envelope
❌ Incorrect Keystroke
Low-frequency triangle wave with dampened decay

This ensures instant playback, zero asset loading, and full offline compatibility.

2️⃣ High-Density DOM Delta Diffing
Test text is pre-split into immutable .char-span nodes
During input:
Only targeted class tokens are mutated
No container rewrites
No layout thrashing

Result: Smooth 60 FPS performance, even on low-power devices.

3️⃣ Isolated State Engine

All runtime logic is encapsulated inside a single structured JavaScript closure:

Timers
Metrics
Error counters
User preferences
Configuration switches

This creates a single source of truth and guarantees predictable UI behavior.

⚙️ Configuration Options
Feature	Type	Available Options
Difficulty Level	String Segment	Easy / Medium / Hard
Time Limit	Integer	30s / 60s / 120s
Audio Feedback	Boolean	On / Muted
Persistence Cache	Local Storage	Automatic analytics storage

💻 Installation & Offline Deployment

TypeForge is fully offline-ready. No setup required.

Clone the Repository
git clone https://github.com/Mr-Nilarnab/-TypeForge-Professional-Typing-Analytics-Speed-Test.git
Run Instantly
Locate index.html
Double-click the file
Open in any modern browser
(Chrome, Edge, Firefox, Safari)

✅ No internet
✅ No local server
✅ No compilation

📜 Credits

Lead Core Engineer & UI/UX Architect
Mr-Nilarnab

All system architecture, typing logic, analytics formulas, Web Audio synthesis, DOM optimization strategies, and UI design were engineered independently.

🔗 Repository

TypeForge – Professional Typing Analytics & Speed Test
