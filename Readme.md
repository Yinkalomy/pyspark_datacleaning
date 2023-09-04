## Initial Schema

root
 |-- ageofparticipant: long (nullable = true)
 |-- clinician: struct (nullable = true)
 |    |-- branch: string (nullable = true)
 |    |-- name: string (nullable = true)
 |    |-- role: string (nullable = true)
 |-- drug_used: string (nullable = true)
 |-- experimentenddate: string (nullable = true)
 |-- experimentstartdate: string (nullable = true)
 |-- noofhourspassedatfirstreaction: long (nullable = true)
 |-- result: struct (nullable = true)
 |    |-- conclusion: string (nullable = true)
 |    |-- sideeffectsonparticipant: string (nullable = true)


## Final Schema

root
 |-- ageofparticipant: long (nullable = true)
 |-- branch: string (nullable = true)
 |-- name: string (nullable = true)
 |-- role: string (nullable = true)
 |-- drug_used: string (nullable = true)
 |-- experimentenddate: string (nullable = true)
 |-- experimentstartdate: string (nullable = true)
 |-- noofhourspassedatfirstreaction: long (nullable = true)
 |-- conclusion: string (nullable = true)
 |-- sideeffectsonparticipant: string (nullable = true)