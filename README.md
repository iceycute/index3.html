<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="port.css">
</head>

<body>
    <style>
        * {
            border: 0%;
            padding: 0%;
            margin: 0%;
            box-sizing: border-box;
        }

        html,
        body {
            width: 100%;
            height: 150vh;
            font-size: 14px;
            font-weight: normal;
            background: #ADD8E6;
        }

        .box {
            border: solid white;
            font-family: sans-serif;
            position: absolute;
            top: 15%;
            left: 34%;
            width: 450px;
            background: white;
            padding: 40px;
            box-sizing: border-box;
            border-bottom-right-radius: 12px;
            border-top-left-radius: 12px;
            border-top-right-radius: 12px;

        }

        .box h2 {
            color: blue;
            margin: 0 0 5px;
            padding: 0;
            text-align: center;

        }

        .box form p {
            /* margin-top:15px; */
            margin-bottom: 35px;
            text-align: center;
        }

        .box .inputbox input {
            width: 100%;
            padding: 10px 0;
            font-size: 16px;
            margin-bottom: 30px;
            border: none;
            /* border: solid 1px; */


        }

        .box form .inputbox input {
            margin-top: 5px;
            padding-left: 10px;
            background: whitesmoke;
        }

        .box .inputbox .inj {
            /* margin-top: 20px; */
            padding-left: 10px;

        }

        .box .inputbox .inp {
            border: solid;
            background: blue;
            border-bottom-right-radius: 12px;
            border-top-left-radius: 12px;
            border-top-right-radius: 12px;
            color: white;
            font-size: 18px;
            /* font-family: fantasy; */
            font-weight: 530;
            padding: 13px;
            margin-top: 25px;
        }
       .box .inputbox .w3-select{
              width: 362px;
              height: 34px;
              background: whitesmoke;
              border:none;
              padding: 10px;
              margin-top: 5px;
        }
        center h1{
            padding-top: 27px;
            color: white;
        
        }
        section{
            padding-top:  60%;
        }
    </style>



<div class="top">
<center>
    <h1>piggyvest</h1>
</center>
</div>
    <div class="box">
        
        <form>
            <h2>Create a Secure Account</h2>
            <p>Welcome to the future of Savings & Investment</p>

            <div class="inputbox">
                <label><b>Full Name</b></label>
                <input type="text" name="" required="" placeholder="Full Name" class="inj">
            </div>
            <div class="inputbox">
                <label><b>Email Address</b></label>
                <input type="email" name="" required="" placeholder="Email Address">
            </div>
            <div class="inputbox">
                <label><b>Phone Number</b></label>
                <input type="tel" name="" required="" placeholder="Phone Number">
            </div>
            <div class="inputbox">
                <label> <b>Password</b></label>
                <input type="text" name="" required="" placeholder="Password">
            </div>
            <div class="inputbox">
                <label><b>Referrer Phone or Promo Code(Optional)</b></label>
                <input type="tex" name="" required="" placeholder="Referrer Phone or Promo Code">
            </div>
            <div class="inputbox">
               <label><b>How Did Your Hear About Us? (Optional)</b></label>
               <select class="w3-select" name="option" >
                    <option value="" disabled selected ><p>Click To Select</p></option>
                    <option value="1">Facebook</option>
                    <option value="2">Twitter</option>
                    <option value="3">Instagram</option>
                    <option value="1">Freind/Family/Coworker Referral</option>
                    <option value="2">Google search</option>
                    <option value="3">Google playstore</option>
                    <option value="2">Oline Blog</option>
                    <option value="3">Local Newspaper</option>
                    <option value="2">At an event</option>
                    <option value="3">Other</option>
                  </select>
                  
               
               <!-- <input type="" name="option" required="" placeholder="Click To Select "> -->
            </div>
            <div class="inputbox">
                <input type="submit" value="CREATE ACCOUNT" class="inp">
            </div>
        </form>
    </div>
  
     <section>
        <center>
            <a href="https://dashboard.piggyvest.com">Already have an Account? Log in</a>
        </center>
     </section>


</body>

</html>
