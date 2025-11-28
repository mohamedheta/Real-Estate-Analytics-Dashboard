# Data Model Documentation

## Main Tables
- Properties  
- Sales  
- Clients  
- Agents  
- Visits  
- Calendar  

## Relationships
- Properties[PropertyID] 1—* Sales[PropertyID]
- Clients[ClientID] 1—* Sales[ClientID]
- Agents[AgentID] 1—* Sales[AgentID]
- Calendar[Date] 1—* Sales[SaleDate]

A PNG version of the model can be added here later.
