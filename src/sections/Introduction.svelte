<script>
  import Scroller from "../lib/Scroller.svelte";
  import ArticleText from "../lib/ArticleText.svelte";
  </script>

<div>
  <Scroller layout="left">
    {#snippet sticky()}{/snippet}

    {#snippet scrolly()}
      <ArticleText>
        <p>Testing out some text</p>
      </ArticleText>
    {/snippet}
  </Scroller>
</div>
