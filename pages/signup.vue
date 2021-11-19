<template>
  <div class="container">
    <div class="pa-7 white d-inline-block">
      <div class="card">
        <div class="t1">
          <p>Sign up your bank account</p>
        </div>

        <v-form>
          <v-container>
            <v-row>
              <v-text-field
                label="Your Name"
                outlined
                light
              />

              <v-text-field
                label="Bank Account"
                outlined
                light
              />

              <v-text-field
                label="Moblie phone number"
                outlined
                light
              />
            </v-row>
            <v-row class="r1">
              <v-text-field
                label="Email"
                outlined
                light
              />
              <v-text-field
                label="Password"
                outlined
                light
              />
            </v-row>
          </v-container>
        </v-form>
        <div class="t2">
          <p>Use 6 characters with a mix of numbers and letters</p>
        </div>
        <div class="check">
          <v-checkbox
            label="By signing up , you agree to Bank's Term of Use & Privacy Policy"
            required
            light
          />
          <div class="btn" />
          <v-row
            align="center"
            justify="space-around"
          >
            <v-btn
              class="b1"
            >
              <p>SIGN UP</p>
            </v-btn>
            <div class="b2">
              or
            </div>
            <v-btn
              class="b3"
              light
            >
              <p>CANCLE</p>
            </v-btn>
          </v-row>
        </div>
        <div class="t3">
          <p>Already signed up? <a href="">Login</a></p>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.pa-7 {
  background-color: #fff;
  border-radius: 25px;
  font-size: 18px;
}
.card{
  background-color: #fff;
  border-radius: 25px;
  color: black;
}
.t1{
  font-size: 18px;
  color: #0c145e;
  margin-bottom: 1rem;
  font-family: Tahoma, Verdana, sans-serif;
}
.t2{
  font-size: 16px;
  color: #0c145e;
  font-family: Tahoma, Verdana, sans-serif;
  text-align: left;
  margin-left: 10px;
}
.t3{
  font-size: 20px;
  color: #0c145e;
  font-family: Tahoma, Verdana, sans-serif;
  margin-left: 10px;
  margin-top: 2.5rem;

}
.v-text-field{
  height: 70px;
  border: #0c145e;
}
.check label{
  margin-top: -10px;
  font-size: 14px;
  margin-left: 5px;
}
.b1{
  background: linear-gradient(to bottom,#ffeb3b,#ffc107);
  margin-top: 1rem;
  color:black;
}
.b1 p{
   padding: 12px 14px;
  margin-top: 15px ;
  color: black;
}

.b2{
  margin-top: 1rem;
}.b3{
  border: 1px solid #0c145e;
  margin-top: 1rem;
  padding: 10px 12px;
  background-color: #fff;
}
.b3 p{
  padding: 12px 14px;
  margin-top: 15px ;
}
</style>
