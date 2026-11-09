# Privacy Policy — Sanctuary Clock

_Last updated: 2026-11-09_

Sanctuary Clock ("the app") is an unofficial companion app that shows community-reported Diablo Clone progress and Terror Zone rotations for Diablo II: Resurrected. It is not affiliated with or endorsed by Blizzard Entertainment.

## What the app collects

The app does not collect any personal information. It has no accounts and no advertising.

**Anonymous usage analytics.** The app uses Google Firebase Analytics (the variant without advertising identifiers) to understand which features are used. Firebase records which buttons are tapped (for example "opened settings", "picked a server", "toggled a reminder"), together with app version, device model, OS version, language and country. This data is aggregated, not linked to your identity, and not used for advertising or tracking across apps. It is processed by Google under the [Firebase privacy terms](https://firebase.google.com/support/privacy).

## Network requests

To show live data, the app sends requests to two sources:

- **The developer's own server** (Google Cloud, Firebase project operated by the developer) for Diablo Clone progress. That server fetches the data from **d2emu.com** once a minute on behalf of all users; your device never contacts d2emu.com directly. Requests to the developer's server contain only the data being requested.
- **d2runewizard.com** (a third-party community site) for Terror Zones and planned walks. These requests contain only the data being requested and a fixed developer contact address and app identifier required by that site's fair-use policy.

They do not include any information about you or your device beyond what any standard HTTPS request carries (such as your IP address, which the server operators may log under their own privacy policies).

## Data stored on your device

Your preferences (tracked server, favorite Terror Zones, alert switches) are stored only on your device and are deleted when you delete the app.

## Notifications

If you allow notifications, the app schedules local notifications on your device for planned walks.

Diablo Clone progress changes and Terror Zone rotations are delivered as **push notifications** through Apple Push Notification service and Google Firebase Cloud Messaging. To receive them, the app registers an anonymous push token with Firebase and subscribes to "topics" that describe only your settings (for example the server you track, your favorite Terror Zones and your app language). The token is a random device identifier that is not linked to your identity and is used for nothing other than delivering these notifications. Turning off the alert switches in Settings unsubscribes the device; deleting the app invalidates the token.

## Children

The app does not knowingly collect any information from anyone, including children.

## Contact

Questions: briat2004@icloud.com

---

# 隱私權政策 — Sanctuary Clock

_最後更新：2026-11-09_

Sanctuary Clock（以下稱「本 App」）是非官方的輔助工具，顯示《暗黑破壞神 II：獄火重生》玩家回報的地表暗黑進度與恐怖地帶輪換，與 Blizzard Entertainment 無關。

## 本 App 收集什麼

本 App 不收集任何個人資訊；沒有帳號、沒有廣告。

**匿名使用分析。** 本 App 使用 Google Firebase Analytics（不含廣告識別碼的版本）了解哪些功能被使用：記錄按了哪些按鈕（例如「開啟設定」、「選擇伺服器」、「切換提醒開關」），以及 App 版本、裝置型號、系統版本、語言與國家。這些資料是彙整統計、不會與你的身分連結、不用於廣告或跨 App 追蹤，由 Google 依 [Firebase 隱私條款](https://firebase.google.com/support/privacy) 處理。

## 網路請求

為了顯示即時資料，本 App 會向兩個來源發出請求：

- **開發者自己的伺服器**（開發者營運的 Google Cloud／Firebase 專案）：地表暗黑進度。該伺服器每分鐘向 **d2emu.com** 取一次資料再提供給所有使用者，你的裝置不會直接連到 d2emu.com。對開發者伺服器的請求只包含要查詢的資料。
- 第三方社群網站 **d2runewizard.com**：恐怖地帶與預告開地表。請求只包含要查詢的資料，以及該網站公平使用政策要求的固定開發者聯絡方式與 App 識別。

不包含任何關於你或你裝置的資訊（一般 HTTPS 請求本身會帶的 IP 位址除外，各伺服器營運者可能依其隱私權政策記錄）。

## 儲存在你裝置上的資料

你的偏好設定（追蹤伺服器、喜愛的恐怖地帶、提醒開關）只存在你的裝置上，刪除 App 即一併刪除。

## 通知

若你允許通知，預告開地表的提醒由 App 在你的裝置上排程本機通知。

地表暗黑進度變化與恐怖地帶換區則透過 Apple 推播服務（APNs）與 Google Firebase Cloud Messaging 以**推播通知**送達。為此 App 會向 Firebase 註冊一個匿名的推播權杖，並訂閱只描述你設定的「主題」（例如追蹤的伺服器、喜愛的恐怖地帶、App 語言）。該權杖是隨機產生的裝置識別碼，不與你的身分連結，除了送達這些通知外不作其他用途。在設定中關閉提醒開關即取消訂閱；刪除 App 後權杖失效。

## 兒童

本 App 不會收集任何人的資訊，包括兒童。

## 聯絡

briat2004@icloud.com

<!-- 線上版本：https://github.com/briat2004/ClockForD2/blob/main/PRIVACY.md（repo ~/ClockForD2，改了這份要同步 PRIVACY.md 並 push） -->
