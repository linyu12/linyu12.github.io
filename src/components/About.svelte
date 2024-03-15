<script>
    import Section from "./Section.svelte";

    let info = [
        { title: "Name", content: "LIN-CHENG-YU" },
        { title: "School", content: "National Tsing Hua University" },
        { title: "Department", content: "Department of Electrical Engineering" },
    ];
</script>

    <Section>
        {#each info as { title, content }}
        <p><strong>{title}: </strong>{content}</p>
        {/each}
    </Section>

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
