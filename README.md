## 🔎 Using VLOOKUP in Excel

### 📌 Purpose
The `VLOOKUP` function was used to retrieve and match data from another table based on a common identifier (such as Product ID or Customer ID).

This helped in:
- Merging related datasets
- Filling missing information
- Enriching the sales dataset with additional details

---

## 🧮 VLOOKUP Formula Structure

```excel
=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])
```

### 🔹 Parameters Explained

- **lookup_value** → The value to search for (e.g., Product ID)
- **table_array** → The range containing the data table
- **col_index_num** → The column number to return data from
- **range_lookup** → FALSE for exact match, TRUE for approximate match

---

## 💡 Example Used in This Project

```excel
=VLOOKUP(A2, Sheet2!A:B, 2, FALSE)
```

### ✅ What This Does:
- Looks for the value in cell **A2**
- Searches in **Sheet2 column A**
- Returns the matching value from **column 2**
- Uses **FALSE** to ensure an exact match

---

## 🎯 Why VLOOKUP Was Important in This Project

✔️ Matched product IDs with product names  
✔️ Linked customer data to sales transactions  
✔️ Reduced manual data entry  
✔️ Improved dataset accuracy  

---

📊 VLOOKUP played a key role in transforming raw sales data into a structured and analysis-ready format.
