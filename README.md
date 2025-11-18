# 📦 Logistics Movement Report – Crystal Reports & SQL Server

This project demonstrates a complete end-to-end reporting workflow using **SAP Crystal Reports** and **Microsoft SQL Server**, designed to showcase advanced reporting, data modeling, and visualization capabilities for logistics and warehouse operations. 

It was created as a portfolio piece for roles involving ERP systems, reporting, and operational analytics.

## 🚀 Project Overview

The solution simulates a real-world logistics environment by generating detailed movement records. The report provides critical insights for warehouse management, including:

* **Movement Types:** Product transfers, incoming/outgoing shipments, and warehouse-to-warehouse relocations.
* **Metrics:** Total number of movements and total quantity moved.
* **Breakdowns:** Data grouped by warehouse and movement type (IN/OUT).
* **Visual Aids:** Conditional highlights for high-volume operations and color-coded types.
* **Traceability:** Includes metadata such as creator, notes, and timestamps.

The project demonstrates practical Crystal Reports experience with a focus on clear visual structure, reporting accuracy, and operational usability.

## 🛠️ Technologies Used

* **Reporting:** SAP Crystal Reports (2025 Edition)
* **Database:** Microsoft SQL Server (2022)
* **Languages:** SQL (DDL, DML, aggregations)
* **Features:** Crystal Reports formula fields, Conditional formatting, Grouping & Summaries

## 🗄️ Database Schema

The project uses a single table designed specifically for logistics reporting.

**Table:** `Movements`

```sql
Movements
---------
MovementID (PK)             -- Primary Key
DocumentNumber              -- Reference Doc
ProductID                   -- Item Identifier
Quantity                    -- Amount moved
OriginWarehouseID           -- Source
DestinationWarehouseID      -- Target
MovementType                -- IN / OUT / TRANSFER
MovementDate                -- Timestamp
CreatedBy                   -- User
Notes                       -- Optional remarks

```
