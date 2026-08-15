# Solvil 熱割れリスク計算 PWA

Android版ChromeからインストールできるPWA基盤です。トップ画面、インストール導線、Service Worker、オフライン表示のみを実装し、未確定の計算式・係数は実装していません。

## 起動と確認

```powershell
npm run dev
npm run check
```

`http://127.0.0.1:4173` を開きます。本番はHTTPSで配信し、Android版Chromeの画面内ボタンまたはメニューの「アプリをインストール」を選択します。
