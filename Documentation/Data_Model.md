Data Model

The Power BI model follows a Star Schema.

Dim Customer

        │

Dim Date —— Fact Sales —— Dim Product

        │

   Fact Returns

        │

 Dim Territory

 Relationships

  From          To          
    
 Dim Date        Fact Sales   
 Dim Customer    Fact Sales   
 Dim Product     Fact Sales   
 Dim Territory   Fact Sales   
 Dim Product     Fact Returns 
 Dim Territory   Fact Returns 
