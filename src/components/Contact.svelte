<script>
    let info = [
        { title: "Email", content: "linyu@gapp.nthu.edu.tw" },
    ];
</script>


    {#each info as { title, content }}
    <p><strong>{title}: </strong>{content}</p>
    {/each}


<style>
    strong {
        font-weight: bold;
        color: #fffffe; /* Optionally change the color */
        font-size: 20px;
        margin-left: 60px;
        padding-right: 10px;
    }
    p {
        color: #b8c1ec;
    }
</style>