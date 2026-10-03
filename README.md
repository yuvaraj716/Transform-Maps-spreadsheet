# ServiceNow Data Import & Transformation using Transform Maps

## Project Overview
This project demonstrates end-to-end data ingestion into ServiceNow using Import Sets and Transform Maps. Bulk employee data was uploaded via an Excel spreadsheet, staged, mapped to a custom target table, transformed with duplicate prevention (Coalesce), and visualized using ServiceNow Platform Analytics Dashboards.

## Key Features & Milestones
- **Target Table Creation:** Configured target table `u_employee_test` with fields: Employee ID, Employee Name, Email, Department, and Location.
- **Import Set & Field Mapping:** Built staging table `u_employee_import` and Transform Map `Sample Spreadsheet Import` with 5 field mappings.
- **Coalesce Implementation:** Enabled Coalesce on `u_employee_id` to prevent duplicate record insertion and handle updates automatically.
- **Reporting & Dashboards:** Designed interactive reports (Department Pie Chart, Location Bar Chart, Employee List) assembled on an **Employee Analytics Dashboard**.

## Technologies Used
- ServiceNow (Next Experience / Platform Analytics)
- System Import Sets & Transform Maps
- Excel (.xlsx) Data Ingestion

## Project Structure
- `Sample Spreadsheet.xlsx` - Input spreadsheet used for staging and import.
- `Screenshots/` - Visual evidence of import runs, transform mapping, coalesce execution, and dashboard visuals.
