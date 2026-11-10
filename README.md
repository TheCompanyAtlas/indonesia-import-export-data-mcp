# Indonesia Import Export Data MCP

**Indonesia Customs Data: Importers, Suppliers & HS Codes.** Indonesia import export data for your AI assistant. Search Indonesia customs shipment records, find importers and foreign suppliers, and break down trade by HS code, partner country and counterparty company, through the Model Context Protocol.

An AI-native alternative to Indonesia trade data from Panjiva, ImportGenius, Volza, Seair, TradeInt and ExportGenius: ask in plain language instead of exporting spreadsheets.

The MCP connection is provided by [The Company Atlas](https://thecompanyatlas.com). This repository does not run a separate server.

## Connect

```
https://thecompanyatlas.com/mcp/trade/indonesia
```

Add this URL as a custom MCP connector in Claude, ChatGPT, Cursor, or any MCP-compatible client. Sign in with Google when prompted.

- Transport: Streamable HTTP
- Auth: Google OAuth (sign in once, stays authorized)
- Free accounts get 50 credits per calendar month
- Defaults to Indonesia: the server tells your AI to filter on `ID` unless you ask about another country

## Indonesia data coverage

- **Years:** 2018–2026
- **Records:** Import and export declarations: Indonesian importer or exporter, foreign counterparty, origin country, HS code, goods description, value, quantity, port, date, plus import duty and VAT where declared.
- **Country code:** `ID` (use `buyerCountry: "ID"` for imports into Indonesia)
- **Common products:** palm oil (HS 1511), stainless steel (HS 7219), coal (HS 2701), mobile phones (HS 8517)

## Notable traders in the data

Companies that appear most often in recent Indonesia records (by number of declaration lines, not value):

**Importers**

- PT Pertamina Patra Niaga
- PT Samsung Electronics Indonesia
- PT Toyota Motor Manufacturing Indonesia
- PT Erajaya Swasembada Tbk
- PT Huawei Tech Investment

**Exporters**

- Indonesia Tsingshan Stainless Steel
- Musim Mas
- PT Wilmar Nabati Indonesia
- Sinar Mas Agro Resources & Technology (SMART)
- PT Permata Hijau Palm Oleo

## Example prompts

- *"Who are the top exporters of crude palm oil (HS 1511) from Indonesia in 2025?"*
- *"What does PT Samsung Electronics Indonesia import, by HS code?"*
- *"Which countries does Indonesia Tsingshan Stainless Steel export to?"*
- *"List the biggest importers of mobile phones (HS 8517) into Indonesia"*
- *"Show the latest shipments imported by PT Toyota Motor Manufacturing Indonesia"*

## Bahasa Indonesia

Data impor ekspor Indonesia untuk asisten AI Anda. Cari data kepabeanan (bea cukai), temukan importir, eksportir dan pemasok luar negeri, lalu analisis perdagangan berdasarkan kode HS, negara mitra dan perusahaan mitra dagang, langsung dari Claude, ChatGPT, Cursor atau klien MCP lainnya.

- **Periode:** 2018–2026
- **Data:** impor dan ekspor: importir atau eksportir Indonesia, mitra dagang luar negeri, negara asal, kode HS, uraian barang, nilai, jumlah, pelabuhan dan tanggal, serta bea masuk dan PPN bila dilaporkan
- **URL MCP:** `https://thecompanyatlas.com/mcp/trade/indonesia`

**Contoh pertanyaan**

- *"Siapa eksportir minyak sawit mentah (HS 1511) terbesar dari Indonesia tahun 2025?"*
- *"Apa saja yang diimpor PT Samsung Electronics Indonesia, berdasarkan kode HS?"*
- *"Ke negara mana saja Indonesia Tsingshan Stainless Steel mengekspor?"*
- *"Siapa importir ponsel (HS 8517) terbesar di Indonesia?"*
- *"Tampilkan pengiriman impor terbaru PT Toyota Motor Manufacturing Indonesia"*

## Tools

### Trade search

| Tool | Description |
|---|---|
| `Trade_search_trades` | Paginated customs shipment search: filter by HS code, buyer, seller, country, port, value and date range |
| `Trade_company_trade_volume_by_year` | Rank importers or exporters by declared value and line counts per year, with HS code and country filters |

### Trade analytics

| Tool | Description |
|---|---|
| `Trade_hs_code_breakdown` | For one company, import and export value by HS chapter, heading or subheading |
| `Trade_year_country_breakdown` | For one company, trade value by year and counterparty country |
| `Trade_partner_breakdown` | For one company, trade value by year and matched counterparty company |

### Company registry

| Tool | Description |
|---|---|
| `Company_search` | Search the global company registry by name or id, with optional country filter |
| `Company_get_by_id` | Full company profile by id |

## Keywords

Indonesia import data, Indonesia export data, Indonesia customs data, Indonesia shipment data, importers in Indonesia, Indonesia buyers and suppliers, HS code search, data impor ekspor Indonesia, data bea cukai, daftar importir dan eksportir Indonesia, kode HS
