# **DuckDB Geospatial Analysis Project**

#### **Project Overview**
This repository, **DuckDB Geospatial Analysis Project**, demonstrates how to handle massive datasets efficiently using **Python** and **DuckDB**. The project focuses on analyzing geospatial data using real-world datasets with over **2 billion records**, showcasing the power of in-memory SQL analytics.

By following this project, you will:

- Learn to process **large-scale datasets** with DuckDB’s in-memory database.  
- Perform advanced **geospatial analysis** using SQL.  
- Explore how to work with **cloud-stored datasets** in formats like GeoParquet and FlatGeobuf.

---

#### **Key Features**
1. **In-Memory Processing with DuckDB**  
   Analyze datasets of up to **140 million records** in a lightweight, scalable setup.  

2. **Cloud Integration**  
   Directly access datasets stored in the cloud, including public data from **Google Open Buildings** and **Microsoft Building Footprints**.

3. **Geospatial Analysis**  
   Utilize geospatial extensions to perform:  
   - Intersections and comparisons of datasets.  
   - Statistical analysis and insights.  
   - Exports to geospatial file formats such as **FlatGeobuf**.

4. **No Database Installation**  
   Run the entire project in-memory without installing external database systems.

---

#### **Dataset Details**
- **Google Open Buildings V3**  
- **Microsoft Building Footprints**

These datasets provide geospatial information for billions of buildings worldwide. For this project, a subset of **140 million records** is extracted for analysis.

---

#### **Repository Structure**
1. `geospatial_analysis_duckdb.ipynb`: The complete Jupyter Notebook for the project workflow.  
2. `requirements.txt`: A list of required Python packages.  
3. `boundaries.geojson`: A GeoJSON file defining the **Area of Interest (AOI)** for analysis.  

---

#### **Setup Instructions**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Anello92/duckdb-project.git
   cd duckdb-project
   ```

2. **Install Dependencies**
   Use `pip` to install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**
   Launch the notebook in your local environment:
   ```bash
   jupyter notebook geospatial_analysis_duckdb.ipynb
   ```

4. **Run in Google Colab (Optional)**  
   If your local machine has limited memory, upload the project files to **Google Colab** for execution.

---

#### **Usage Workflow**
- **Step 1**: Install and enable DuckDB geospatial extensions (`httpfs` and `spatial`).  
- **Step 2**: Load geospatial datasets directly from the cloud (AWS S3).  
- **Step 3**: Execute SQL queries to analyze geospatial data and generate insights.  
- **Step 4**: Export results in geospatial formats (e.g., FlatGeobuf).

---

#### **Requirements**
Install the following dependencies from `requirements.txt`:
- `duckdb`
- `geopandas`
- `pyarrow`

Installation command:
```bash
pip install -r requirements.txt
```

---

#### **Highlights**
- Process massive geospatial datasets using **SQL**.  
- Achieve high performance with DuckDB’s in-memory engine.  
- Avoid complex infrastructure setups—everything is self-contained.

---

#### **Credits**
- **Dataset Sources**:  
  [Google Open Buildings](https://sites.research.google/open-buildings/#download)  
  [Microsoft Building Footprints](https://beta.source.coop/repositories/vida/google-microsoft-open-buildings/description)

Let me know if there’s anything else you’d like to tweak or refine!
