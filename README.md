# parseCSV lib for Codeigniter.
 
Ref: https://github.com/parsecsv/parsecsv-for-php

```
$csv = new parseCSV();
$csv->auto('sample.csv');
$rows = $csv->data;
foreach ($rows as $row):
  //process data here.
  print_r($row);
endforeach;
```
