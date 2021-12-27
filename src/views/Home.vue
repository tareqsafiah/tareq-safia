<template>
<div id="home">
    <navbar id="nav"/>
    <div class="container-fluid" id="backg">
    <div class="row">
      <div class="col-sm-12 col-md-5 col">
      <br><br><br>
        <div id="card1" class="v-card c-sheet ">
         <div id="t1" class="test1 font-weight-bold">
              <span>Welcome In My Protfolio</span>
          </div><br><br><br>
          <div id="t2" class="test2 font-weight-light font-italic">
            <h4>Let's make something great together.</h4></div><br>
          <div id="t3" class="test3 font-weight-light font-italic">
              <h6>Get in touch with us for a quick quote</h6>
            </div>
          <div class="middel">
            <a href="/mywork/" class="btn btn1">My Work</a>
            <a href="getservice/" class="btn btn2">Start a Project</a>
      </div>
        </div>
      </div>
 <div class="col-sm-12 col-md-6 col right-15-anim" id="mid">
      <div id="card2" class="v-sheet" style="position:relative">
            <v-img src="../assets/def.png"/>
            <br><br><br>
      </div>
    </div>
    </div>
  </div>
    </div>
</template>

<script>
import navbar from '../components/header.vue'
export default {
  name: 'home',
  components: {
    navbar
  }
}
</script>
<style scoped>
#home{
background-color: #dfe6e9;
    opacity: 0.99;
height: 100%;
}
#nav{
  position: sticky;
  top:0;
  z-index: 10;
}
#midd {
    background-color: transparent;
    border: 0px;
    box-shadow: 0px 0px 0px 0px;
    opacity: 1;

}
#t1,
#t2,
#t3
{
  text-decoration: none;
  color: #2d3436;
  font-size: 25px;
  left: 4%;
  display: inline;
  height: 100px;
  font-weight: bold;
  position: relative;
  animation-name: mymove;
  animation-duration: 2.5s;
  animation-iteration-count: 1;
  animation-timing-function: ease;
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
.col-md-5 {
    flex: 0 0 41.6666666667%;
    max-width: 41.6666666667%;
    padding: 12px;
}
.col-md-7{
      flex: 0 0 58.3333333333%;
    max-width: 58.3333333333%;
    padding: 12px;
}
.col-sm-12 {
    flex: 0 0 100%;
    max-width: 100%;
    padding: 12px;
}
.col {
    flex-basis: 0;
    flex-grow: 1;
    max-width: 100%;
    padding: 12px;
}
.v-card {
    overflow-wrap: break-word;
    white-space: normal;
}
  .btn{
            left: 4%;
            position: relative;
            display: block;
            color: #2d3436;
            font-size: 20px;
            font-family: "monttserrat";
            text-decoration: none;
            width: fit-content;
            margin: 30px 0;
            width: 50%;
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
            border-radius: 10px;
        }
        .btn1::before{
            width: 100%;
            height: 0;
            transform: translate(-50%, -50%) rotate(45deg);
            border-radius: 10px;
        }
        .btn1:hover::before{
            height: 800%;
            border-radius: 10px;
        }
        .btn2::before{
            width: 100%;
            height: 0;
            transform: translate(-50%, -50%) rotate(45deg);
            border-radius: 10px;
        }
        .btn2:hover::before{
            height: 800%;
            border-radius: 10px;
            border-radius: 10px;
        }
        .middle{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
        }
        body{
          background: #dfe6e9;
          opacity: 0.99;
          height: 100%;
        }
        .v-application {
    display: flex;
    position: sticky;
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
