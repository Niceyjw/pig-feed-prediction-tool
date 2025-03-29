# pig-feed-prediction-tool
A prediction tool for DE and ME based on the China Feed Database
## 📦 Download All Files

All related files, including:

- Python script (`predict.py`)
- Trained model files (`models/model_de.pkl`, `models/model_me.pkl`)
- Excel-based prediction tool (`predict.xlsm`)

are available via Baidu Netdisk:

🔗 **Download link:** [https://pan.baidu.com/s/1qdqU4CuOtdUYuo_UpPuVgQ](https://pan.baidu.com/s/1qdqU4CuOtdUYuo_UpPuVgQ)  
🔐 **Access code:** `5suq`

---

## 📝 File Descriptions

| File | Description |
|------|-------------|
| `predict.py` | Python script for running predictions |
| `models/model_de.pkl` | Trained model for DE prediction |
| `models/model_me.pkl` | Trained model for ME prediction |
| `predict.xlsm` | Excel-based prediction interface with embedded VBA macros |

---

## 🚀 How to Use

1. Download all files from the Baidu Netdisk link.
2. You can choose to:
   - Run `predict.py` with your own input data (requires Python 3 and necessary packages)
   - Use `predict.xlsm` in Microsoft Excel to input feed composition data and obtain DE/ME predictions

### ⚠️ Important Notes for Excel Tool Users

- The `predict.xlsm` file contains a macro that uses **Shell** to call Python.
- Please make sure to **replace the Python interpreter path in the macro code** with the full path to your own Python environment.  
  For example:
  ```vba
  Shell "C:\Users\yourname\anaconda3\python.exe path\to\predict.py", vbNormalFocus
