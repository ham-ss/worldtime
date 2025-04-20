# worldtime

🕰️ A Folia-compatible plugin to simulate in-game calendar and timekeeping with real persistence.  
📦 Developed for MARVserver.

---

## 📝 Overview（概要）

**marvtime** tracks and displays in-game years, months, and days using persistent storage.  
It supports configurable save-backends (MariaDB or JSON) and multilingual support.

Minecraft 内の年・月・日を計測・保持する Folia 対応プラグインです。 
Minecraft の world フォルダ内の level.dat にある Time（tick）を基準にする
これは「サーバー全体が稼働していた合計時間（tick単位）」で、日付の進行（例: 1日 = 24000tick）に基づいて計算可能
MariaDB または JSON に保存可能で、複数言語の表示に対応しています。

> ⚠️ This plugin is provided **as-is**.  
> No support or bug fixes are guaranteed.

> ⚠️ 本プラグインは「現状のまま」提供されます。  
> 不具合への対応やサポートは**一切保証されません**。
