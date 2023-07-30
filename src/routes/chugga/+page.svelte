
<div class="container">
	<img src="https://custom-skills-public.s3.amazonaws.com/trollilopolis/images/trolleyTitle.png" alt="trolley" class="trolley" />
</div>


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