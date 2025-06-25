# 📊 Elements of Structured Data

## 🧩 Sources of Data
- Data comes from multiple sources:  
  - 🌡️ Sensor measurements  
  - 📝 Text  
  - 📷 Images  
  - 📹 Videos  
  - 🖱️ Clickstreams (user interactions with web/apps)  
  - 🌐 IoT (streams of real-time data)

## 📦 Structured vs. Unstructured Data
- **Unstructured**: Raw form like pixels in images, free-form text, etc.
- **Structured**: Organized into tables with **rows** and **columns** (e.g., from databases or studies)

## 🔢 Types of Structured Data

### 1. Numeric Data
- **Continuous**: Values along a continuum (e.g., wind speed, time)  
- **Discrete**: Countable values (e.g., number of events)

### 2. Categorical Data
- **Nominal**: Fixed set of labels (e.g., screen type: plasma, LED)  
- **Binary**: Only two values (e.g., yes/no, 0/1)  
- **Ordinal**: Ordered categories (e.g., ratings: 1 to 5)

## 🧠 Why Data Types Matter
- Determine:
  - 📈 Type of visual display
  - 📊 Analysis technique
  - 🤖 Statistical/predictive models
- Optimise performance in tools like **R** and **Python**

## 🛠️ Engineering Perspective
- Programmers might see categories as text/numbers, but explicit data typing provides benefits:
  - 🔁 **Behavior control**: Influences how models/charts handle data  
  - 💾 **Storage optimisation**: Helps in efficient storage and indexing  
  - ✅ **Validation**: Ensures only allowed values are used (like enums)

## ⚠️ Tool-Specific Notes
- **R**:
  - `read.csv` auto-converts text to factors (can cause issues with unexpected values)
- **Python**:
  - `pandas.read_csv` does **not** auto-convert; use `dtype='category'` manually
  - `sklearn.preprocessing.OrdinalEncoder` supports ordinal data

