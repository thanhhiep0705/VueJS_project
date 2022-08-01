<template>
  <div class = "post">
    <p class = "post-date">{{date}}</p>
    <p id = "post-type">{{type}}</p>
    <P class = "post-title">{{title}}</P>
    <div class = "icon">
        <i class="fa-solid fa-angle-right"></i>
    </div>
  </div>
</template>

<script>
export default {
    name: "PostComp",
    props:{
      date: String,
      title: String,
      type: String
    },
    data(){
        return{

        }
    }

}
</script>

<style>
.post {  
  display: flex;
  justify-content: left;
  max-width: 1400px;
  margin: 50px 0px;
  padding-bottom: 15px;
  border-bottom: 2px solid #9EA4B5;
}

.post p{
  justify-content: center;
  align-content: center;
  padding: 5px 0px;
  margin-right: 25px;
  margin-bottom: 0px;
  color: #425E98
}

.icon{
  opacity: 0.5;
  padding: 5px 0px;
  width: 2%;
}

.post-date {
  width: 8%;
  font-weight: 800;
}

#post-type {
  width: 12%;
  padding: 5px 15px;
  text-align: center;
  background-color: #fdf5b5;
  border-radius: 20px;
}

.post-title{
  align-self: left ;
  width: 70%;
}

.post p:hover{
  color: #c72222;
}

</style>