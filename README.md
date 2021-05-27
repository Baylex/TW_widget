# TW TIA Estimators 
As for my work with Transformation Waco, I was asked to create 2 interactive online calculators as it pertains to their Teacher Incentive Allotment (TIA) designations.

## What is the Teacher Incentive Allotment?
The TIA is an optional funding source to help increase teacher salaries to six-figures in Texas through earning additional stipends.  The ideal teacher prioritizes teaching in high need subjects and rural campuses.   
[Source: Texas Education Agency](https://tea.texas.gov/texas-educators/educator-initiatives-and-performance/educator-initiatives/teacher-incentive-allotment)

## JavaScript Initial Plan
My initial attempt was to write the calculator using only JavaScript.  I gathered some starter code and began exploring options of how to build the calculators.  However, after researching some more, I was able to determine a significantly easier process.        
[Simple Interactive Website](https://baylex.github.io/TW_Estimators/)    
[Source starter code](https://simplestepscode.com/javascript-quiz-tutorial/)   

## Design and Write Formulas for the Estimators in Excel Online
With a OneDrive account, I was able to write VLOOKUP and conditional formulas as needed for the 2 calculators in Excel Online, which was validated by the TIA Coordinator.  All inputs from the end user needed to be made into dropdown menu items per the design specifications.  Once the design, branding, and layout was approved by the Communication committee, the next thing to do was to secure the formulas.  Using the desktop application of Excel, the spreadsheet was locked, all formulas and lookup arrays were hidden, password protections set, and finally saved back into Excel Online.   
![Pic1](https://github.com/Baylex/TW_Estimators/blob/main/images/Excel_Online.PNG)  

## Design the layout of the Estimators in Squarespace 
The initial design was for the estimator on top and the directions below.  However, working inside Squarespace, the directions were moved to the left to show both the calculator and directions as soon as you land on the page.  The Communication committee did a secondary checked for branding, font, and coloring alignments to coordinate with the rest of the website.  
![Pic2](https://github.com/Baylex/TW_Estimators/blob/main/images/Squarespace.PNG)

## Embed the Estimators into Squarespace with JavaScript
In OneDrive with Excel Online, right clicking the file will allow the embed option to appear, which generates some JavaScript code that can be adjusted in a secondary screen.  When all the adjustments are made, the code can be copied and pasted into a JavaScript container within Squarespace.  I wrapped the code with the center script to align the estimator on the page for a final clean look.

## Final version of the Estimators
[TIA Designation Estimator](https://transformationwaco.org/tia-designation-estimator)   
![Pic3](https://github.com/Baylex/TW_Estimators/blob/main/images/designation.PNG)

[TIA Pooled Eligibility Estimator](https://transformationwaco.org/tia-pooled-estimator)   
![Pic4](https://github.com/Baylex/TW_Estimators/blob/main/images/Pooled.PNG)

## Challenges
I was able to get all the input selections set up as dropdown menu items.  However, I wanted to use the 0% to 100% as a spin button under the Developer tab.  Unfortunately, the Excel Online version does not support the spin button from either the Form control or the Active X control.  I had to settle using the List option under Data Validation and used a reference array for the list.  
[Spin Buttons in Excel](https://support.microsoft.com/en-us/office/add-a-scroll-bar-or-spin-button-to-a-worksheet-f8443be3-ff00-4cad-bb2f-bf0f88ebf5bb)
  
## Future Versions
The team wants to add the estimated stipend amounts based on the campus.  However, the funding formulas will need some more time and work to disaggregate appropriately.    
[Funding Allotments](https://tiatexas.org/about-teacher-incentive-allotment/allotments/)   
[Funding Map](https://tiatexas.org/about-teacher-incentive-allotment/funding-allocations-map/)  
