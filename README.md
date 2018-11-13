# Trail2Polyline

## こちらのスクリプトはUnityの位置座標をRhinoのPolylineに変換するものになります。

### 1. Unity側の操作

- TrailExport.csを、位置座標を取得したいオブジェクトにアタッチします。

- 設定項目は、取得する時間間隔(Interval)、取得する時間(ExportTime)です。

- 出力先はプロジェクトフォルダ内に出力されるように設定されいています。

### 2. Python側の操作

- RhinocerosからCsvToPoint.pyを走らせてください。

- csvを選択してください。（複数対応）

- おわり

![image](./image/CsvToPoint.gif)