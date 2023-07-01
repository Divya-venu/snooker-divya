# snooker-divya
/* Reset default styles */
body, h1, h2, h3, p, ul, li {
  margin: 0;
  padding: 0;
}

/* Header styles */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
}

.logo img {
  height: 50px;
}

nav ul {
  list-style-type: none;
}

nav ul li {
  display: inline-block;
  margin-left: 10px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
}

/* Section styles */
section {
  padding: 40px;
}

/* Footer styles */
footer {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}
.container {
  display: grid;
  align-items: center; 
  grid-template-columns: 1fr 1fr;
  column-gap: 2px;
 }
 
 img {
   max-width: 100%;
   max-height:100%;
 }
 
 .text {
   font-size: 18px;
   color:chocolate;
   font-family: 'Segoe UI';
 }
 .tables
 {
  font-size: 18px;
   color:hsla(0, 0%, 98%, 0.938);
   font-family:'Times new Roman';
 }
 .box{
  width:300px;
  height:300px;
  padding: 300p;
  position: absolute;
  top: 3300px;
  left: 50%;
  transform: translate(-50%,-50%);
  background: #FFFBE5;
  text-align: center;
}
.box h1
{
  color: black;
  text-transform: uppercase;
  font-weight: 700;
}
.box input[type="text"],.box input[type="password"]
{
  border:0;
  background:none;
  display:block;
  margin:20px auto;
  text-align:center;
  border:3px solid #0367fd;
  padding:14px 10px;
  outline:none;
  color:white;
  border-radius:24px;
  transition:0.25px;
}

.box input[type="text"],.box input[type="password"]:focus{
     
  width: 270px;
  border-color: #ffc400ec;
}
.box input[type="submit"]{
  border:0;
  background:none;
  display:block;
  margin:20px auto;
  text-align:center;
  border:3px solid #ffc400ec;
  padding:14px 35px;
  outline:none;
  color:rgb(211, 21, 21);
  border-radius:24px;
  transition:0.25px;
  cursor: pointer;

}
.box input[type="submit"]:hover{
  background: #ffc400ec;
}
.body1{
  margin:0;
  padding:0;
  font-family:sans-serf;
  background-color: rgb(5, 1, 1);
  background-size: cover;
}
.div1 {
  background: url(g1.jpg);
  background-size: 1500px 800px;
  background-repeat: no-repeat;
}
.pic1{
  height: 300px;
  width: 300px;
  margin: 10px;
  }

  .focus img{
    -webkit-transition: all 1s ease;
        -moz-transition: all 1s ease;
             -o-transition: all 1s ease;
          -ms-transition: all 1s ease;
                 transition: all 1s ease; 
       }
.focus img:hover{
      border: 30px solid #f0e9e9;
      border-radius:40%;
    -webkit-transition: all 1s ease;
       -moz-transition: all 1s ease;
            -o-transition: all 1s ease;
         -ms-transition: all 1s ease;
                transition: all 1s ease; 
               }


  .pic2{
    margin-left: 480px;
    margin-right: 480px;
    margin-top:-310px;
    height: 300px;
    width: 300px;
    }

  .pic3{
    margin-left: 950px;
    margin-right: 950px;
    margin-top:-310px;
    height: 300px;
    width: 300px;
    border-top-left-radius: 10%;
    }
    .pic4{
    margin-left: 50px;
    margin-right: 950px;
    margin-top:-90px;
    height: 300px;
    width: 300px;
    border-top-left-radius: 10%;
    }
    .pic5{
      margin-left: 520px;
      margin-right: 950px;
      margin-top:-305px;
      height: 300px;
      width: 300px;
     }
    .pic6{
      margin-left: 980px;
      margin-right: 950px;
      margin-top:-305px;
      height: 300px;
      width: 300px;
      }
      .membership{
        width: 65em;
        border: 3px solid #DE3163;
        box-shadow: 9px 6px 4px #5B2C6F;
        padding: 7px 11px;
        background-image: linear-gradient(150deg, #EAFAF1 , #E8DAEF 30%,#E5E8E8 );
    }
    .column {
      float: left;
      width: 30%;
      padding: 5px;
    }
    
    /* Clear floats after image containers */
    .row::after {
      content: "";
      clear: both;
      display: table;
    }
    .event1{
      margin-left: 400px;
      margin-right: 500px;
      margin-top:-305px;
    }
    .event2{
      margin-left: 0px;
      margin-right: 100px;
      margin-top:-305px;
    }
    .event3{
      margin-left: 0px;
      margin-right: 0px;
      margin-top:-305px;
      height: 300px;
    }
    .logo1{
      height: 30px;
    }
   
    .title{
      width: 100%;
      border: 3px solid #ffffff;
      box-shadow: 9px 6px 4px #daa6f0;
      padding: 7px 11px;
      background-image: linear-gradient(150deg, #EAFAF1 , #E8DAEF 30%,#E5E8E8 );
      font-family: 'Times New Roman';
      font-size: 30px;
      text-align:center;
  }
  .table-text{
    font-family: 'Times New Roman';
      font-size: 18px;
  }
