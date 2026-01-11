
---

## 🚀 Welcome to this dbt Project

This repository contains a **dbt (data build tool) project** designed to transform raw data into **analytics-ready models** following best practices in **analytics engineering**.

The project leverages **modular SQL models, testing, and documentation** to build reliable and scalable data transformations.

---

## 🛠️ Getting Started

Make sure dbt is installed and your profile is correctly configured.

Run the following commands to get started:

```bash
dbt debug
dbt run
dbt test
```

---

## 📂 Project Structure

* **models/** – SQL models organized by layer (bronze / silver / gold)
* **tests/** – Data quality and schema tests
* **snapshots/** – Slowly changing dimensions (SCD)
* **macros/** – Reusable SQL logic
* **seeds/** – Static reference data (CSV)
* **docs/** – Auto-generated documentation

---

## 🧪 Testing & Data Quality

This project includes:

* Schema tests (not null, unique, accepted values)
* Referential integrity tests
* Custom dbt tests for business logic validation

Run all tests with:

```bash
dbt test
```

---

## 📊 Data Modeling Approach

* Raw data ingested into **Bronze layer**
* Cleaned and standardized into **Silver layer**
* Analytics-ready **Star Schema** in the **Gold layer**
* Supports **One Big Table** and **Dimensional Modeling**

---

## 📘 Resources

* 📚 **dbt Documentation**: [https://docs.getdbt.com](https://docs.getdbt.com)

