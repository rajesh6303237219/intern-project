
<section class="main">
<div class="contuct">
 <h1>CONTACT  <span class="text-green-800">ME</span></h1>   
</div>
<div class="text">
<h2>CONTACT ME HERE</h2>
<h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. In, laborum numquam? Quam excepturi perspiciatis quas </h3>
<h3>quasi.</h3>    
</div>
<div class="maincontent">
<div class=flex> 
<div class="icons">
    <ul>
    <li><i class="fa-solid fa-location-dot text-white font-bold "></i></li>
    <li><i class="fa-solid fa-envelope text-white font-bold"></i></li>
   <li><i class="fa-solid fa-phone-volume"></i></li>
  <li><i class="fa-solid fa-earth-americas"></i></li>
    </ul>   
</div>
<div class="locations">
    <h3>Location</h3>
    <h3>Email</h3>
    <h3>Phone number</h3>
    <h3>Language</h3>
</div>
</div> 
<div class="details">
    <p>:PM Palem road vizag</p>
    <p>:rajeshbogadi123@gmail.com</p>
    <p>:6303237219</p>
    <p>:English, Telugu</p>
</div>
</div>
<div class="socialmedia-icons">
 <i class="fa-brands fa-facebook text-white mt-10 bg-green-900 p-2 rounded-lg"></i>
  <i class="fa-brands fa-twitter  text-white  bg-green-900 p-2 rounded-lg"></i>
  <i class="fa-brands fa-github  text-white  bg-green-900 p-2 rounded-lg"></i>
  <i class="fa-brands fa-youtube  text-white  bg-green-900 p-2 rounded-lg"></i>
</div>
<div class="inputs">
<form class="forms">
  <input class="one"type="text" placeholder="Your Name">
  <input class="two"type="text"name="email"placeholder="Email">
  <input class="three"type="text"name="enter subject"placeholder="Enter Subject">
  <textarea class="bg-black rounded-md text-white"rows="6" cols="24" placeholder="message here"></textarea> 
</form>
</div>
</section>
<style>
    .main{
       background-color:#191D2B;
       height:150vh;
    }
  .contuct h1{
      text-align: center;
      font-size:70px;
      font-weight: bold;
      color:white;
      }
      
      .text h2{
          color:white;
          word-spacing:5px;
          font-size:35px;
          font-weight: bold;
          margin-left:17%;
          margin-top:4%;
      }
      .text h3{
         color:white;
        margin-left:17%;
      } 
       ul li{
        color:white;
        margin-left:20px;
        gap:10px;
        font-size:23px;
        margin-top:9px;
    }
    .flex{
       display: flex;
       gap:13px;
    }
    .locations h3{
      color:white;
     margin-top:8px;
     font-size:23px;
    }
    .details{
      color:white;
      margin-top:20px;
      font-size:23px;
    }
    .maincontent{
      display: flex;
      justify-content: space-around;
      margin-top:30px;
    }
    .socialmedia-icons{
         margin-left:19%;
         font-size:35px;
    }
    .socialmedia-icons:hover{
       cursor: pointer;
      }
      .forms{
         display: flex;
         flex-direction: column;
         gap:10px;
         width:60%;
         margin-left:20%;
         margin-top:50px;
          }
          .one{
             background-color:black;
             border-radius:10px;
            height:6vh;
            color:white;
          }
          .two{
            background-color:black;
             border-radius:10px;
            height:6vh;
            color:white;
          }
         .three{
            background-color:black;
             border-radius:10px;
            height:6vh;
            color:white;
          }
          @media screen and (min-width:2559px){
            .contuct h1{
              font-size:120px;
            }
            .text h3{
               font-size:40px;
            }
            .text h2{
               font-size:60px;
            }
            .icons ul li{
                font-size:30px;
                margin-top:20px;
            }
            .locations h3{
               font-size:40px;
            }
            .details{
               font-size:40px;
            }
            .socialmedia-icons i{
               margin-top:120px;
               gap:60px;
               font-size:40px;
             }
             .forms input{
                 font-size:34px;
                 font-weight:bold;
                 margin-top:30px;
             }
             .forms textarea{
                 font-size:34px;
                 font-weight:bold;
                 margin-top:30px;
             }
          }
         @media screen and (max-width:920px){
          .maincontent{
                display: flex;
                flex-direction: column;
                margin-left:18%;
          }
          .icons{
             margin-top:30px;
          }
          .locations{
            margin-top:30px;
          }
          .details{
             margin-top:40px;
             font-size:30px;
          }
          }
          @media screen and (max-width:522px){
             .contuct h1{
                font-size:57px;
             }
             .details{
                font-size:22px;
             }
          }
          @media screen and (max-width:792px) and (min-width:319px){
                .main{
                  height:200vh;
                }
          }
          @media screen and (max-width:351px) and (min-width:319px){
            .main{
                height:220vh;
                width:100vw;
            }
            .contuct h1{
               font-size:40px;
            }
            .details{
              font-size:16px;
            }
            .text h2 {
               font-size:17px;
            }
            .text ,h3{
              font-size:13px;
            }
           
          }
        </style>