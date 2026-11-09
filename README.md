# Finland Legal Research MCP Server (`fi-legal-mcp`)

**[Suomi](#lang-fi) | [Svenska](#lang-sv) | [English Documentation](#english-documentation)**

---

<a id="lang-fi"></a>
## Oikeudellinen MCP-palvelin (Lainsäädäntö ja oikeuskäytäntö) (`fi-legal-mcp`) — Suomi

### Tietoa tästä paketista

Tämä paketti sisältää Model Context Protocol (MCP) -palvelimen, joka yhdistää tekoälysovelluksesi (Claude Desktop, Cursor, Windsurf, VS Code / Copilot, Cline tai Antigravity) suoraan Finlex-tietokantaan (`finlex.fi`) ja Suomen tuomioistuinjärjestelmän ratkaisuihin (käräjäoikeudet, hallinto-oikeudet, hovioikeudet, korkein oikeus KKO ja korkein hallinto-oikeus KHO).

### Asennus (Tekoälysovelluksen valinta)

1. **Lataa:** Napsauta oikeasta yläkulmasta **`<> Code` -> `Download ZIP`** ja pura kansio tietokoneellesi.
2. **Käynnistä asennusohjelma:** Kaksoisnapsauta **`Click_Here_To_Install_Windows.bat`** (Windows) tai **`Click_Here_To_Install_Mac.command`** (macOS).
3. **Valitse tekoälysovellus:** Valitse käyttämäsi tekoälyohjelmat (Claude, Cursor, Windsurf, VS Code, Antigravity), napsauta asenna ja käynnistä valitsemasi sovellus uudelleen.

**Tietoturvahuomautus:** Ohjelma toimii vain luku -tilassa (read-only) eikä lue tai muokkaa tietokoneellasi olevia henkilökohtaisia tiedostoja.

### Oikeusasteet ja viralliset tietolähteet

| Oikeusaste | Kattavat tuomioistuimet |
|:---|:---|
| **Ensimmäinen oikeusaste (Käräjä- ja hallinto-oikeudet)** | 20 Käräjäoikeudet (District Courts), 6 Hallinto-oikeudet (Regional Administrative Courts) & Markkinaoikeus (Market Court) |
| **Muutoksenhakuaste (Hovioikeudet)** | 5 Hovioikeudet (Courts of Appeal: Helsinki, Turku, Vaasa, Itä-Suomi, Rovaniemi) & Vakuutusoikeus |
| **Ylimmät tuomioistuimet (KKO ja KHO)** | Korkein oikeus (KKO — Supreme Court) & Korkein hallinto-oikeus (KHO — Supreme Administrative Court) |

- **Finlex Open Data API (finlex.fi / data.finlex.fi):** [https://www.finlex.fi](https://www.finlex.fi) (`finlex.fi`, `eduskunta.fi`)
- **Finlex Oikeuskäytäntö (finlex.fi/fi/oikeus — KKO, KHO, Hovioikeudet & Hallinto-oikeudet):** [https://www.finlex.fi/fi/oikeus/](https://www.finlex.fi/fi/oikeus/) (`finlex.fi`, `korkeinoikeus.fi`, `kho.fi`, `oikeus.fi`)

---

<a id="lang-sv"></a>
## Rättslig MCP-server för lagstiftning och rättspraxis (`fi-legal-mcp`) — Svenska

### Om detta arkiv

Detta arkiv innehåller en Model Context Protocol (MCP) server som ansluter din AI-applikation (Claude Desktop, Cursor, Windsurf, VS Code / Copilot, Cline eller Antigravity) direkt till officiella författningssamlingar och rättsfallsdatabaser för **Finland** (första instans, hovrätter/kammarrätter samt högsta domstolar).

### Installation (Val av AI-applikation)

1. **Ladda ner:** Klicka på **`<> Code` -> `Download ZIP`** uppe till höger och packa upp mappen på din dator.
2. **Starta installationsguiden:** Dubbelklicka på **`Click_Here_To_Install_Windows.bat`** (Windows) eller **`Click_Here_To_Install_Mac.command`** (macOS).
3. **Välj AI-klient:** Markera de AI-program du använder (Claude, Cursor, Windsurf, VS Code, Antigravity), klicka på installera och starta om din AI-applikation.

**Säkerhetsinformation:** Installationsprogrammet arbetar i skrivskyddat läge (read-only) och läser eller ändrar inga personliga filer på din dator.

### Domstolshierarki och officiella källor

| Instans | Domstolar som omfattas |
|:---|:---|
| **1:a instans (Underrätter)** | 20 Käräjäoikeudet (District Courts), 6 Hallinto-oikeudet (Regional Administrative Courts) & Markkinaoikeus (Market Court) |
| **2:a instans (Överrätter / Appellationsdomstolar)** | 5 Hovioikeudet (Courts of Appeal: Helsinki, Turku, Vaasa, Itä-Suomi, Rovaniemi) & Vakuutusoikeus |
| **Högsta instans (Högsta domstolar)** | Korkein oikeus (KKO — Supreme Court) & Korkein hallinto-oikeus (KHO — Supreme Administrative Court) |

- **Finlex Open Data API (finlex.fi / data.finlex.fi):** [https://www.finlex.fi](https://www.finlex.fi) (`finlex.fi`, `eduskunta.fi`)
- **Finlex Oikeuskäytäntö (finlex.fi/fi/oikeus — KKO, KHO, Hovioikeudet & Hallinto-oikeudet):** [https://www.finlex.fi/fi/oikeus/](https://www.finlex.fi/fi/oikeus/) (`finlex.fi`, `korkeinoikeus.fi`, `kho.fi`, `oikeus.fi`)

---

<a id="english-documentation"></a>
## English Documentation

Model Context Protocol (MCP) server providing live, read-only access to **Finland (FI)** legislation, official gazettes, multi-tier judicial decisions (First Instance, Regional/Cantonal/Appellate, and Supreme/Constitutional courts, including HTML and PDF full-text extraction), and statutory citation verification across all major AI clients (**ChatGPT Desktop, OpenAI Codex CLI, Claude Desktop, Claude Code CLI, Cursor, Windsurf, VS Code / GitHub Copilot / Cline / Roo Code, Google Antigravity / Gemini CLI, Perplexity, and Continue.dev**).

---

### Interactive Desktop Setup (Select Your AI Assistant)

This package includes a graphical installer for legal practitioners and non-technical users that lets you select which AI application(s) you use:

1. **Download:** Click **`<> Code`** at the top right of this repository, select **`Download ZIP`**, and extract the folder to your computer.
2. **Run the Setup Utility:**
   - **Windows:** Double-click `Click_Here_To_Install_Windows.bat`
   - **macOS:** Double-click `Click_Here_To_Install_Mac.command`
3. **Select Your AI Client(s) & Connect:** Check the box(es) for the AI assistant(s) installed on your computer (**ChatGPT Desktop & OpenAI Codex CLI**, **Claude Desktop & Claude Code CLI**, **Cursor**, **Windsurf**, **VS Code / GitHub Copilot / Cline / Roo Code**, **Google Antigravity / Gemini CLI**, or **Perplexity / Continue.dev**), click **Install to Selected AI Clients**, and restart your selected AI application.

**System Integrity Note:** The setup utility operates strictly in read-only mode with respect to your personal files and documents. It installs an isolated Python runtime inside the extracted folder and registers the server entry only in the AI client configuration files you select.

---

### Multi-Tier Judicial Hierarchy & Live Indexed National Archives

This server performs live queries across the full judicial hierarchy and official legal archives of **Finland**, extracting full text from both HTML pages and official court/gazette PDF judgments:

| Judicial Tier | Covered Courts & Tribunals |
|:---|:---|
| **Tier 1 — First Instance** | 20 Käräjäoikeudet (District Courts), 6 Hallinto-oikeudet (Regional Administrative Courts) & Markkinaoikeus (Market Court) |
| **Tier 2 — Regional / Cantonal / Appellate** | 5 Hovioikeudet (Courts of Appeal: Helsinki, Turku, Vaasa, Itä-Suomi, Rovaniemi) & Vakuutusoikeus |
| **Tier 3 — Supreme & Constitutional** | Korkein oikeus (KKO — Supreme Court) & Korkein hallinto-oikeus (KHO — Supreme Administrative Court) |

#### Official Portals & Live Indexed Domains

- **National Legislation & Official Gazette:** Finlex Open Data API (finlex.fi / data.finlex.fi) — [https://www.finlex.fi](https://www.finlex.fi)
  - *Indexed Legislation Domains:* `finlex.fi`, `eduskunta.fi`
- **Court Decisions & Jurisprudence Archives:** Finlex Oikeuskäytäntö (finlex.fi/fi/oikeus — KKO, KHO, Hovioikeudet & Hallinto-oikeudet) — [https://www.finlex.fi/fi/oikeus/](https://www.finlex.fi/fi/oikeus/)
  - *Indexed Judicial & Open Case Law Domains:* `finlex.fi`, `korkeinoikeus.fi`, `kho.fi`, `oikeus.fi`

---

### Available MCP Tools

| Tool | Description |
|:---|:---|
| `search_legislation` | Searches enacted statutes, codes, decrees, and official gazette publications in Finland. |
| `search_case_law` | Searches national jurisprudence and open judicial archives for Finland. |
| `search_tiered_court_decisions` | Filters case law specifically by judicial instance (`first_instance`, `appellate_regional`, `supreme_constitutional`) or specific regional/cantonal/district court. |
| `list_court_hierarchy` | Returns the complete 3-tier court structure and supported regional court filters for Finland. |
| `get_legal_document_markdown` | Retrieves full statutory or judicial texts (both HTML and official `.pdf` court judgments) and converts them into clean Markdown. |
| `verify_citation` | Validates statutory and case law citations against official registries. |

---

<details>
<summary><b>Manual Configuration for Developers (Optional)</b></summary>

```json
{
  "mcpServers": {
    "fi-legal-mcp": {
      "command": "uvx",
      "args": [
        "--from",
        "https://github.com/jurisatlas/fi-legal-mcp/archive/refs/heads/main.zip",
        "fi-legal-mcp"
      ]
    }
  }
}
```
</details>
