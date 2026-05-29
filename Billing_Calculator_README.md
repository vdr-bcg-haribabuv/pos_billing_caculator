# Billing Calculator Pro Suite

## Overview

Billing Calculator Pro is a browser-based Point of Sale (POS) billing application built entirely with HTML, CSS, and JavaScript.

No installation, server, database, internet connection, or third-party software is required.

All data is stored locally in the browser using Local Storage.

---

## Included Files

### 1. index-patched.html
Main application launcher.

Provides navigation between:
- Simple Billing
- Qty & Discount Billing
- Bill History
- Configuration

Open this file first.

---

### 2. addition-pro-patched.html
Simple Billing module.

Features:
- Quick amount entry
- Running total
- Edit amount by double-click
- Remove items
- Thermal receipt printing
- Bill history integration
- View old bills
- Re-print old bills

Best for:
- Grocery shops
- Small retail stores
- Fast billing counters

---

### 3. calculator-pro-patched.html
Quantity and Discount Billing module.

Features:
- Price
- Quantity
- Discount %
- Automatic calculations
- Edit values by double-click
- Remove line items
- Thermal receipt printing
- Bill history integration
- View old bills
- Re-print old bills

Best for:
- General stores
- Hardware stores
- Wholesale counters
- Retail shops

---

### 4. bills-patched.html
Bill History module.

Features:
- View all bills
- Search by Bill Number
- Search by Date
- Today's Bills filter
- View Bill
- Re-print Bill
- Show overall sales total
- Clear history

---

### 5. config-patched.html
Shop Configuration.

Stores:
- Shop Name
- Shop Address

Configuration is automatically used on all printed receipts.

---

## Installation

### Option 1 – Local Computer

Place all files inside the same folder:

index-patched.html
addition-pro-patched.html
calculator-pro-patched.html
bills-patched.html
config-patched.html

Open:

index-patched.html

in Chrome, Edge, Firefox, or Brave.

---

### Option 2 – USB Drive

Copy the complete folder to a USB drive.

The application will continue to work on any Windows PC with a browser.

---

### Option 3 – Internal Office Network

Place files on:
- Shared Drive
- Internal Server
- Intranet Site

Users can open the application directly from the shared location.

---

## First Time Setup

1. Open Configuration.
2. Enter Shop Name.
3. Enter Shop Address.
4. Click Save Configuration.

All future receipts will use these details.

---

## Bill History Workflow

### Saving Bills

Bills are automatically saved when printed.

Saved information:
- Bill Number
- Bill Date
- Line Items
- Total Amount
- Bill Type

---

### Viewing Old Bills

Bill History
→ View

The original bill is restored.

---

### Re-printing Old Bills

Bill History
→ Re-print

The original bill is restored and printed.

---

## Browser Storage

The application uses:

Local Storage

No external database is required.

Data remains available until:
- Browser data is cleared
- Site data is deleted
- User clicks Clear History

---

## Backup Recommendation

Because data is stored locally:

Recommended:
- Export browser profile backups
- Periodically print reports
- Keep a copy of the application folder

For business-critical usage, migrate bill storage to:
- SQLite
- MySQL
- PostgreSQL
- Cloud Database

---

## Printing

Supported:
- Thermal Printers
- USB Printers
- Network Printers
- Standard A4 Printers

Recommended Settings:

Paper Width:
72mm or 80mm

Margins:
None

Scale:
100%

Headers & Footers:
Disabled

---

## Keyboard Shortcuts

Simple Billing:
- Enter → Add Amount

Qty & Discount Billing:
- Enter → Move to next field
- Enter on Discount → Add Item

Global:
- Spacebar → Print Bill

---

## Data Storage Keys

Shop Configuration:
- shopName
- shopAddress

Bill Storage:
- bills

Temporary View Mode:
- viewBillIndex

---

## Limitations

Current Version:
- Single device storage
- No cloud sync
- No user login
- No GST calculations
- No inventory tracking
- No stock management

---

## Recommended Future Enhancements

- GST Billing
- Inventory Management
- Product Catalog
- Barcode Scanning
- Customer Management
- Daily Reports
- Excel Export
- PDF Export
- Cloud Backup
- Multi-user Login
- Multi-store Support

---

## Troubleshooting

### Bills Not Appearing

Check:
- Browser Local Storage enabled
- Same browser being used
- History not cleared

---

### Print Layout Issues

Use:
- Chrome
- Edge

Set:
- Scale = 100%
- Margins = None

---

### Configuration Not Showing

Open:
Configuration

Save details again.

Refresh the page.

---

## Version

Billing Calculator Pro
Patched Release

Includes:
- Bill History Fix
- View Bill Fix
- Re-print Bill Fix
- Original Bill Restoration Support

