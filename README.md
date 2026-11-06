# Eronov Dilshodbek

I run The Endurance Industrial Technologies in Tashkent. We build automation and software for factories and industrial plants. I've been doing this for 3 years.

## Projects

### C-MIND - refinery production planning
Planning and optimization system for oil refineries. LP/MILP model on Pyomo and HiGHS: crude assays and TBP curves, unit operating modes, blending, multi-period plans, mass/sulfur/hydrogen balance checks. Also has an RBI module based on API 580/581. Desktop app (PySide6), CLI and REST API. Works with Excel and .pims files, OPC UA integration.

### FIFO WMS - warehouse management
Warehouse system with FIFO stock rotation. FastAPI backend, React frontend with a 3D view of the warehouse. Handheld terminal app for receiving pallets from the production line by SSCC scan. ESP32 temperature and humidity sensors in the warehouse. Pulls history from Smartup ERP. Running in production.

### Production line marking and aggregation
Desktop app that runs on a production line. Talks to the conveyor over serial, scans and checks product codes, packs units into boxes and boxes into pallets, and sends everything to the national marking system (Asl Belgisi). Has an operator HMI, a Telegram bot for shift reports and a cloud dashboard as a Telegram Mini App.

### Marking operations app
Electron + TypeScript desktop app for marking work: stock, sales, e-invoices and aggregation, with license control.

### Aggregation engine
Windows tool for working with marking codes through the Asl Belgisi API: putting codes into circulation, multi-level aggregation, checking the code hierarchy, CSV import. Built to .exe with GitHub Actions.

### Voice assistant mini app
Telegram Mini App with an admin panel and an AI assistant that speaks Uzbek (speech-to-text, text-to-speech, LLM).

Mostly Python and TypeScript.

Contact: enduranceindustrial@outlook.com
