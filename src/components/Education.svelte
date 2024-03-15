<script>
    let info = [
        { title: "Degree", content: "Bachelor's Candidate in Electrical Engineering" },
        { title: "Expected Graduation Time", content: "JUN-2025" },
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