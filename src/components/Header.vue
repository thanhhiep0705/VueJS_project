<template>
  <div class="header">
    <h2 >{{ header }}</h2>
    <div class="underlined"></div>
  </div>
</template>

<script>
export default {
  name: "HeaderComp",
  props: {
    header: String,
  },
};
</script>

<style>
/* .header {
    color: #2e4375;
    text-align: center;
    font-weight: 300;
    display: inline-block;
    padding-bottom: 5px;
    position: relative;
}
.header:before{
    content: "";
    position: absolute;
    width: 80%;
    height: 1px;
    bottom: 0;
    left: 10%;
    border-bottom: 3px solid red;
} */

.header {
  margin: auto;
  color: #2d3f72;
  width: fit-content;
  display: flex;
  flex-direction: column;
}
.header h2{
    margin-bottom: 20px;
}

.underlined {
  border-radius: 2px;
  height: 4px;
  margin-left: 10px;
  width: calc(100% - 20px);
  background-color: purple;
  background-image: linear-gradient(to right, #518cdc, #64c8d6);
}
</style>

