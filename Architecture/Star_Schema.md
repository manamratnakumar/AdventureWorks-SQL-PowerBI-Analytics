Star Schema

The warehouse follows the Star Schema model to improve reporting performance.

                DimCustomer
                     │
                     │
DimDate ─── FactSales ─── DimProduct
                     │
                     │
              DimTerritory
                     │
               FactReturns


               
Benefits:

Faster queries

Simple relationships

Better Power BI performance

Easier maintenance
