<script>
    let { children } = $props();
</script>

<div class="article-text">
    <p>
        {@render children()}
    </p>
</div>

<style>
    .article-text {
        margin: 50vh auto;
        width: 50%;
        text-align: center;
        font-family:'Trebuchet MS'; 
        background-color: #aac2f7;
        color: #070608;
        border: solid #080A87 3px;
        border-radius: 20px;
        padding: 20px;
        box-shadow: 16px 16px #749CDD;
    }
</style>
