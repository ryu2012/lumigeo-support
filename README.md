# LumiGeo

<p align="center">
  <img src="icon.png" width="128" height="128" alt="LumiGeo App Icon" style="border-radius: 24px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">
</p>

<p align="center">
  <strong>Panasonic LUMIX カメラ GPS ジオタグ自動同期 iOS アプリケーション</strong><br>
  <em>Automatic Background GPS Geotagging & BLE Sync for Panasonic LUMIX Cameras</em>
</p>

<p align="center">
  <a href="https://ryu2012.github.io/lumigeo-support/privacy.html">Privacy Policy</a> •
  <a href="https://github.com/ryu2012/lumigeo-support/issues">Issues / Feedback</a>
</p>

<p align="center">
  <a href="altstore://source?url=https://ryu2012.github.io/lumigeo-support/apps.json">
    <img src="assets/download-badge-altstore-dark.png" height="44" alt="Download on AltStore">
  </a>
  &nbsp;&nbsp;
  <a href="sidestore://source?url=https://ryu2012.github.io/lumigeo-support/apps.json">
    <img src="assets/add-source-to-sidestore.png" height="44" alt="Add Source to SideStore">
  </a>
</p>

---

## 🇯🇵 日本語 (Japanese)

### 概要
**LumiGeo（ルミジオ）** は、Panasonic LUMIX カメラをお使いのフォトグラファーのための、常時 Bluetooth Low Energy (BLE) バックグラウンド接続・高精度 GPS 位置情報自動同期 iOS アプリケーションです。

iPhone をポケットやバッグに入れたまま、カメラの電源を入れるだけで自動的に再接続し、撮影写真へリアルタイムに正確な位置情報を記録します。

### インストール方法 (AltStore / SideStore)
1. iOS 端末から上記バッジをタップするか、AltStore / SideStore の「Sources」タブを開いて「＋」ボタンから以下の URL を追加します：
   ```
   https://ryu2012.github.io/lumigeo-support/apps.json
   ```
2. ソース一覧に追加された「LumiGeo」を選択してインストールしてください。

### 主な特徴
- **自動再接続 & バックグラウンド同期**:
  iOS のバックグラウンド復帰機能を活用。iPhone がスリープ状態でも、カメラの電源 ON を検知して自動で接続・位置情報送信を開始します。
- **高精度リアルタイム GPS**:
  撮影位置のズレを防ぐため、移動速度や測位精度に応じた最適な更新頻度でカメラへジオタグを送信します。
- **高いプライバシー保護**:
  位置情報やカメラ識別情報は、iPhone とカメラの間だけで完結します。外部サーバーへの送信や収集は一切行いません。

### 動作確認済み機種
- **LUMIX Sync 方式**: Panasonic LUMIX S1（ペアリング時 Wi-Fi 認証 ➡ BLE 同期）
- **LUMIX Lab 方式**: Panasonic LUMIX S9 / LUMIX L10（BLE 直接同期）

---

## 🇺🇸 English

### Overview
**LumiGeo** is an iOS utility app tailored for photographers using Panasonic LUMIX cameras, offering seamless Bluetooth Low Energy (BLE) background reconnection and precise real-time GPS location synchronization.

Keep your iPhone in your pocket or camera bag; simply turn on your camera, and LumiGeo automatically connects and writes accurate geotags to your photos.

### Installation (AltStore / SideStore)
1. Tap the badge above on your iOS device, or open AltStore / SideStore, navigate to **Sources**, and tap **+** to add this repository:
   ```
   https://ryu2012.github.io/lumigeo-support/apps.json
   ```
2. Locate **LumiGeo** in the sources list and tap Install.

### Key Features
- **Automatic Background Reconnection**:
  Utilizes iOS CoreBluetooth background preservation and restoration. LumiGeo automatically wakes up and resumes GPS sync whenever your camera powers on.
- **Accurate Real-Time Geotagging**:
  Continuously supplies high-precision coordinates with optimal transmission intervals, ensuring every shot captures the exact location.
- **Privacy-First Design**:
  All GPS data and device information stay strictly local between your iPhone and camera. No data is collected, stored remotely, or sent to third-party servers.

### Verified Camera Models
- **LUMIX Sync Protocol**: Panasonic LUMIX S1 (Wi-Fi pairing auth ➡ BLE sync)
- **LUMIX Lab Protocol**: Panasonic LUMIX S9 / LUMIX L10 (Direct BLE sync)

---

## リンク / Links
- **プライバシーポリシー (Privacy Policy)**: [https://ryu2012.github.io/lumigeo-support/privacy.html](https://ryu2012.github.io/lumigeo-support/privacy.html)
- **不具合報告・ご要望・お問い合わせ (Issues & Contact)**: [GitHub Issues](https://github.com/ryu2012/lumigeo-support/issues)

---

### 免責事項 / Disclaimer
*LUMIX および Panasonic は、パナソニックホールディングス株式会社の登録商標または商標です。LumiGeo は独立したサードパーティツールであり、パナソニックと提携、承認、支援されているものではありません。*  
*Panasonic and LUMIX are registered trademarks of Panasonic Holdings Corporation. LumiGeo is an independent third-party tool and is not affiliated with, endorsed, or sponsored by Panasonic.*
