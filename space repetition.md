 ```dataview
 TABLE tags, file.cday AS Created
 FROM "03 permanent (core)"
 WHERE type = "permanent" AND review <= date(today)
 SORT review ASC
 ```
