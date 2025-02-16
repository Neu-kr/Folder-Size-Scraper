# 📂 Folder Size Scraper

**A simple Python tool to calculate folder sizes and export results to an Excel file.**

## ✨ Features

- **📊 Automatic Folder Size Calculation:** Recursively calculates the total size of each subfolder in the specified directory.
- **📄 Excel Export:** Saves folder name, size (in KB, MB, GB), and exact byte count to `output.xlsx`.
- **🔄 Data Persistence:** Appends new results to an existing `output.xlsx` file without overwriting previous data.
- **💻 Easy-to-Use CLI:** Enter the target folder path when prompted.

## 🛠 Requirements

- Python 3.x
- [openpyxl](https://pypi.org/project/openpyxl/)

## 🚀 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/folder-size-scraper.git
cd folder-size-scraper
```

### 2️⃣ Install Dependencies

```bash
pip install openpyxl
```

## 📌 Usage

Run the script using:

```bash
python script.py
```

When prompted, enter the full path of the folder you want to scan. The script will then:

1. Calculate the total size of each subfolder.
2. Save the results to `output.xlsx` in the same directory as the script.
3. Append new data to the existing file if it already exists.


---

# 📂 フォルダサイズスクレイパー（日本語版）

**フォルダのサイズを計算し、ExcelファイルにエクスポートするシンプルなPythonツールです。**

## ✨ 特徴

- **📊 自動フォルダサイズ出力:** 指定されたディレクトリの各サブフォルダの合計サイズを出力。
- **📄 Excelエクスポート:** フォルダ名、サイズ（KB、MB、GB）、および正確なバイト数を `output.xlsx` に保存します。
- **🔄 データ保持:** 既存の `output.xlsx` ファイルに新しい結果を追加し、以前のデータを上書きしません。
- **💻 簡単なCLI:** 指定したフォルダパスを入力するだけで利用可能。

## 🛠 必要環境

- Python 3.x
- [openpyxl](https://pypi.org/project/openpyxl/)

## 🚀 インストール

### 1️⃣ リポジトリをクローン

```bash
git clone https://github.com/yourusername/folder-size-scraper.git
cd folder-size-scraper
```

### 2️⃣ 依存関係をインストール

```bash
pip install openpyxl
```

## 📌 使用方法

スクリプトを実行:

```bash
python script.py
```



