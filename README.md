# GST Billing App

A Flutter-based GST Billing App for TATA Retail Solutions.  
- Automated GST calculation (5%, 12%, 18%, 28% split into CGST/SGST)
- Fast product entry and billing
- Itemized bill with tax breakdown
- Persistent, searchable product and invoice database
- Clean, maintainable code with Provider & Hive

## Getting Started

1. Clone the repo
2. Run `flutter pub get`
3. Run `flutter pub run build_runner build`
4. Run the app: `flutter run`

## Features

- Add products with GST rates
- Auto-calculate CGST, SGST, and total
- Generate and save invoices
- Searchable invoice history

## Tech Stack

- Flutter
- Provider (state management)
- Hive (local database)
