## Propose
Trying to track down acute heart failure patients
1.to understand the characteristic of Audicor(AUDICOR is an acoustic cardiography system that analyses heart sounds to assess cardiac function.) and heart rate variability with or without cardiovascular
2.to see if Audicor and heart rate variability are able to be come the indicator of disease risk


## :one: Data combination
combine all the data sets


## :two: Data Cleaning and Imputation
Collected data from acute heart failure patients who returns to the hospital for three times. Some patients are not able to make it which cause missing values.
Three kinds of imputations : 1.  Median 2. The information of last visit of hospital 3. random forest


## :three: Classification
Divide Audicor and HRV into two groups, which is normal and abnormal.
We turn these data into dummy variable in order to do mean analysis.


## :four: Mean Analysis
The mean analysis of Audicor and HRV
It includes Physiological parameters, Historical medical records, Echocardiography, Audicor, HRV


## :five: Event Analysis
Under four situations : death in hospital, first hospitalization, death in hospital or first hospitalization, first hospital death plus stroke
It includes Physiological parameters, Historical medical records, Echocardiography, Audicor, HRV


## :six: Survival Analysis(Cox Regression)
Under four situations : death in hospital, first hospitalization, death in hospital or first hospitalization, first hospital death plus stroke
It includes Physiological parameters, Historical medical records, Echocardiography, Audicor, HRV

## all of the result are captured in excel
with AF
[https://docs.google.com/spreadsheets/d/1J0LDHroh-Dx8b8-ZcUV06Zd1lzoUg4zj/edit?usp=sharing&ouid=113089451230441310076&rtpof=true&sd=true]

without AF
[https://docs.google.com/spreadsheets/d/1r3xsQ9CGlGwo4h-A81wmB4OgfS-aOnmN/edit?usp=sharing&ouid=113089451230441310076&rtpof=true&sd=true]
