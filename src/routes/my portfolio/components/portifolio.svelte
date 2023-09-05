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
     @media screen and (max-width:426px) and (min-width:424px){
       .main{
         display: flex;
         flex-direction: column;
         height:130%;
       }
       .disply{
          display: flex;
          flex-direction: column;
       }
       .flex{
          display: flex;
          flex-direction: column;
       }
       .images img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .image1 img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .image2 img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .card1 img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .card2 img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .card3 img{
           height:35vh;
           width:60vw;
           margin-left:80px;
       }
     }
     @media screen and (max-width:376px) and (min-width:374px){
      .main{
         display: flex;
         flex-direction: column;
         height:130%;
         width:110vw;
       }
       .disply{
          display: flex;
          flex-direction: column;
       }
       .flex{
          display: flex;
          flex-direction: column;
       }
       .images img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .image1 img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .image2 img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .card1 img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .card2 img{
           height:45vh;
           width:60vw;
           margin-left:80px;
       }
       .card3 img{
           height:35vh;
           width:60vw;
           margin-left:80px;
       }
     }
     @media screen and (max-width:321px) and (min-width:319px){
      .main{
         display: flex;
         flex-direction: column;
         height:130%;
         width:130vw;
       }
       .disply{
          display: flex;
          flex-direction: column;
       }
       .flex{
          display: flex;
          flex-direction: column;
       }
       .images img{
           height:45vh;
           width:80vw;
           margin-left:80px;
       }
       .image1 img{
           height:45vh;
           width:80vw;
           margin-left:80px;
       }
       .image2 img{
           height:45vh;
           width:80vw;
           margin-left:80px;
       }
       .card1 img{
           height:45vh;
           width:80vw;
           margin-left:80px;
       }
       .card2 img{
           height:45vh;
           width:80vw;
           margin-left:80px;
       }
       .card3 img{
           height:35vh;
           width:80vw;
           margin-left:80px;
       }
     }
</style>
