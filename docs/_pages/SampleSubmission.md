---
Layout: AboutMe
permalink: /SampleSubmission/
title: "SampleSubmission"
excerpt: ""
author_profile: false
---

<head>
<style>
.myDiv {
  margin-left: 20%;
  margin-right: 25%;
  text-align: left;
}
</style>
</head>

<div class="myDiv">
<Center><H3><u> SR Data Submission </u></H3></Center>

<label for="ReportingMonth">Reporting Period Month:</label>
<select name="ReportingMonth" id="ReportingMonth">
  <option value="Please Select">Please Select</option>
  <option style = "color:black" value="January">January</option>
  <option style = "color:black" value="February">February</option>
  <option style = "color:black" value="March">March</option>
  <option style = "color:black" value="April">April</option>
  <option style = "color:black" value="May">May</option>
  <option style = "color:black" value="June">June</option>
  <option style = "color:black" value="July">July</option>
  <option style = "color:black" value="August">August</option>
  <option style = "color:black" value="September">September</option>
  <option style = "color:black" value="October">October</option>
  <option style = "color:black" value="November">November</option>
  <option style = "color:black" value="December">December</option>
</select>

<label for="ReportingYear">Reporting Period Year:</label>
<select name="ReportingYear" id="ReportingYear">
  <option value="Please Select">Please Select</option>
  <option style = "color:black" value="2021">2021</option>
  <option style = "color:black" value="2022">2022</option>
  <option style = "color:black" value="2023">2023</option>
  <option style = "color:black" value="2024">2024</option>
  <option style = "color:black" value="2025">2025</option>
  <option style = "color:black" value="2026">2026</option>
  <option style = "color:black" value="2027">2027</option>
  <option style = "color:black" value="2028">2028</option>
  <option style = "color:black" value="2029">2029</option>
  <option style = "color:black" value="2030">2030</option>
  <option style = "color:black" value="2031">2031</option>
  <option style = "color:black" value="2032">2032</option>
</select>

<label for="FileType">FileType:</label>
<select name="FileType" id="FileType">
  <option value="Please Select">Please Select</option>
  <option style = "color:black" value="Premium Details">Premium Details</option>
  <option style = "color:black" value="Claim Details">Claim Details</option>
  <option style = "color:black" value="Premium Controls">Premium Controls</option>
  <option style = "color:black" value="Claim Controls">Claim Controls</option>
  <option style = "color:black" value="Other">Other</option>
</select>
<BR>
<textarea name="comment">If applicable, enter any comments here...</textarea>
<BR>
<input id="attestcb" type="checkbox" style="float: left; margin-top: 5px;>">
An officer of the administrator has attested that, to the best of his or her knowledge and belief, the data provided with this submission is a financially accurate representation of activity in the specified period.
<BR>
<label for="myfile">Select a file:</label>
<input type="file" id="UploadedFile" name="UploadedFile">

</div>
