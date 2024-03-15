<script>
    let info = [
        { title: "Programming Languages", content: "C++, Python" },
        { title: "Web Development", content: "HTML, CSS, JavaScript" },
        { title: "Software Tools", content: "MATLAB, Verilog, Arduino" },
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
        margin-left: 50px;
        padding-right: 10px;
    }
    p {
        color: #b8c1ec;
    }
</style>