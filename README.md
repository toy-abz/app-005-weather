# Day05 — 天気予報アプリ（最小機能版） / Weather App (Minimal Version)

都市名を入力すると、現在の **天気** と **気温（℃）** を表示するシンプルなWebアプリです。  
OpenWeatherMap API を利用しています。  

This is a simple web application that displays the **current weather** and **temperature (℃)** for a given city name.  
It uses the OpenWeatherMap API.

---

## 🚀 デモ / Demo
🔗 [GitHub Pages 公開URL](https://toy-abz.github.io/app-005-weather/)  
*(公開後にリンクが有効になります / The link will be available after deployment.)*

---

## 🛠️ 使い方 / How to Use
1. 都市名を入力（例: Tokyo, Osaka, Sapporo）  
2. **検索ボタン** または **Enterキー** で実行  
3. 結果がカード形式で表示されます  

1. Enter a city name (e.g., Tokyo, Osaka, Sapporo).  
2. Press the **Search button** or **Enter key**.  
3. The result will be displayed as a card.

---

## 🔑 APIキー設定 / API Key Setup
このアプリは OpenWeatherMap の APIキーが必要です。  

This app requires an API key from OpenWeatherMap.

1. [OpenWeatherMap](https://openweathermap.org/) で無料アカウントを作成  
2. **My API Keys** ページからキーをコピー  
3. `index.html` 内の以下を編集  

```js
const API_KEY = "YOUR_API_KEY_HERE"; // ← ここを書き換える
