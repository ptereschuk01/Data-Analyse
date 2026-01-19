# Data Cleaning Phases (Detailed)

## 🟦 Data Collection & Overview
- [CSV-Import / CSV Import](#csv-import--csv-import)  
- [Excel-Import / Excel Import](#excel-import--excel-import)  
- [CSV/Excel/SQL/API-Import / CSV/Excel/SQL/API Import](#csvexcel-sql-api-import--csvexcel-sql-api-import)  
- [Typprüfung / Check Data Types](#typprüfung--check-data-types)  
- [Größenprüfung / Check Dimensions](#größenprüfung--check-dimensions)  
- [Statistikprüfung / Check Statistics](#statistikprüfung--check-statistics)  

## 🟦 Missing Values Handling
- [Löschen von Zeilen/Spalten mit fehlenden Werten / Remove Rows/Columns with Missing Values](#löschen-von-zeilenspalten-mit-fehlenden-werten--remove-rowscolumns-with-missing-values)  
- [Auffüllen von fehlenden Werten / Fill Missing Values](#auffüllen-von-fehlenden-werten--fill-missing-values)  
- [Vorhersage fehlender Werte / Predict Missing Values](#vorhersage-fehlender-werte--predict-missing-values)  

## 🟦 Duplicates Removal
- [Überprüfung vollständig identischer Zeilen / Check Fully Duplicate Rows](#überprüfung-vollständig-identischer-zeilen--check-fully-duplicate-rows)  
- [Zusammenführen von Duplikaten / Merge Duplicates](#zusammenführen-von-duplikaten--merge-duplicates)  

## 🟦 Data Type Validation
- [Umwandlung in die benötigten Typen / Convert to Correct Types](#umwandlung-in-die-benötigten-typen--convert-to-correct-types)  
- [Korrektur von Eingabefehlern / Fix Input Errors](#korrektur-von-eingabefehlern--fix-input-errors)  

## 🟦 Anomalies & Outliers
- [Erkennung von Ausreißern / Detect Outliers](#erkennung-von-ausreißern--detect-outliers)  
- [Entfernen oder Anpassen / Remove or Adjust](#entfernen-oder-anpassen--remove-or-adjust)  

## 🟦 Standardization & Normalization
- [Zahlen-Normalisierung / Normalize Numbers](#zahlen-normalisierung--normalize-numbers)  
- [Kategorien-Standardisierung / Standardize Categories](#kategorien-standardisierung--standardize-categories)  
- [Bereinigung von Textdaten / Clean Text Data](#bereinigung-von-textdaten--clean-text-data)  

## 🟦 Feature Engineering
- [Aufteilen von Datumsangaben / Split Dates](#aufteilen-von-datumsangaben--split-dates)  
- [Berechnung neuer Kennzahlen / Calculate New Metrics](#berechnung-neuer-kennzahlen--calculate-new-metrics)  
- [Kodierung kategorialer Variablen / Encode Categorical Variables](#kodierung-kategorialer-variablen--encode-categorical-variables)  

## 🟦 Data Integrity Checks
- [Logische Prüfungen / Logical Checks](#logische-prüfungen--logical-checks)  
- [Prüfung der Schlüssel-Eindeutigkeit / Check Key Uniqueness](#prüfung-der-schlüssel-eindeutigkeit--check-key-uniqueness)  
- [Überprüfung von Wertebereichen / Check Value Ranges](#überprüfung-von-wertebereichen--check-value-ranges)  

## 🟦 Saving Clean Data
- [Speichern in CSV/Excel/SQL / Save to CSV/Excel/SQL](#speichern-in-csv-excel-sql--save-to-csv-excel-sql)  
- [Dokumentation von Änderungen und Reinigungsregeln / Document Changes and Cleaning Rules](#dokumentation-von-änderungen-und-reinigungsregeln--document-changes-and-cleaning-rules)  

---

# Detailed Steps

### CSV-Import / CSV Import
Description and examples of importing CSV files.  

### Excel-Import / Excel Import
Description and examples of importing Excel files.  

### CSV/Excel/SQL/API-Import / CSV/Excel/SQL/API Import
Working with different data sources.  

### Typprüfung / Check Data Types
How to check data types and convert them to the correct types.  

### Größenprüfung / Check Dimensions
How to check the number of rows and columns, data completeness.  

### Statistikprüfung / Check Statistics
Using `describe()` and other methods to understand data distribution.  

### Löschen von Zeilen/Spalten mit fehlenden Werten / Remove Rows/Columns with Missing Values
Description of removing missing values.  

### Auffüllen von fehlenden Werten / Fill Missing Values
Methods for filling with mean, median, or mode.  

### Vorhersage fehlender Werte / Predict Missing Values
Using models to fill missing values.  

### Überprüfung vollständig identischer Zeilen / Check Fully Duplicate Rows
Detecting duplicate rows.  

### Zusammenführen von Duplikaten / Merge Duplicates
How to merge rows with duplicate keys.  

### Umwandlung in die benötigten Typen / Convert to Correct Types
Converting data to `int`, `float`, `str`, `datetime`.  

### Korrektur von Eingabefehlern / Fix Input Errors
Replacing incorrect values or typos.  

### Erkennung von Ausreißern / Detect Outliers
Methods: IQR, z-score for detecting anomalies.  

### Entfernen oder Anpassen / Remove or Adjust
Removing outliers or replacing them with median/mode.  

### Zahlen-Normalisierung / Normalize Numbers
Min-max scaling, z-score for numerical features.  

### Kategorien-Standardisierung / Standardize Categories
Unifying categorical values, fixing typos.  

### Bereinigung von Textdaten / Clean Text Data
Removing extra spaces, converting to lowercase.  

### Aufteilen von Datumsangaben / Split Dates
Creating new features: day, month, year.  

### Berechnung neuer Kennzahlen / Calculate New Metrics
Difference, mean, sum, and other derived features.  

### Kodierung kategorialer Variablen / Encode Categorical Variables
One-hot encoding, label encoding.  

### Logische Prüfungen / Logical Checks
Checking data logic, e.g., start_date ≤ end_date.  

### Prüfung der Schlüssel-Eindeutigkeit / Check Key Uniqueness
Ensuring unique identifiers.  

### Überprüfung von Wertebereichen / Check Value Ranges
Validating correct minimum and maximum values.  

### Speichern in CSV/Excel/SQL / Save to CSV/Excel/SQL
Export cleaned data for further analysis.  

### Dokumentation von Änderungen und Reinigungsregeln / Document Changes and Cleaning Rules
Creating logs, describing rules and changes.
