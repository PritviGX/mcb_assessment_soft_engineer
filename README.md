# MCB Assessment software engineer
Technical Assessment for Software Engineer Role
## **Overview**
This repository contains SQL scripts for database migration, reporting, and analytics for BCM Ltd.

## **Tools Used**
- **Database:** Oracle Database
- **SQL Tool:** SQL Developer
- **Version Control:** GitHub

## **Assignment Breakdown**
### **1. Database Schema**
The database was normalized into the following tables:
- `Suppliers`
- `Orders`
- `Invoices`

### **2. Scripts (Stored Procedures)**
| Script | Description |
|--------|-------------|
| `1.DB_Prequisite.sql` | Creates `XXBCM_ORDER_MGT` table and insert the data |
| `2.Create_Necessary_Tables_AND_ID_SEQUENCE.sql` | Create normalized tables and sequencing ids |
| `3.Migrate_Data` | Transfers data from `XXBCM_ORDER_MGT` to suppliers, orders and invoices respectively making sure no redundant is inserted on multiple execution |
| `4.Get_Order_Summary_Report` | Generates order summary report |
| `5.GET_SECOND_HIGHEST_ORDER_DETAILS` | Retrieves second highest order total |
| `6.GET_SUPPLIER_ORDER_SUMMARY` | Lists suppliers with their total orders |

## **View SQL files and OUTPUT PDF**
- Download and extract ZIP file MCB SQL Assessment_ Pritvi Gopee
- Go to Answers where you will find the scripts and PDF doc with tools used and outputs
