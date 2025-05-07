<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this Developer TechXchange workshop. 



## Accessing the hands-on lab

Click [here](https://github.com/DevOps-on-IBMZ/DTX-wca4z-CICS/blob/main/DTX-Lab-Connection-Instructions.pdf) to read the instructions for IBM System access. 

All lab instructions are in the "Lab Docs" folder on your remote desktop, or can be downloaded from [here](https://github.com/DevOps-on-IBMZ/DTX-wca4z-CICS/blob/main/DevTechXchange-COBOLCICSJavaInterop-Lab.pdf) to view it locally.



**Please enter the user number provided by the lab instructor.**

<form onsubmit="return false;">
<div class="input-group mb-3 col-6">
<span class="input-group-text" id="basic-addon1">User Number</span>
<input type="text" class="form-control" placeholder="User Number" aria-label="UserNumber" aria-describedby="basic-addon1" id="registration-email" maxlength="50" required oninput="validate();">
</div>
<div class="col-6">
<button id="btn-submit" class="btn btn-primary" type="submit" onclick="getLab(document.getElementById('registration-email').value)" disabled>Submit</button>
</div>
</form>
<div id="lab" class=".container .text-monospace">
</div>

## Help 
Having trouble with labs? Send an email to [Steve Fowlkes](mailto: fowlkes@us.ibm.com).
