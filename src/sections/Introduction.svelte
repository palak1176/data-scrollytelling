<script>
  import Scroller from "../lib/Scroller.svelte";
  import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
  <ArticleText><h3>What's the difference between 63120 and 63139?</h3></ArticleText>
  <ArticleText><h3>You might say 19.</h3></ArticleText>
  <ArticleText><h3>But these 2 numbers aren't just numbers. They represent two ZIP codes, 
                divided by just one street in St. Louis, Missouri: Delmar Boulevard.</h3></ArticleText>
    <Scroller layout="right">
        {#snippet sticky()}
            <!-- svelte-ignore a11y_img_redundant_alt -->
            <img src="zip-codes.png" alt="A picture of 63120 and Delmar Blvd" />
        {/snippet}

        {#snippet scrolly()}
            <ArticleText>
              <h3>To the north lies 63120 — a community that's 89.8% Black, where disinvestment has spanned generations.</h3>
            </ArticleText>
            <ArticleText>
              <h3>To the south is 63139 — just 16.1% Black, whiter, wealthier, and historically protected from the same policies that drained its neighbor."</h3>
            </ArticleText>
        {/snippet}
    </Scroller>
  <ArticleText><h3>They're only minutes apart. But when it comes to wealth, opportunity, and access, the gap between them is vast.</h3></ArticleText>
  <ArticleText><h3>As you scroll, we’ll travel down Delmar — not just across distance, but across history, policy, and the numbers that still shape lives today.</h3></ArticleText>

</div>
