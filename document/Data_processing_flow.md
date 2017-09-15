# Data processing flow

### Input
  - csv
  - JSON
  - XML
  - Azure
  - character code

### Missing data
  - numerical
    - average 0,1 : 付け足す  
    - delete : 消す
      - その部分だけ  
      - その日全部 row
      - その属性全部 column

### Category data （定性的，質的変数）
  - dummy variable
  - e.g.

|大|中|小|
|:--:|:--:|:--:|
|001|010|100|

|TCP|UDP|ICMP|
|:--:|:--:|:--:|
|001|010|100|

### normalization （標準化）
  - [0,1] : [min,max]
    - 最大値がない場合は使えない
    - e.g. 気温
  - z-score = (x:original_data - μ:mean)/σ:s.d:ばらつき

### variable selection

### Machine Learning
