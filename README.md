📊 Excel Sales Automation Toolkit

Sales report automation for small businesses: transforms a messy spreadsheet (dates in different formats, inconsistent names, duplicates, missing data) into a professional report with metrics and charts generated with formulas, not fixed values — so the file recalculates automatically whenever the business adds new sales.

The Problem

Many small businesses — such as online cosmetics stores, boutiques, or family-owned businesses — manage their sales manually in Excel: each salesperson enters data differently, dates are recorded in different formats, customer and product names vary in capitalization and spacing, and calculating basic metrics (What is my best-selling product? How much did I sell this month?) means hours of manual work every time.

This project automates that process from start to finish.

What It Does
Step	Description
1. Cleaning	Normalizes text, standardizes date formats, removes duplicates and empty rows, and recalculates totals from scratch (never relies on an existing total)
2. Summary	Calculates total sales, average order value, units sold, and best-selling product — all using Excel formulas (SUM, SUMIF, INDEX/MATCH)
3. Report	Generates a professionally formatted .xlsx file with a sales-by-product table and an automatic bar chart
Before / After

Before (data/before/ventas_desordenadas.xlsx): 153 rows with mixed date formats (2026-06-01, 01/06/2026, 01-06-2026), names such as "serum vitamina c" and "SERUM VITAMINA C" treated as different products, missing quantities, and duplicate rows.

After (data/after/reporte_automatizado.xlsx): 140 clean rows, a summary sheet with live metrics, and a sales-by-product chart.

The data is fictional and was generated for this project — it is not real business data.
