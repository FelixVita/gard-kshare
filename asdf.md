| Complexity   | Source         | What                                                                                    | How        | System        |
|--------------|----------------|-----------------------------------------------------------------------------------------|------------|---------------|
| :red_circle: | GIC            | Tables are extracted to dump files. Files are then moved to Arendal and loaded to stage | Bcp        | Sybase        |
|              |                |                                                                                         | Sqlloader  | Oracle        |
|              | ML             | Tables are extracted to dump files. Files are then moved to Arendal and loaded to stage | Bcp        | Sybase        |
| xx           |                |                                                                                         | Sqlloader  | Oracle        |
|              | LCI            | Tables are extracted to dump files. Files are then moved to Arendal and loaded to stage | Bcp        | Sybase        |
| xx           |                |                                                                                         | Sqlloader  | Oracle        |
| xx           | Agresso        | Data read by DWH                                                                        | Db-link    | Oracle        |
| xx           | FMT            | Apex application(?)                                                                     | Db-link    | Oracle        |
| xx           | Paris          | Tables are copied to stage                                                              | Datapump   | Oracle        |
| xx           | Pool           | Tables are copied to stage                                                              | Datapump   | Oracle        |
| xx           | Cash & Cons.   | Tables are extracted to dump files. Files are then loaded to stage                      | Bcp        | Sqlserver     |
|              |                |                                                                                         | Sqlloader  | Oracle        |
| xx           | Clearwater     | Tables are extracted to dump files. Files are then loaded to stage                      | Bcp        | Sqlserver     |
|              |                |                                                                                         | Sqlloader  | Oracle        |
| xx           | Windward       | Data read from OLTP05 by DWH                                                            | Db-link    | External/Mule |
| xx           | Lloyds         | Data read from OLTP05 by DWH                                                            | Db-link    | External/Mule |
| xx           | Exchange Rates | Data read from OLTP05 by DWH                                                            | Db-link    | External/Mule |
| xx           | Exact          | Data read from OLTP05 by DWH                                                            | Db-link    | External/Mule |
| xx           | Salesforce     | Copied to/from DWH                                                                      | Dataloader | Salesforce    |
|              |                |                                                                                         |            | Tallend       |
| xx           | Mapping System | Data read from OLTP05 by DWH                                                            | Db-link    | Apex          |
| xx           | FMT            | Data read from OLTP05 by DWH                                                            | Db-link    | Apex          |
| Xx           | Risk Driver    | Data read from OLTP05 by DWH                                                            | Db-link    | Apex          |
| xx           | IBNR           | Data read from OLTP05 by DWH                                                            | Db-link    | Apex          |
|              |                |                                                                                         |            | Excel         |
| xx           | Solvency       | Data read from Solvency by DWH                                                          | Db-link    | Oracle        |
| xx           | MDM            | Data read from MDM by DWH                                                               | Db-link    | Oracle        |