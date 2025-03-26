# MCP Risk Calculator

A web application for calculating supplier risks based on the Model Context Protocol (MCP) methodology.

## Features

- Calculate risk scores (1-5 scale) for suppliers based on their country location
- Process individual suppliers or bulk supplier lists
- Support for country identification via name, ISO2, or ISO3 codes
- Input via file or direct text
- Detailed risk breakdown including all 12 risk factors
- CSV output support

## Risk Factors

The system evaluates the following 12 static risks:
1. GHG Emissions
2. Trade Unions
3. Wages
4. Working Time
5. Gender-Based Violence
6. Hazardous Chemicals
7. Bribery and Corruption
8. Water
9. Health and Safety
10. Forced Labor
11. Child Labor
12. Biodiversity

## Deployment

This application is deployed on Vercel. To deploy locally:

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

## Input Format

The supplier data should be in CSV format with two columns:
```
supplier_name,country
```

Example:
```
Acme Corp,United States of America
Tech Ltd,GB
Supplier C,USA
```

## License

MIT License 