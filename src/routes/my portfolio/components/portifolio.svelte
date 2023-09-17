<section class="main">
<div class="myportfolio">
 <h1>MY <span class="text-green-800">PORTFOLIO</span></h1>
 <h2>Here is some of my work that I've done in various programming language</h2>
</div>
<div class="disply">
<div class="images">
  <img src="/img2.jpg"/>  
</div>
<div class="image1">
  <img src="/img3.jpg"/>
</div>
<div class="image2">
  <img src="/img4.jpg"/>
</div>
</div>
<div class="flex">
  <div class="card1">
  <img src="/img5.jpg"/>  
  </div>
  <div class="card2">
    <img src="/img6.jpg"/>
  </div>
  <div class="card3">
    <img src="/img7.jpg"/>
  </div>
</div>
</section>
<style>
    .main{
       background-color:#000000;
       height:130vh;
    }
    .myportfolio h1{
        color:white;
        text-align: center;
        font-weight: bold;
        font-size:70px;
    }
    .myportfolio h2{
         color:white;
         text-align: center;
         margin-top:70px;
         font-weight: bold;
         font-size:20px;
    }
    .images img{
       height:36vh;
       width:24vw;
       border-radius:14px;
    }
    .image1 img{
      height:36vh;
       width:24vw;
       border-radius:14px;
    }
    .image2 img{
      height:36vh;
       width:24vw;
       border-radius:14px;
    }
    .disply{
      display:flex;
      justify-content:center;
      margin-top:80px;
      gap:30px;
    }
    .flex{
      display: flex;
      justify-content:center;
      gap:30px;
      margin-top:40px;
    }
    .card1 img{
      height:36vh;
       width:24vw;
       border-radius:14px;
    }
    .card2 img{
      height:36vh;
       width:24vw;
       border-radius:14px;
    }
    .card3 img{
      height:36vh;
       width:24vw;
       border-radius:14px;
    }
    .hovering h3{
     color:white;
    }
    .hover{
       color:white;
    }
    .images:hover{
       cursor: pointer;
       scale: 0.2em;
       border-style: solid;
       border-width:5px;
       border-color:green;
       border-radius:20px;
      }
      .image1:hover{
       cursor: pointer;
       scale: 0.2em;
       border-style: solid;
       border-width:5px;
       border-color:green;
       border-radius:20px;
      }
      .image2:hover{
       cursor: pointer;
       scale: 0.2em;
       border-style: solid;
       border-width:5px;
       border-color:green;
       border-radius:20px;
      }
      .card1:hover{
       cursor: pointer;
       scale: 0.2em;
       border-style: solid;
       border-width:5px;
       border-color:green;
       border-radius:20px;
      }
      .card2:hover{
       cursor: pointer;
       scale: 0.2em;
       border-style: solid;
       border-width:5px;
       border-color:green;
       border-radius:20px;
      }
      .card1:hover{
       cursor: pointer;
       scale: 0.2em;
       border-style: solid;
       border-width:5px;
       border-color:green;
       border-radius:20px;
      }
      .card2:hover{
       cursor: pointer;
       scale: 0.2em;
       border-style: solid;
       border-width:5px;
       border-color:green;
       border-radius:20px;
      }
      .card3:hover{
       cursor: pointer;
       scale: 0.2em;
       border-style: solid;
       border-width:5px;
       border-color:green;
       border-radius:20px;
      }
     @media screen and (min-width:2529px){
      .myportfolio{
        font-size:100px;
      }
     }
     @media screen and (max-width:705px){
      .disply{
            display: flex;
            flex-direction: column;
            margin-left:33%;
      }
      .main{
          height:330vh;
      }
      .myportfolio h2{
          font-size:16px;
      }
      .images img{
            height:40vh;
            width:36vw;
      }
      .image1 img{
            height:40vh;
            width:36vw;
      }
      .image2 img{
            height:40vh;
            width:36vw;
      }
      .flex{
          display: flex;
          flex-direction: column;
          margin-left:33%;
      }
      .card1 img{
            height:40vh;
            width:36vw;
      }
      .card2 img{
            height:40vh;
            width:36vw;
      }
      .card3 img{
            height:40vh;
            width:36vw;
      }
      .myportfolio h1{
           font-size:60px;
      }
     }
     @media screen and (max-width:447px){
        .myportfolio h1{
            font-size:40px;
        }
       .images{
          height:40vh;
          width:40vw;
       }
     }
     @media screen and (max-width:324px){
            .myportfolio h1{
                font-size:35px;
            }
            .myportfolio h2{
                font-size:13px;
            }
     }
</style>