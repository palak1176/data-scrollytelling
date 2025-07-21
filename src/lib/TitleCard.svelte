<script>
    let { title } = $props();
</script>

<div class="title-card">
    <div class="content">
        <h1>{title}</h1>       
    </div>
</div>

<style>
    .title-card {
        background-color:#f7f5eb;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        padding: 2rem;
        box-sizing: border-box;
        font-family: "Inter", sans-serif;
    }

    .content {
        max-width: 700px;
        background-color: #870819;
        padding: 2rem;
        border: 6px solid #dd747d;
        border-radius: 2rem;
        box-shadow: 16px 16px #be3048;
    }

    h1 {
        font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        font-size: 3rem;
        margin: 0;
        color: #FBFFF1;
        text-shadow: 1px 1px 0 #3066BE;
    }

    @media (max-width: 600px) {
        h1 {
            font-size: 2.2rem;
        }
       
    }
</style>
