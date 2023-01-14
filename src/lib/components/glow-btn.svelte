<div class="glow-button">Nos conte o seu problema</div>

<script>

</script>
  

<style lang="scss">
.glow-button {
  background-color:white; /* Green background color */
  width: 70%;
  padding: 13px;
  text-align: center; /* Center the text */
  text-decoration: none; /* Remove underline from text */
  font-size: 1rem; /* Font size for the text */
  border-radius: 5px;
  background-color: #2677BC;
  color: white;
  
  animation: glow 3s ease-in-out infinite; /* Animation for the button */
}

/* Keyframe animation to change the box-shadow */
@keyframes glow {
  from {
    box-shadow: 10 0 10px #089abe; /* Start with no box-shadow */
  }
  50% {
    box-shadow: 10px 10px 20px #089abe; /* End with a 10px box-shadow */
  }
  to {
    box-shadow: 0px 0px 00px #089abe; /* End with a 10px box-shadow */
  }
}




</style>
