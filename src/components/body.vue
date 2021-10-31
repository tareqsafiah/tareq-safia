<template>
<v-app>
  <div class="continer" data-v-822f34ec="" id="backg" >
    <div class="row" data-v-822f34ec="">
      <div class="col-sm-12 col-md-5 col">
      <br><br><br>
        <div id="card1" class="v-card c-sheet " data-v-d53af812="" data-v-822f34ec="">
         <div id="t1" class="test1 font-weight-bold">
              <span>Welcome In My Protfolio</span>
          </div><br><br><br>
          <div id="t2" class="test2 font-weight-light font-italic">
<h4>
Let's make something great together.</h4>            </div><br>
          <div id="t3" class="test3 font-weight-light font-italic">
              <h6>Get in touch with us for a quick quote</h6>
            </div>
          <div class="middel">
            <a href="/MyWork/" class="btn btn1">Review My Work</a>
            <a href="GetService/" class="btn btn2">
Start a Project
</a>
      </div>
        </div>
      </div>
 <div class="col-sm-12 col-md-6 col right-15-anim" data-v-822f34ec="" id="mid">
      <div id="card2" class="v-sheet" data-v-d53af812="" data-v-822f34ec="" style="position:relative">
            <v-img src="../assets/def.png"/>
            <br><br><br>
      </div>
    </div>
    </div>
  </div>
</v-app>
</template>
<script>
export default {
  name: 'bodyy'
}
</script>
<style scoped>
#midd {
    background-color: transparent;
    border: 0px;
    box-shadow: 0px 0px 0px 0px;
    opacity: 1;

}
/* @media screen and (max-width:600px) {
  .colm {
    width: 100%;
  }
} */
#t1,
#t2,
#t3
{
  text-decoration: none;
  color: #2d3436;
  font-size: 25px;
  left: 4%;
  display: inline;
  width: 250px;
  height: 100px;
  font-weight: bold;
  position: relative;
  animation-name: mymove;
  animation-duration: 2.5s;
  animation-iteration-count: 1;
    animation-timing-function: ease;
    /* font-family: weight-bold; */
    cursor: pointer;
}
@keyframes mymove {
  from {left: -110%;}
  to {color:#2d3436; left: 4%;
}
}
#t1 :hover{
color: #ff7675;

}
#t2 :hover{
color: #ff7675;
}
#t3
 :hover{
color: #ff7675;
}
  /* #mid{
 width: ;
  } */
  .btn{
            left: 4%;
            position: relative;
            display: block;
            color: #2d3436;
            font-size: 20px;
            font-family: "monttserrat";
            text-decoration: none;
            width: 60%;
            margin: 30px 0;
            border: 2px solid #ff7675;
            padding: 14px 40px;
            overflow: hidden;
            transition: 1s all ease-out;
            border-radius: 10px;
            text-align: center;
            animation-name: mybtn;
            animation-duration: 2.5s;
            animation-iteration-count: 1;
            animation-timing-function: ease-out;
        }
@keyframes mybtn {
  from {left: -310%;}
  to {color:#2d3436; left: 4%;
}
        }
        .btn::before{
          text-decoration: none;
            background-color: #ff7675;
            content: "";
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: -1;
            transition: all 0.6s ease;
        }
        .btn1::before{
            width: 100%;
            height: 0;
            transform: translate(-50%, -50%) rotate(45deg);
        }
        .btn1:hover::before{
            height: 650%;
        }
        .btn2::before{
            width: 100%;
            height: 0;
            transform: translate(-50%, -50%) rotate(45deg);
        }
        .btn2:hover::before{
            height: 650%;
        }
        .middle{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
        }
        .continer{
          background-color: #dfe6e9;
    opacity: 0.99;
height: 100%;
        }
        .right-15-anim {
    -webkit-animation: transation-right 1.5s;
    animation: transation-right 2.5s;
}
@keyframes transation-right{
  0% {
    opacity: 0;
    transform: translatex(40px);
}
100% {
    opacity: 1;
    transform: translateY(0);
}
}
</style>
