Data Warehouse Architecture

The project uses a Star Schema.

               
                  DimCustomer    
          
                        |
                        |
   
  DimDate   ----| FactSales  | DimProduct |
  
                        |
                        |
                 
                 | DimTerritory  |
                 

                        |

                 
                 | FactReturns   |

              

Dimension Tables

DimDate

DimCustomer

DimProduct

DimTerritory

Fact Tables

FactSales

FactReturns
