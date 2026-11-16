<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg" />
    <img src="./assets/hero-dark.svg" width="100%" alt="Yücel Gümüş — Full Stack AI Engineer, Multi-Agent Systems, 3D and Spatial Intelligence" />
  </picture>

  <br/><br/>

  [![Portfolio](https://img.shields.io/badge/Portfolio-yucelgumus.dev-EC7D55?style=for-the-badge&labelColor=253341&logo=googlechrome&logoColor=F5F9F5)](https://www.yucelgumus.dev/)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Y%C3%BCcel_G%C3%BCm%C3%BC%C5%9F-3E5164?style=for-the-badge&labelColor=253341&logo=linkedin&logoColor=F5F9F5)](https://www.linkedin.com/in/yucel-gumus/)
  [![Hugging Face](https://img.shields.io/badge/Hugging_Face-yucelgumus61-F2A488?style=for-the-badge&labelColor=253341&logo=huggingface&logoColor=253341)](https://huggingface.co/spaces/yucelgumus61)
  [![GitHub](https://img.shields.io/badge/GitHub-yucel--gumus-253341?style=for-the-badge&labelColor=3E5164&logo=github&logoColor=F5F9F5)](https://github.com/yucel-gumus)
</div>

---

## 👨‍💻 Mühendislik Odağı & Deneyim

Merhaba, ben **Yücel Gümüş**. **Çoklu etmenli yapay zeka (Multi-Agent AI) sistemleri**, **gerçek zamanlı 3B WebGL / dijital ikiz sahneleri** ve **mekansal zeka (CBS / GIS)** alanlarında fikirden canlı üretime uzanan yazılımlar tasarlıyorum.

- 🧠 **Full Stack AI Engineer @ EnerwiseAI (Tekhnelogos):** Çoklu etmenli iş akışı orkestrasyonu, yerel donanım (**NVIDIA DGX Spark**) üzerinde LLM dağıtımı/ince ayarı, zaman serisi modellemesi, OCR + yapılandırılmış veri çıkarımı ve `.NET Core` / `React & TypeScript` üretim sistemleri geliştiriyorum.
- 🏗️ **Geçmiş Üretim Deneyimi:** **Turkuvaz Medya Grubu**'nda yüksek trafikli dijital yayın ve akademi platformları; **Pavo Group (Interdata)** bünyesinde gerçek zamanlı araç/sensör telemetri sistemleri ve test otomasyonu; **Harita Genel Müdürlüğü**'nde **CesiumJS** tabanlı 3B uydu/İHA harita uygulamaları geliştirdim.
- ☁️ **Canlı Ekosistem:** **Google Cloud Run**, **Firebase Hosting / Firestore**, **Vercel Edge** ve **GitHub Pages** üzerinde aktif çalışan **20+ canlı uygulama**, merkezi FastAPI AI ağ geçidi ve çok sağlayıcılı akış proxy'leri işletiyorum.

---

## 🏗️ Canlı Üretim Mimarisi

```mermaid
flowchart LR
  subgraph Client["Istemci ve 3B WebGL Katmani"]
    PF["yucelgumus.dev (Next.js 15)"]
    ARENA["DaM[AI]ngala & Sahm[AI]t (Three.js r186)"]
    TWIN["Gobeklitepe 3D & Cesium 6-DOF Drone"]
    APPS["13+ AI, RAG, Harita & Atlas Web Uygulamasi"]
  end

  subgraph CloudRun["Google Cloud Run (europe-west3 / europe-west4)"]
    GW["Central FastAPI AI Gateway"]
    ADK["KENSAI Multi-Agent Supervisor (Google ADK)"]
    NODE["Zero-Dep Node 22 SSE BYOK Proxy"]
    TOOLS["DevControl AI & SiteAnaliz & Firecrawl LangGraph"]
  end

  subgraph Data["Veri, Vektor & Kontrol Duzlemi"]
    FS["Firebase Firestore (Canli Model Yonlendirme)"]
    VEC["Pinecone Vector RAG & Memory"]
    STORE["MongoDB · Upstash Redis · AWS S3 · GCS"]
  end

  PF -->|"Edge SSE Proxy"| ADK
  ARENA -->|"Direct Cloud Run SSE"| NODE
  APPS -->|"BFF / Direct HTTPS"| GW
  GW --> FS
  GW --> VEC
  ADK --> STORE
  TOOLS --> FS
```

---

## 🌟 Vitrin Projeleri (Seçkin Sistemler)

| Proje | Mühendislik Özeti | Teknoloji | Erişim |
|---|---|---|---|
| **DaM\[AI\]ngala** | %100 prosedürel 3B çayevinde Türk Daması ve TAZOF Mangala arenası; sıfır bağımlılıklı Node 22 SSE proxy ile OpenAI, Claude, Gemini ve OpenCode Zen arasında canlı maçlar | `React 19`, `Three.js`, `Node 22`, `Cloud Run` | [Canlı](https://damaingala.web.app/) |
| **Şahm\[AI\]t Arena** | Obsidyen katedral sahnesinde meshopt `.glb.gz` ve dinamik LOD taşlar, düello animasyonları ve 4 LLM sağlayıcılı canlı BYOK satranç karşılaşmaları | `React 19`, `Three.js`, `chess.js`, `Node 22` | [Canlı](https://sahmait.web.app/) |
| **DevControl AI** | GitHub repo sağlığı, hotspot refactor tespiti, commit sınıflandırma ve Gemini tabanlı mimari kod inceleme/risk analizi platformu | `TypeScript`, `React 19`, `Express`, `Firestore` | [Canlı](https://devcontrol-ai.web.app/) · [GitHub](https://github.com/yucel-gumus/DevControl-AI) |
| **Cesium 6-DOF Drone** | Uzungöl arazisinde 240 Hz RK4 kuadrotor fiziği, 120 Hz 17-durumlu ESKF, Dryden rüzgâr türbülansı, 1.150 OSM engeli ve PX4 `.ulg` kalibrasyonu | `CesiumJS`, `Web Workers`, `ES Modules`, `Playwright` | [Canlı](https://yucel-gumus.github.io/cesium-drone.github.io/) · [GitHub](https://github.com/yucel-gumus/cesium-drone.github.io) |
| **SiteAnaliz** | Lighthouse, CrUX, HTTP Observatory, SSL Labs ve W3C HTML denetimlerini SSRF korumalı tarayıcıyla birleştirip düzeltme prompt'ları üreten denetim motoru | `Node.js`, `Express`, `Gemini`, `Cloud Run` | [Canlı](https://site-analiz.web.app/) · [GitHub](https://github.com/yucel-gumus/web-site-analiz) |
| **Göbeklitepe 3B İkiz** | A–H anıtsal yapıları, 118 arkeolojik buluntu, 12 rehberli keşif durağı ve gündönümü güneş hizalanması simülasyonu sunan 3B dijital ikiz | `Three.js`, `JavaScript`, `WebAudio`, `Cloud Run` | [Canlı](https://gobeklitepe.web.app/) |
| **Türk Tarih Atlası** | MÖ 220'den günümüze 87 devlet, 748 hükümdar, 798 savaş ve 834 birincil kaynağı derleme zamanı Zod doğrulamasıyla sunan etkileşimli soyağacı | `Svelte 5`, `TypeScript`, `Vite 8`, `Zod` | [Canlı](https://yucel-gumus.github.io/turk-tarih-atlasi/) · [GitHub](https://github.com/yucel-gumus/turk-tarih-atlasi) |
| **Portfolyo & KENSAI** | Google ADK supervisor + GitHub ve CV uzman ajanlarıyla canlı SSE sohbet, Upstash Redis önbelleği ve S3 medya yönetimi sunan ana platform | `Next.js 15`, `Google ADK`, `FastAPI`, `MongoDB` | [yucelgumus.dev](https://www.yucelgumus.dev/) |

---

## 📂 Tüm Proje Ekosistemi

<details open>
<summary><strong>🤖 Yapay Zeka, Çoklu Ajan, RAG &amp; Üretken Uygulamalar (8 Açık Proje)</strong></summary>

| Proje | Açıklama | Teknoloji | Bağlantılar |
|---|---|---|---|
| **Market AI** | Canlı market fiyat arama, 3 aşamalı AI tarif → ürün seçimi ve tek/çift mağaza rota optimizasyonu | `Next.js 15`, `Zustand`, `Leaflet`, `Vitest` | [Canlı](https://market-ai-coral.vercel.app/) · [GitHub](https://github.com/yucel-gumus/market-ai) |
| **Yapay Zeka Tartışma Platformu** | Çok turlu uzman ajan münazarası, tarafsız Hakem Ajan puanlaması ve kalıcı paylaşım | `Next.js 15`, `React 19`, `Firestore` | [Canlı](https://yapay-zeka-tartisma-platformu.vercel.app/) · [GitHub](https://github.com/yucel-gumus/yapay-zeka-tartisma-platformu) |
| **RAG Web Chat** | Web sitelerini SSRF korumalı kazıyıp oturum bazlı kaynaklı soru-cevap yapan RAG platformu | `Next.js 15`, `Cheerio`, `Pinecone` | [Canlı](https://rag-web-chat.vercel.app/) · [GitHub](https://github.com/yucel-gumus/RAG_Web_Chat) |
| **Document Chat** | PDF, DOCX ve TXT belgelerini parçalayıp SSE akışıyla doküman sohbeti sunan RAG arayüzü | `Next.js 15`, `pdfreader`, `mammoth` | [Canlı](https://document-chat-iota.vercel.app/) · [GitHub](https://github.com/yucel-gumus/document_chat) |
| **Firecrawl + LangGraph Summarizer** | LangGraph durum makinesi ile canlı web sayfalarını yapılandırılmış JSON özete dönüştüren servis | `FastAPI`, `LangGraph`, `Firecrawl`, `Gemini` | [Canlı](https://firecrawl-mcp.web.app/) · [GitHub](https://github.com/yucel-gumus/Firecrawl_MCP-Gemini-LangGraph) |
| **GA4 MCP Chat** | Google Analytics 4 verilerini Model Context Protocol üzerinden doğal dilde sorgulayan analitik paneli | `React`, `TypeScript`, `MCP`, `GA4` | [Canlı](https://ga4-mcp-chat-kappa.vercel.app/) · [GitHub](https://github.com/yucel-gumus/GA4_MCP_Chat) |
| **AI Flashcard Generator** | Konu başlığından çift taraflı etkileşimli çalışma kartları ve PDF çıktısı üreten uygulama | `React 19`, `Vite 6`, `jsPDF` | [Canlı](https://bilgi-kart-olu-turucu.vercel.app/) · [GitHub](https://github.com/yucel-gumus/flashcard_generate) |
| **AI Speech-to-Text** | WebAudio frekans spektrumu ile ses kaydı, transkripsiyon ve metin iyileştirme | `TypeScript`, `Vite 6`, `WebAudio`, `DOMPurify` | [Canlı](https://yucel-gumus.github.io/speech-to-text/) · [GitHub](https://github.com/yucel-gumus/speech-to-text) |

</details>

<details>
<summary><strong>🗺️ Mekansal Zeka (CBS / GIS), Harita &amp; Görsel Analiz (7 Proje)</strong></summary>

| Proje | Açıklama | Teknoloji | Bağlantılar |
|---|---|---|---|
| **Mosque AI (İstanbul Cami Rehberi)** | 2.741 İstanbul camisi GeoJSON verisi, namaz vakitleri ve tool-calling harita asistanı | `React 19`, `Google Maps`, `Zustand`, `Vitest` | [Canlı](https://yucel-gumus.github.io/mosque_ai/) · [GitHub](https://github.com/yucel-gumus/mosque_ai) |
| **AI Map Route Planner** | Çok günlük gezi rotası, TSP kümeleme, Street View ve yazdırılabilir broşür planlayıcısı | `Vanilla TS`, `Vite 6`, `Google Maps SDK` | [Canlı](https://ai-map-planning-and-info.vercel.app/) · [GitHub](https://github.com/yucel-gumus/ai_map_planning_and_info) |
| **3D Image Space** | 3B küre ve UMAP yerleşimi üzerinde anlamsal görsel arama ve otomatik etiketleme galerisi | `React 19`, `Three.js / R3F`, `IndexedDB` | [Canlı](https://image-space-ten.vercel.app/) · [GitHub](https://github.com/yucel-gumus/image_space) |
| **Image Object Finder** | Görsellerde 2B sınırlayıcı kutu, nokta ve segmentasyon maskesi tespiti yapan analiz tuvali | `React 19`, `Jotai`, `Vite 6` | [Canlı](https://image-find-object.vercel.app/) · [GitHub](https://github.com/yucel-gumus/image_find_object) |
| **GeoGemini** | 10 kategoride çok modlu coğrafi keşif ve akıllı mekan öneri haritası | `React 19`, `Leaflet`, `Framer Motion` | [Canlı](https://yucel-gumus.github.io/GeoGemini/) · [GitHub](https://github.com/yucel-gumus/GeoGemini) |
| **Gemini MCP Maps** | Lit Web Components tabanlı, SSE araç çağrılı etkileşimli harita sohbeti | `Lit 3`, `TypeScript`, `Leaflet`, `MCP` | [Canlı](https://yucel-gumus.github.io/gemini-mcp-maps/) · [GitHub](https://github.com/yucel-gumus/gemini-mcp-maps) |
| **Turkey 81-Province GIS Map** | 81 il vektör poligonları üzerinde WGS84 DMS, EPSG:3857 ve dinamik UTM (35N–38N) dönüşümü | `React`, `Leaflet`, `Proj4`, `GeoJSON` | [Canlı](https://yucel-gumus.github.io/turkey-map.github.io/) · [GitHub](https://github.com/yucel-gumus/turkey-map.github.io) |

</details>

<details>
<summary><strong>🛡️ Siber Güvenlik (TSCM), Veri Panelleri, Algoritma &amp; CLI Araçları (5 Proje)</strong></summary>

| Proje | Açıklama | Teknoloji | Bağlantılar |
|---|---|---|---|
| **AirSentinel** | Apple Silicon macOS için BLE / Wi-Fi / ONVIF gizli kamera ve ASTM F3411 Drone Remote ID tarayıcı + yerel Ollama analizi | `Python`, `FastAPI`, `Bleak`, `CoreWLAN`, `Ollama` | [GitHub](https://github.com/yucel-gumus/airsentinel) |
| **Dynamic Energy Dashboard** | Sürükle-bırak (`@dnd-kit` + `react-grid-layout`) destekli 16 bileşenli endüstriyel enerji/KPI paneli | `React 19`, `Vite 7`, `Zustand`, `Recharts` | [Canlı](https://yucel-gumus.github.io/dynamic_dashboard/) · [GitHub](https://github.com/yucel-gumus/dynamic_dashboard) |
| **Pathfinding Visualizer** | A*, Dijkstra, BFS, DFS, Greedy Best-First ve Bidirectional BFS + özyinelemeli labirent simülatörü | `React 19`, `Tailwind CSS`, `Framer Motion` | [GitHub](https://github.com/yucel-gumus/path_find) |
| **Video Cut Terminal** | Hızlı sahne kırpma, ses çıkarma ve toplu dönüştürme sunan komut satırı medya aracı | `Python`, `Typer`, `Rich`, `FFmpeg`, `OpenCV` | [GitHub](https://github.com/yucel-gumus/Video_Cut_Terminal) |
| **Rick &amp; Morty MultiSelect** | Klavye navigasyonlu, vurgulu arama ve etiket chip yönetimli çoklu seçim bileşeni | `React`, `TypeScript` | [Canlı](https://yucel-gumus.github.io/RickAndMorty_MultiSelect/) · [GitHub](https://github.com/yucel-gumus/RickAndMorty_MultiSelect) |

</details>

---

## 🛠️ Teknoloji Yığını

<div align="center">

**AI, Ajanlar &amp; Protokoller**

![Google Gemini](https://img.shields.io/badge/Google_Gemini-253341?style=flat-square&logo=google&logoColor=F2A488)
![Google ADK](https://img.shields.io/badge/Google_ADK-EC7D55?style=flat-square&logo=googlecloud&logoColor=253341)
![LangGraph](https://img.shields.io/badge/LangGraph-AB421C?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-3E5164?style=flat-square&logo=langchain&logoColor=F5F9F5)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-253341?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone_Vector-3E5164?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-253341?style=flat-square&logo=ollama&logoColor=F5F9F5)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-F2A488?style=flat-square&logo=huggingface&logoColor=253341)

**Frontend, 3B WebGL &amp; CBS (GIS)**

![TypeScript](https://img.shields.io/badge/TypeScript-3E5164?style=flat-square&logo=typescript&logoColor=F5F9F5)
![React](https://img.shields.io/badge/React_19-253341?style=flat-square&logo=react&logoColor=F2A488)
![Next.js](https://img.shields.io/badge/Next.js_15-253341?style=flat-square&logo=next.js&logoColor=F5F9F5)
![Svelte](https://img.shields.io/badge/Svelte_5-EC7D55?style=flat-square&logo=svelte&logoColor=253341)
![Three.js](https://img.shields.io/badge/Three.js_%2F_WebGL-253341?style=flat-square&logo=three.js&logoColor=F5F9F5)
![CesiumJS](https://img.shields.io/badge/CesiumJS-3E5164?style=flat-square&logo=cesium&logoColor=F5F9F5)
![Leaflet](https://img.shields.io/badge/Leaflet-DCE3EA?style=flat-square&logo=leaflet&logoColor=253341)
![Vite](https://img.shields.io/badge/Vite-AB421C?style=flat-square&logo=vite&logoColor=F5F9F5)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3E5164?style=flat-square&logo=tailwindcss&logoColor=F5F9F5)

**Backend, Bulut &amp; Veri**

![Python](https://img.shields.io/badge/Python-3E5164?style=flat-square&logo=python&logoColor=F5F9F5)
![FastAPI](https://img.shields.io/badge/FastAPI-253341?style=flat-square&logo=fastapi&logoColor=EC7D55)
![Node.js](https://img.shields.io/badge/Node.js-3E5164?style=flat-square&logo=nodedotjs&logoColor=F5F9F5)
![.NET Core](https://img.shields.io/badge/.NET_Core-253341?style=flat-square&logo=dotnet&logoColor=F5F9F5)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-3E5164?style=flat-square&logo=googlecloud&logoColor=F5F9F5)
![Firebase](https://img.shields.io/badge/Firebase-EC7D55?style=flat-square&logo=firebase&logoColor=253341)
![Docker](https://img.shields.io/badge/Docker-3E5164?style=flat-square&logo=docker&logoColor=F5F9F5)
![MongoDB](https://img.shields.io/badge/MongoDB-253341?style=flat-square&logo=mongodb&logoColor=EDF3EE)
![Upstash Redis](https://img.shields.io/badge/Redis-AB421C?style=flat-square&logo=redis&logoColor=F5F9F5)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-3E5164?style=flat-square&logo=postgresql&logoColor=F5F9F5)

</div>

---

## 📈 GitHub İstatistikleri

<div align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=yucel-gumus&show_icons=true&count_private=true&bg_color=DCE3EA&title_color=253341&text_color=3E5164&icon_color=EC7D55&border_color=BCC7D2" height="170" alt="GitHub Stats" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=yucel-gumus&layout=compact&bg_color=DCE3EA&title_color=253341&text_color=3E5164&icon_color=EC7D55&border_color=BCC7D2" height="170" alt="Top Langs" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=yucel-gumus&background=DCE3EA&border=BCC7D2&stroke=BCC7D2&ring=EC7D55&fire=EC7D55&currStreakNum=253341&sideNums=253341&currStreakLabel=253341&sideLabels=3E5164&dates=3E5164" height="170" alt="GitHub Streak" />
</div>

---

<div align="center">
  <a href="https://www.yucelgumus.dev/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Designed_%26_Engineered_by-Y%C3%BCcel_G%C3%BCm%C3%BC%C5%9F-EC7D55?style=for-the-badge&labelColor=253341&logo=googlechrome&logoColor=F5F9F5" alt="Yücel Gümüş" />
  </a>
</div>
