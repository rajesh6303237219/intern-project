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
  @media screen and (min-width:2559px){
    .img{
      height:74vh;
      width:35vw;
      display: flex;
      justify-content: center;
    }
    .introduction{
       font-size:30px;
    }
    .icon a, i{
        font-size:30px;
        margin-top:35px;
      }
      .h1{
        margin-top:90%;
      }
      .introduction p{
         font-size:20px;
      }
      .introduction h1{
        font-size:70px;
         }
         .introduction p{
             font-size:40px;
         }
         .h1{
          margin-top:38%;
         }
         .introduction button{
               font-size:25px;
               margin-top:60px;
         }
        }
        @media screen and (max-width:1025px) and (min-width:1023px){
        .img {
            height:84vh;
            width:30vw;
        }  
        .introduction h1{
             font-size:30px;
        }
        .introduction p{
           font-size:14px;
        }
        .h1{
           margin-top:38%;
        }
        }
        @media screen and (max-width:769px) and (min-width:767px){
          .main{
            display: flex;
            flex-direction: column;
          }
          .img{
             height:86vh;
             width:40vw;
             display: flex;
             align-items: center;
          }
          .img {
             margin-left:29%;
          }
          .main-content{
             height:100%;
          }
          .introduction h1{
              display: flex;
              justify-content: center;
              word-spacing:20px;
              }
              .h1{
                 margin-top:10%;
              }
              .introduction p{
                display: flex;
                justify-content: center;
              }
                 button{
                  margin-left:35%;
                  margin-top:19%;
              }
              .icon {
            display: flex;
            flex-direction:row;
            margin-left:220px;
          }
        }
        @media screen and (max-width:426px) and (min-width:424px){
          .main-content{
                height:100%;
          }
          .main{
           display: flex;
           flex-direction: column;
           height: 100%;
          }
          .img{
             width:64vw;
             display: flex;
             align-items: center;
             margin-left:19%;
          }
          .introduction{
           margin-left:60px;
          }
          .introduction button{
              margin-left:18%;
              margin-top: 40px;
          }
          .icon {
            display: flex;
            flex-direction: row;
            margin-left:80px;
            
          }
        }
        @media screen and (max-width:376px) and (min-width:374px){ 
          .main-content{
                height:100%;
          }
          .main{
           display: flex;
           flex-direction: column;
          }
          .img{
             width:64vw;
             display: flex;
             align-items: center;
             margin-left:19%;
          }
          .introduction{
           margin-left:60px;
          }
          .introduction button{
              margin-left:13%;
              margin-top:20%;
          }
          
          .icon {
           display: flex;
           flex-direction: row;
           margin-left:60px;
          }
        }
        @media screen and (max-width:321px) and (min-width:319px){
          .main-content{
                height:100%;
          }
          .main{
           display: flex;
           flex-direction: column;
          }
          .img{
             width:64vw;
             display: flex;
             align-items: center;
             margin-left:19%;
             margin-top:70px;
          }
          .introduction{
           margin-left:20px;
          }
          .introduction button{
              margin-left:18%;
          }
          .icon {
            display: flex;
            flex-direction: row;
            margin-left:34px;
          }
        }
</style>