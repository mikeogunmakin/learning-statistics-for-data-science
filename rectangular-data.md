# 📐 Rectangular Data

## 🧾 What is Rectangular Data?
- A **two-dimensional** structure:
  - **Rows** = Records or cases
  - **Columns** = Features or variables
- Often referred to as:
  - **DataFrame** in Python (pandas)
  - **data.frame** in R
- Similar to a **spreadsheet** or **database table**

## 🔄 Transforming Data into Rectangular Format
- **Unstructured data** (like text) must be processed into features
- **Relational databases**: Data from multiple tables needs to be extracted and **flattened** into a single table for analysis/modeling

## 🆔 Indexes in Rectangular Data
### Python (pandas):
- Default: automatic integer index
- Supports:
  - 🪜 **Multilevel/hierarchical indexes**
  - 🧠 More efficient operations

### R:
- Default: implicit integer index based on row order
- Does **not** support custom/multilevel indexes natively
- Workarounds:
  - Use `row.names` for custom keys
  - Use `data.table` or `dplyr` packages for:
    - 💨 Speed improvements
    - 📊 Multilevel indexing

## 🧰 Other Data Structures in Data Science

### ⏱️ Time Series Data
- Successive measurements over time
- Key for:
  - Forecasting
  - IoT data analysis

### 🗺️ Spatial Data
- Used in:
  - Mapping
  - Location analytics
- Two views:
  - **Object-based** (e.g., a house with coordinates)
  - **Field-based** (e.g., pixel values like brightness)

### 🌐 Graph/Network Data
- Represents relationships:
  - Social networks (e.g., Facebook)
  - Physical networks (e.g., distribution hubs, roads)
- Used in:
  - 📦 Recommender systems
  - 🔁 Network optimization

## 🎯 Key Takeaway
While many data structures exist, **rectangular data** is the core format used for most **predictive modelling** tasks in data science.
