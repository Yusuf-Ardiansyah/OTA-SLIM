<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=36&duration=2800&pause=800&color=39FF14&center=true&vCenter=true&width=800&lines=Y-TUBE+SLIM+ARCHITECTURE;SULTAN+DARK+NEUMORPHISM+3D+ENGINE;ZERO+ADS+%E2%80%A2+BACKGROUND+AUDIO+%E2%80%A2+R8+HARDENED;ENGINEERED+BY+Y-ARDIANSYAH" alt="Y-TUBE SLIM Header" />

<br/>

<img src="youtube.png" alt="Y-TUBE SLIM Logo" width="130" />

# 👑 Y-TUBE SLIM EDITION 👑
**Next-Gen Ultra-Lightweight Native Android YouTube Client**  
`[ High Speed Engine ]` ──🔗── `[ Zero Ads Script ]` ──🔗── `[ R8 Demon & Ghost Security ]`

<p align="center">
  <img src="https://img.shields.io/badge/ARCHITECT-Y--ARDIANSYAH-FFD700?style=for-the-badge&logo=github&logoColor=090A0E&labelColor=1A1D24" />
  <img src="https://img.shields.io/badge/CORE-Kotlin_%2B_Java_JNI-39FF14?style=for-the-badge&logo=kotlin&logoColor=090A0E&labelColor=1A1D24" />
  <img src="https://img.shields.io/badge/UI-Jetpack_Compose_3D-00FF66?style=for-the-badge&logo=android&logoColor=090A0E&labelColor=1A1D24" />
  <img src="https://img.shields.io/badge/SHIELD-R8_Demon_%26_Ghost-FF0055?style=for-the-badge&logo=shield&logoColor=white&labelColor=1A1D24" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/repo-size/Yusuf-Ardiansyah/Y-TUBE-SLIM?style=flat-square&color=39FF14&labelColor=090A0E&label=REPO%20SIZE" />
  <img src="https://img.shields.io/github/last-commit/Yusuf-Ardiansyah/Y-TUBE-SLIM?style=flat-square&color=FFD700&labelColor=090A0E&label=LAST%20UPDATE" />
  <img src="https://img.shields.io/badge/THEME-Sultan_Dark_%23090A0E-D4AF37?style=flat-square&labelColor=090A0E" />
  <img src="https://img.shields.io/badge/TARGET-Android_Native_Slim-10B981?style=flat-square&labelColor=090A0E" />
</p>

</div>

---

## ⛓️ Interactive System Chain Architecture (Mermaid Graph)

Diagram rantai interaktif di bawah ini memetakan alur eksekusi data dari **Application Boot**, **Security Layer**, **Jetpack Compose UI**, hingga **Background Media Engine**:

```mermaid
flowchart TD
    classDef core fill:#090A0E,stroke:#FFD700,stroke-width:2px,color:#FFD700,font-weight:bold
    classDef ui fill:#1A1D24,stroke:#39FF14,stroke-width:2px,color:#39FF14,font-weight:bold
    classDef bridge fill:#090A0E,stroke:#00FF66,stroke-width:2px,color:#FFFFFF
    classDef service fill:#1A1D24,stroke:#FF0055,stroke-width:2px,color:#FFDF00,font-weight:bold

    subgraph BOOT ["🔒 1. CORE BOOT & SECURITY SHIELD"]
        A["🚀 CoreApp.kt<br/>(Application Init)"]:::core --> B["🛡️ CoreSystem.java<br/>(System Integrity Verification)"]:::core
        B --> C["⚙️ JniConfigState.java<br/>(Native JNI Config & Guard)"]:::core
    end

    subgraph UI_LAYER ["🎨 2. SULTAN DARK UI & COMPOSE LAYER"]
        C --> D["📱 MainActivity.kt<br/>(Entry Activity & Lifecycle)"]:::ui
        D --> E["🎬 Youtube.kt<br/>(Main Player Screen)"]:::ui
        E <--> F["🖼️ MiniPlayer.kt<br/>(Floating PiP / Multitask UI)"]:::ui
        E --- G["✨ Logo.kt + Theme.kt<br/>(Sultan Dark #090A0E & Neon #39FF14)"]:::ui
    end

    subgraph ENGINE_LAYER ["⚡ 3. INTERCEPTOR & JS-NATIVE BRIDGE"]
        E --> H["👆 TouchInterceptor.kt<br/>(Custom Swipe & Gesture Engine)"]:::bridge
        E --> I["💉 WebScripts.kt<br/>(Sultan AdBlocker & Sponsor Skip)"]:::bridge
        I <--> J["🔗 JsInterface.kt<br/>(2-Way JS-to-Kotlin Bridge)"]:::bridge
        J <--> K["🧠 PlayerViewModel.java<br/>(Reactive Playback State)"]:::bridge
    end

    subgraph AUDIO_LAYER ["🎧 4. BACKGROUND MEDIA ENGINE"]
        J --> L["🎵 AudioService.kt<br/>(Foreground MediaSession & Lockscreen Audio)"]:::service
        K --> L
    end
```

---

## 🧱 High-Level Block & Chain Pipeline

```	ext
╔══════════════════════════════════════════════════════════════════════════════════════╗
║                          Y-TUBE SLIM EXECUTION PIPELINE                              ║
╠══════════════════════════════════════════════════════════════════════════════════════╣
║                                                                                      ║
║  ┌──────────────────────┐      ┌──────────────────────┐      ┌────────────────────┐  ║
║  │     CoreApp.kt       │ ───► │   CoreSystem.java    │ ───► │ JniConfigState.java│  ║
║  │  [App Bootstrapper]  │      │  [Anti-Tamper Core]  │      │  [JNI State Guard] │  ║
║  └──────────┬───────────┘      └──────────────────────┘      └─────────┬──────────┘  ║
║             │                                                          │             ║
║             ▼                                                          ▼             ║
║  ┌────────────────────────────────────────────────────────────────────────────────┐  ║
║  │                           MainActivity.kt & Youtube.kt                         │  ║
║  │              [Jetpack Compose UI Host • Sultan Dark Theme #090A0E]             │  ║
║  └──────────┬─────────────────────────────┬────────────────────────────┬──────────┘  ║
║             │                             │                            │             ║
║             ▼                             ▼                            ▼             ║
║  ┌──────────────────────┐      ┌──────────────────────┐      ┌────────────────────┐  ║
║  │ TouchInterceptor.kt  │      │    WebScripts.kt     │      │   MiniPlayer.kt    │  ║
║  │ [Gesture & Touch UI] │      │ [Sultan AdBlock DOM] │      │ [Floating Overlay] │  ║
║  └──────────┬───────────┘      └──────────┬───────────┘      └─────────┬──────────┘  ║
║             │                             │                            │             ║
║             └──────────────────┐          ▼          ┌─────────────────┘             ║
║                                │   ┌──────────────┐  │                               ║
║                                └──►│JsInterface.kt│◄─┘                               ║
║                                    │[Native Bridge]│                                 ║
║                                    └──────┬───────┘                                  ║
║                                           │                                          ║
║                        ┌──────────────────┴──────────────────┐                       ║
║                        ▼                                     ▼                       ║
║             ┌──────────────────────┐              ┌────────────────────┐             ║
║             │ PlayerViewModel.java │ ◄──────────► │  AudioService.kt   │             ║
║             │ [Playback State Hub] │              │ [Background Audio] │             ║
║             └──────────────────────┘              └────────────────────┘             ║
║                                                                                      ║
╠══════════════════════════════════════════════════════════════════════════════════════╣
║    BINARY PROTECTION : R8 Full Mode + Custom Obfuscation (demon.txt & ghost.txt)     ║
╚══════════════════════════════════════════════════════════════════════════════════════╝
```

---

## 📂 Complete Repository Structure Tree

```	ext
📦 Y-TUBE-SLIM (Root Project)
 ┣━━ 📄 .gitignore                        # Security Filter (Blocks .jks, .cxx, build/)
 ┣━━ 📄 build.gradle.kts                  # Root Gradle Configuration
 ┣━━ 📄 settings.gradle.kts               # Module & Dependency Resolution
 ┣━━ 📄 gradle.properties                 # JVM & R8 Build Optimization Flags
 ┣━━ 🖼️ youtube.png                       # Official Y-TUBE SLIM Brand Asset
 ┣━━ 🖼️ ic_launcher-playstore.png         # High-Res Store Icon
 ┃
 ┗━━ 📂 app                               # Main Native Android Module
      ┣━━ 📄 build.gradle.kts             # App Build Config, Signing & R8 Rules
      ┣━━ 📄 proguard-rules.pro           # Hardened ProGuard / R8 Keep Rules
      ┣━━ 💀 demon.txt                    # Custom R8 Obfuscation Dictionary (Class/Method)
      ┣━━ 👻 ghost.txt                    # Custom R8 Obfuscation Dictionary (Package/Field)
      ┃
      ┗━━ 📂 src/main
           ┣━━ 📄 AndroidManifest.xml     # Permissions, AudioService & Activity Config
           ┃
           ┣━━ 📂 java/id/y/ardiansyah    # Core Package (Y-ARDIANSYAH)
           ┃    ┣━━ 🚀 CoreApp.kt               ──► Application Class & Global Init
           ┃    ┣━━ 🛡️ CoreSystem.java          ──► System Integrity & Security Engine
           ┃    ┣━━ ⚙️ JniConfigState.java      ──► JNI Native Configuration Bridge
           ┃    ┣━━ 📱 MainActivity.kt          ──► Main Compose Host & Window Controller
           ┃    ┣━━ 🎬 Youtube.kt               ──► Core YouTube Player & WebView Container
           ┃    ┣━━ 📺 MiniPlayer.kt            ──► Interactive Draggable MiniPlayer UI
           ┃    ┣━━ 🧠 PlayerViewModel.java     ──► Playback State & UI Synchronization
           ┃    ┣━━ 🎧 AudioService.kt          ──► Foreground Service & Media Notification
           ┃    ┣━━ 🔗 JsInterface.kt           ──► @JavascriptInterface Native Bridge
           ┃    ┣━━ 💉 WebScripts.kt            ──► AdBlock JS Injection & DOM Cleaner
           ┃    ┣━━ 👆 TouchInterceptor.kt      ──► Custom Gesture & Multi-Touch Handler
           ┃    ┣━━ ✨ Logo.kt                  ──► Custom Vector & Brand UI Component
           ┃    ┗━━ 📂 ui/theme
           ┃         ┣━━ 🎨 Color.kt            ──► Sultan Dark Palette (#090A0E, #39FF14)
           ┃         ┣━━ 🌗 Theme.kt            ──► Material3 Dark Scheme Configuration
           ┃         ┗━━ 🔤 Type.kt             ──► Custom Typography Definitions
           ┃
           ┗━━ 📂 res                     # Optimized Android Resources
                ┣━━ 📂 drawable           ──► ic_youtube_notif.xml (Media Notification Icon)
                ┣━━ 📂 mipmap-*           ──► WebP Ultra-Compressed Adaptive Launcher Icons
                ┣━━ 📂 raw/keep.xml       ──► Strict Resource Shrinking Whitelist
                ┣━━ 📂 values             ──► colors.xml, strings.xml, themes.xml
                ┗━━ 📂 xml                ──► backup_rules.xml & data_extraction_rules.xml
```

---

## 💎 Bento Grid Feature Matrix

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ 1. Sultan AdBlocker Engine</h3>
      <p>Terintegrasi langsung di dalam <code>WebScripts.kt</code>. Menyuntikkan filter DOM & CSS tingkat lanjut untuk melenyapkan iklan video <i>pre-roll</i>, <i>mid-roll</i>, banner promosi, dan <i>overlay</i> pengganggu secara instan tanpa <i>delay</i>.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🎧 2. Non-Stop Background Audio</h3>
      <p>Ditenagai oleh <code>AudioService.kt</code> sebagai <i>Foreground Media Service</i>. Memungkinkan pemutaran musik dan podcast tetap berjalan mulus saat aplikasi diminimalkan atau layar ponsel dimatikan (<i>Screen-Off Playback</i>).</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📺 3. Seamless MiniPlayer & Gestures</h3>
      <p>Kombinasi <code>MiniPlayer.kt</code> dan <code>TouchInterceptor.kt</code> memberikan kontrol sentuh super responsif, <i>swipe gesture</i> presisi, serta mode pemutar mengambang untuk <i>multitasking</i> tanpa hambatan.</p>
    </td>
    <td width="50%" valign="top">
      <h3>💀 4. Demon & Ghost R8 Hardening</h3>
      <p>Menggunakan kamus pengacakan biner khusus (<code>demon.txt</code> & <code>ghost.txt</code>) yang dipadukan dengan <code>CoreSystem.java</code>, <code>JniConfigState.java</code>, dan <code>keep.xml</code> untuk menghasilkan APK ekstra ramping sekaligus kebal <i>decompiler</i>.</p>
    </td>
  </tr>
</table>

---

## 📊 Technical Module Specification

| Layer | File Modul | Bahasa | Peran & Tanggung Jawab Utama |
| :--- | :--- | :---: | :--- |
| **Core & Guard** | `CoreApp.kt`, `CoreSystem.java`, `JniConfigState.java` | `Kotlin` `Java` | Inisialisasi awal aplikasi, validasi *state* JNI, dan pengamanan *runtime*. |
| **UI & Theme** | `MainActivity.kt`, `Youtube.kt`, `MiniPlayer.kt`, `Logo.kt` | `Kotlin Compose` | Rendering antarmuka **Sultan Dark UI**, kontrol pemutar utama, dan animasi transisi. |
| **Bridge & DOM** | `WebScripts.kt`, `JsInterface.kt`, `TouchInterceptor.kt` | `Kotlin` `JS` | Injeksi *script* anti-iklan, intersepsi *touch event*, dan komunikasi *WebView-to-Native*. |
| **Media & State** | `AudioService.kt`, `PlayerViewModel.java` | `Kotlin` `Java` | Sinkronisasi status pemutaran video/audio dan manajemen notifikasi media latar belakang. |
| **Obfuscation** | `proguard-rules.pro`, `demon.txt`, `ghost.txt`, `keep.xml` | `R8 Config` | Penciutan ukuran APK (*shrinking*) dan obfuskasi agresif *bytecode* DEX. |

---

## 🎨 Sultan UI Color Palette

| Role | Hex Code | Preview | Usage |
| :--- | :---: | :---: | :--- |
| **Deep Obsidian** | `#090A0E` | ![#090A0E](https://placehold.co/15x15/090A0E/090A0E.png) | Primary Background & Canvas |
| **Dark Slate 3D** | `#1A1D24` | ![#1A1D24](https://placehold.co/15x15/1A1D24/1A1D24.png) | Elevated Cards & MiniPlayer Surface |
| **Cyber Neon Green** | `#39FF14` | ![#39FF14](https://placehold.co/15x15/39FF14/39FF14.png) | Active Indicators, Accents & Borders |
| **Sultan Gold** | `#FFD700` | ![#FFD700](https://placehold.co/15x15/FFD700/FFD700.png) | VIP Badges, Highlights & Branding |

---

<div align="center">

```	ext
╔═══════════════════════════════════════════════════════════════════════╗
║   ⚡ ENGINEERED WITH PRECISION BY Y-ARDIANSYAH (YUSUF ARDIANSYAH) ⚡ ║
║         Independent Android & Application Security Architect          ║
╚═══════════════════════════════════════════════════════════════════════╝
```

<a href="https://github.com/Yusuf-Ardiansyah">
  <img src="https://img.shields.io/badge/GITHUB_PROFILE-YUSUF--ARDIANSYAH-090A0E?style=for-the-badge&logo=github&logoColor=39FF14&labelColor=1A1D24" alt="GitHub" />
</a>

</div>
