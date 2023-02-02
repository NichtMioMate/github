<template>
    <div class="nachrichtencomponent">
       
      
    </div>
<div class="StartText"> 
    Hier können Sie dem Support schreiben

</div>
<div class="MessageFeld">
    <p>{{ message }}</p>
    <textarea v-model="message" placeholder="Hier können sie etwas hinein schreiben"></textarea>
</div>
 
  </template>
  
  <script>
  export default {
    name: 'NachrichtenComponent',
    props: {
      msg: String
    },
}

  </script>


  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  .StartText{
  padding-top: 100px;
  align-items: center;
  justify-content: space-between;
  font-size: 26px;


}

.MessageFeld{
  padding-top: 50px;
  align-items: center;
  justify-content: stretch;
  font-size: 26px;
  size-adjust: 100px;
  color: white;


}

textarea {
  width: 1700px;
  height: 450px;
  font-size: 25px;
  color:white;
}
  </style>