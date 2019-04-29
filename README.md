# Adder-Subtractor
implement by neural network

# Report
## Q1. Analyze the results under different number of digits, training epoch, training size ...

### Different number of digits  
- In 100 epoch comparison, data size 36000   

|digits     | loss | accuracy |
|-----|------|------|
|3|0.1451441201945146|0.95096875|
|4|0.5435593464533488|0.8006050003369649|
|5|0.8493591320435206|0.690370833826065|

---
### Different training epoch  
- Data size 36000

|epoch|loss|accuracy|
|-----|-----|-----|
|100|0.09084687401056289|0.9685291666666667|
|200|0.059655092824871345|0.9806083333333333|
|300|0.05813017793592686|0.98245|
|400|0.05831938024403838|0.9826479166666666|
|500|0.05609151270463287|0.9845333333333334|

---
### Different training size    
- In 100 epoch comparison  

|training size|loss|accuracy|
|-----|-----|-----|
|36000|0.0976901263092955|0.96611875|
|18000|0.3865795685807864|0.85424375|
|9000|1.160702965593338|0.56805|

---
### Different training batch size  
- Data size 36000

|batch size|loss|accuracy|
|-----|-----|-----|
|128|0.2030707090501984|0.94389375|
|256|0.09084687401056289|0.9685291666666667|
|512|0.34124497500658035|0.8817395833333334|
|1024|0.927651391617457|0.6435854166666667|


## Q2. Can we apply the same training approach for multiplication?  

 - By experiment, it can not apply same training approach on it.

|Layer number|loss|accuracy|
|-----|-----|-----|
|1|0.7557860101699829|0.7010041667461395|
|2|0.6974024806499481|0.7185916664600372|
|3|0.6423751524686814|0.736104166650772|
