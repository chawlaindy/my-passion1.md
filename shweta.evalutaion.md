# What work did you get?
### Task
              1.Create a evaluation sheet for self and others.
              2.Put the formula of average in average column. 
              3.If average column Value is equal to or less than then row colure should be appear red.
# How to write formula ?

#### =SUM(COUNTIF(C4:J4,"Excellent")*5,COUNTIF(C4:J4,"Very good")*4,COUNTIF(C4:J4,"Good")*3,COUNTIF(C4:J4,"Satisfactory")*2,COUNTIF(C4:J4,"Fair")*1,COUNTIF(C4:J4,"Poor")*0)/COUNTA(C4:J4)

# How does the formulae work?

### Excel AVERAGE Function

**Summary**
The Excel AVERAGE function is categorized under Excel Statical functions. It will return the average value of a given series of numbers in Excel.
      
      1.Get the average of a group of numbers
      2.Syntax = SUM(COUNTIF(range,"words1")*num1,COUNTIF(range,"2")*number2)/COUNTA(range)
      3.The AVERAGE function calculates the average of string. To calculate the average, Excel sums all string and divides by the count of numeric values. This behavior can be replicated with the SUM and COUNT functions.

##### Notes 📝:

:black_circle: AVERAGE automatically ignores empty cells and cells with text values(if condition not difine).

:black_circle: AVERAGE includes zero values. Use AVERAGEIF or AVERAGEIFS to ignore zero values.

:black_circle: Arguments can be supplied as constants, ranges, named ranges, or cell references.

:black_circle: AVERAGE can handle up to 255 total arguments.

# Objective of Exercises

#### To learn about excel sheet:bat:
#### To learn about excel sheet:paperclip:
#### To learn about excel formula:cat:
#### To learn about algorithm:dog:

# How it was implemented

## Explanation of ImplementationThe **SUM function** adds values. You can add individual values, cell references or ranges or a mix of all three.
The **COUNTIF function** function is an Excel Statical function. This function helps count the number of cells that contain a number, as well as the number of arguments that contain numbers.
The **COUNTA** function counts cells containing any type of information, including error values and empty text("")
The **AVERAGE function** in Excel calculates the average of a group of numbers. The AVERAGE function ignores logical values, empty cells and cells that contain text.



## Test Results

| **SR-No.** | **TEST CASE** | **TEST OUTCOME** | **EXPECTED OUTCOME** | **STATUS** | **REMARKS** |
| --- | --- | --- | --- | --- | ---- |
| **1** | Type the Excellent in Punctuality column. | The Value 5 successfully print in average column when I put the Excellent in Punctuality column. | After put the Excellent  in Punctuality column successfully printed the value 5 in the average column. | **Passed** | Testing has been passed |
| **2** | Type the Very good in Punctuality column | The Value 4 successfully print in average column when i put the Very good in Punctuality column. | After put the Very good  in Punctuality column successfully printed the value 4 in the average column. | **Passed** | Testing has been passed |
| **3** | Type the Good in Punctuality column. | The Value 3 successfully print in average column when I put the Good in Punctuality column. | After put the Good in Punctuality column successfully printed the value 3 in the average column. | **Passed** | Testing has been passed |
| **4** | Type the Satisfactory in Punctuality column | The Value 2 successfully print in average column when i put the Satisfactory in Punctuality column. | After put the Satisfactory in Punctuality column successfully printed the value 2 in the average column. | **Passed** | Testing has been passed |
| **5** | Type the Fair in Punctuality column. | The Value 1 successfully print in average column when I put the Fair in Punctuality column. | After put the Fair  in Punctuality column successfully printed the value 1 in the average column. | **Passed** | Testing has been passed |
| **6** | Type the Very Poor in Punctuality column | The Value 0 successfully print in average column when i put the Poor in Punctuality column. | After put the Poor  in Punctuality column successfully printed the value 1 in the average column. | **Passed** | Testing has been passed |


## Conclusion
I would like to share that i got to learn a lot of new things in this project. and i would like to learn more further and improve the project.

#### Thank You

