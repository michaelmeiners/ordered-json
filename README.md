# ordered-json

=============================
Version 20170927
----------------
Fixes for BigDecimal vs Double for large floats (before it was truncating 1234678.12345678901234 to 1.23456E14)


=============================
Version 20160407
----------------
Created from the open-source Json utility to provide a JSON object LinkedHashMap that preserves the order of the keys when dumping the JSON back to string
