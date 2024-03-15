<script>
    let photo = "https://www.w3schools.com/w3images/lights.jpg";
    let myphoto = './photo.jpg';
</script>


<!--<img src= {photo} alt="Light" class="circle-border"/>-->
<img src= {myphoto} alt="Light" class="circle-border"/>
<!---
<img src="./photo.jpg" alt="Light" class="circle-border"/>
<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
-->

<style>
    .circle-border {
        width: 250px;
        height: 250px;
        border: 5px solid #eebbc3;
        border-radius: 50%; 
        text-align: center;
        display: flex;
        margin: 0 auto;
	}
</style>