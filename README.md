# Length-of-Life
This project showcases Excel skills. It uses Vlookup and IF formulas to create a semi-dynamic, automatically updating dashboard using Excel only.

This is a reconstructed version of a project I was asked to do for a previous employer. In this rendition, I use a self-made dataset on cars. I take the raw data and use IF statements to generate a unique code for each car and then sort it into one of three hidden sorted sheets depending on how many months that car was being driven before being decommissioned. I then use charts to represent that data categorically on pie and bar charts, along with a series of three-line charts showing the frequency of how many months a car was in service before being decommissioned by each month. Laslty, I have pivot tables accessible for the viewer if the viewer wanted to take a deeper dive into the data. 

In the Excel file there are a total of 6 sheets. Three are considered front end (for the user of the file), and three are considered backend. The sheet files are:
<ul>
  <li>FRONT END</li>
    <ul>
      <li>Data</li>
      <li>Results</li>
      <li>Reason Categories</li>
    </ul>
  <li>BACK END</li>
    <ul>
      <li>CODE SHEET (Over1Year)</li>
      <li>CODE SHEET (Under1Year)</li>
      <li>CODE SHEET (3MonthsandUNder)</li>
    </ul>
</ul>


In the data sheet (which is where the raw data is contained), there are three initial columns:
<ul>
  <li>VIN: Which is not a real VIN of Ocurse, but just a series of numbers meant to represent a real VIN. </li>
  <li>Months—Shows how many months each vehicle was on the read before being decommissioned.</li>
  <li>Reason Category: This shows the category of reason that the vehicle was decommissioned for the passenger vehicle.</li>
</ul>

In the Results sheet we have the displayed dashboard, which includes pie, bar, and line charts along with pivot tables and some descriptive statistics on each slice of the dataset.

In the Reason Categories tab, we have an explanation of each category, so that way, when an administrative employee comes to enter in the data, the employee can see a brief description of each category. This was important in the origonal model because we had regular ambiguity as to which category to choose from. 

The remaining three sheets that are considered backend consist of the remaining formulas, which are used to sort the data into the slices. (It is also of note that there are many hidden columns in the data sheet as well that use formulas to support these three sheets.).
