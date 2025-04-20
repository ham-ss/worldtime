# worldtime

🕰️ A Folia-compatible plugin to simulate and track in-game calendar progression.  
📦 Developed for MARVserver.

---

## 📝 Overview（概要）

**worldtime** is a Folia-compatible plugin that tracks and preserves in-game year, month, and day progression.  
It uses the `Time` value stored in `level.dat` under the world folder, which represents the **total server runtime in ticks**.  
The date is calculated based on Minecraft’s internal tick system (1 day = 24,000 ticks).  
Data is persistently stored in **MariaDB** or **JSON**, and the plugin supports **multiple languages**.

**worldtime** は Minecraft 内の年・月・日を計測・保持する **Folia 対応プラグイン**です。  
時間の基準としては、`world` フォルダ内の `level.dat` に保存されている `Time`（tick）値を使用します。  
これは「**サーバーが稼働していた総時間（tick単位）**」であり、1日 = 24,000tick という Minecraft の仕様に基づいて日時を計算します。  
データは **MariaDB または JSON** に保存でき、**多言語表示**にも対応しています。

> ⚠️ This plugin is provided **as-is**.  
> No support or bug fixes are guaranteed.

> ⚠️ 本プラグインは「現状のまま」提供されます。  
> 不具合への対応やサポートは**一切保証されません**。
