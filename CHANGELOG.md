# Change Log
##### 1.2.3
- Fix projection bug
---
##### 1.2.2
- Projection now supports multiple of same field without alias
---
##### 1.2.1
- Array items have full filtering range through the `$mathElem` operator
- Change log added
---
### 1.2.0
- Oprerator selection changed to a shorter format: `name: { EQ: "John" }`
  -  Old format deprecated
---
##### 1.1.1
-  Fix omition of zeros in update `$set` fields
---
### 1.1.0
- Changes non-null field of name `_id` to nullable in insert type
- Resolver dependencies now extracted from the GraphQL type definition
- Query and update callbacks combined in `getUpdateResolver`
---
##### 1.0.9
- Add Enum support
- getUpdateResolver: make query callBack redaundent
---
##### 1.0.8
- Fix of bugs in 1.0.7
---
##### 1.0.7
- Common code file created
- Arguments validators added
- Non numberic type filtered from update `$inc`
  - If there are no valid fields, a fictive fieldis added
- Nested objects added to sort
  - If there are no valid fields, a fictive field is added
---
##### 1.0.6
- Package license set to MIT 
- Base fields of `getGraphQLUpdateArgs` are now non-null