<script>
  import svelteLogo from './assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
</script>
<main class="wrapper">
<div class="container rounded bg-white mt-5 mb-5">
  <div class="row">
    <div class="col-md-3 border-right">
      <div class="d-flex flex-column align-items-center text-center p-3 py-5"><img class="rounded-circle " width="300px" src="https://media-exp1.licdn.com/dms/image/C4D0BAQGAUbVRtYhCwQ/company-logo_200_200/0/1645348114439?e=2147483647&v=beta&t=HCurpBmcJTOwhmVcC5UkJTuxuCJRguldsHPRhoqyU9c"></div>
  </div>
      <div class="col-md-5 border-right">
          <div class="p-3 py-5">
              <div class="d-flex justify-content-between align-items-center mb-3">
                  <h4 class="text-right">Patient Information</h4>
              </div>
              <div class="row mt-2">
                  <div class="col-md-6"><label class="labels">Name</label>
                    <p class=form-control>Subham</p>
                  </div>
                  <div class="col-md-6"><label class="labels">Surname</label><p class=form-control>
                    Govinda</p></div>
              </div>
              <div class="row mt-3">
                  <div class="col-md-12"><label class="labels">Mobile Number</label><p class=form-control>
                    9808128733</p></div>
                  <div class="col-md-12"><label class="labels">Address</label><p class=form-control>
                    Hattiban,Lalitpur</p></div>
                    <div class="col-md-12"><label class="labels">Date of Birth</label><p class=form-control>
                     2002/10/11</p></div>
                     <div class="col-md-12"><label class="labels">Sex</label><p class=form-control>
                      Male</p></div>
                     <div class="col-md-12"><label class="labels">Age</label><p class=form-control>
                    19yrs 7m 0d</p></div>
                  <div class="col-md-12"><label class="labels">PatientID</label><p class=form-control>
                    77059676</p></div>
                  <div class="col-md-12"><label class="labels">Diagnosis</label><p class=form-control>
                    Asthma</p></div>
                  <div class="col-md-12"><label class="labels">Reffered by</label><p class=form-control>
                    Yadav Bhatta</p></div>
                  
              </div>
             </div>
      </div>

</div>
</div>
</main>




<style>

.form-control:focus {
    box-shadow: none;
    border-color: #BA68C8
}

.text-right{
  font-size: 30px;
  margin-left: 100px;
}

.labels{
  font-weight: bold;
}
.rounded-circle {
  border-radius: 150px;
 

}
</style>
