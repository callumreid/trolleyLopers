<script>
  let audio = new Audio('https://custom-skills-public.s3.amazonaws.com/trollilopolis/trolleyRumbleShort.mp3');

  function playSound() {
    audio.play();
  }
</script>

<div class='container' on:click={playSound}>
	<img src='https://custom-skills-public.s3.amazonaws.com/trollilopolis/images/trolleyTitle.png' alt='trolley' class='trolley' />
</div>

<audio id="train-sound" src="path-to-your-audio-file.mp3" preload="auto"></audio>

<style>
  .container {
    width: 300px;
    height: 300px;
    position: relative;
  }

  .trolley {
    width: 50px;
    height: 50px;
    position: absolute;
    top: 50%;
    left: 50%;
    animation: spin 4s linear infinite;
  }

  @keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }
</style>
