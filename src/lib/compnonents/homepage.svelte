<section class=main-content>
  <div class="main">
  <div class=img>
  <img src=/img1.png>  
  </div>
  <div class="introduction">
  <h1 class="h1">HI,I'am     <span class="text-green-800">   Salano</span></h1>
  <h1><span class="text-green-800">MIlan diaz.  </span> A</h1>
  <h1>Web Developer.</h1>
  <p id="content">I'am a web developer,i love to create beautiful </p>
  <p>and functional website.loreum ipsum dolorsit </p>
  <p>amet conseceter adipisicing elit. offica, libero lorem</p>
  <p>neque blanditiis sed aut!</p>
  <button>Download cv</button>
  </div>
  <div class="icon">
    <a href="/#"><i class="fa-solid fa-house bg-green-800 h-11 cursor-pointer p-3 rounded-lg"></i></a>
    <a href="/about us"><i class="fa-solid fa-user  bg-green-800 h-11 cursor-pointer p-3 rounded-lg"></i></a>
    <a href="/my portfolio"><i class="fa-solid fa-image  bg-green-800 h-11 cursor-pointer p-3 rounded-lg"></i></a>
     <a href="/contuct us"><i class="fa-solid fa-phone  bg-green-800 h-11 cursor-pointer p-3 rounded-lg"></i></a>
  </div>
</div>  
</section>
<style>
  
    .img{
      background-color: #000000;
    }
    .introduction h1{
        color:white;
        font-size:40px;
        font-weight:900;
      }
    .introduction p{
         color:white;
         font-size:20px;
         gap:10px;
         margin-top:10px;
    }
    .h1{
      margin-top:30%;
    }
    .img{
     margin-top:6%;
     border-radius:20px;
    }
    .main-content{                                               
     background-color: #191D2B;
     height: 101vh;
    }
    .main{
      display: flex;
     justify-content: space-around;
    }
    .introduction button{
      color:white;
      background-color:#166534;
      padding:14px;
      width:180px;
      border-radius:12px;
      border-inline-style:#27ae60;
      font-size:15px;
      margin-top:30px;
    }
    button:hover{
      cursor: pointer;
      transition: 0.1s ease-in-out;
      background-color:white;
      color: #27ae60;
    }
    .icon{
      display: flex;
      flex-direction: column;
      gap:8%;
      color: white;
      margin-top:12%;
      font-size:20px;
    }
    #content{
       margin-top:40px;
    }       
  @media screen and (max-width:1141px){
    .icon a{
          margin-top:20%;
    }
    .img img{
        margin-top:80px;
    }
  }
  @media screen and (max-width:971px){
       .img img{
         height:60vh;
         width:30vw;
        }
   .h1{
       margin-top:80px;
        }
  }
  @media screen and (max-width:1025px) and (min-width:1023px){
      .img{
        height:80vh;
         width:30vw;
         margin-top:99px;
      }
      .img img{
        height:60vh;
      }
      .introduction{
        margin-top:0px;
      }
  }
  @media screen and (max-width:869px){
   .main{
      display: flex;
      flex-direction: column;
     }
     .main-content{
     height:240vh;
     }
     .img{
       width:40vw;
       height:80vh;
       margin-left:240px;
     }
     .img img{
         margin-left:50px;
     }
     .introduction{
      margin-left:30%;
     }
     .icon{
        display: flex;
        flex-direction: row;
        margin-top:0px;
        margin: left 60px;
     }
     .icon a{
        margin-left:90px;
     }
  }
  @media screen and (max-width:707px){
     .icon a{
        margin-left:70px;
     }
     .introduction{
       margin-left:25%;
     }
  }
  @media screen and (max-width:612px){
    .img{
      height:90vh;
      width:50vw;
      margin-left:140px;
    }
    .introduction{
       margin-left:100px;
    }
    .icon{
      gap:20px;
    }
    }
   @media screen and (max-width:560px){
    .introduction{
       margin-left:56px;
    }
   }
   @media screen and (max-width:525px){
    .introduction h1{
      font-size:30px;
      margin-left:50px;
    }
    .introduction p{
      font-size:17px;
      margin-left:30px;
    }
    .introduction button{
       margin-left:20%;
    }
    .icon{
      gap:0px;
      margin-left: 0%;
    }
    .main-content{
      height:200vh;
    }
   }
   @media screen and (max-width:466px){
    .icon a{
      margin-left:46px;
      gap:20px;
    }
      }
 @media screen and (max-width:442px){
  .introduction p{
    font-size:14px;
    margin-left:8px;
  }
  .img{
     height:90vh;
     width:290px;
     margin-left:69px;
     margin-top:80px;
  }
  .img img{
     margin-left:90px;
  }
 }  
 @media screen and (max-width:390px){
   .img{
      height:80vh;
      margin-left:50px;
   }
   .introduction h1{  
       margin-left:22px;
   }
   .introduction p{
       font-size:12px;
   }
   .introduction button{
        margin-left:40px;
   }
 }   
 @media screen and (max-width:365px){
   .icon,a{
     font-size:13px;
     padding:0px;
   }
 }
 @media screen and (max-width:341px){
     .img{
      width:70vw;
     }
     .img img{
        margin-left:70px;
 }
 .introduction h1{
    font-size:23px;
 }
 .introduction p{
   margin-left:0px;
   font-size:10px;
 }
 .introduction button{
    margin-left:0px;
 }
 .icon ,a{
    gap:0px;
    font-size:8px;
 }
 }
</style>