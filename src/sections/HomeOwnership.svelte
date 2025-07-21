<script>
  import Scroller from "../lib/Scroller.svelte";
  import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
    <Scroller layout="right">
           {#snippet sticky()}
        <iframe 
            width="600" 
            height="371"
            scrolling="no" 
            seamless frameborder="0"
            src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQAewDF5cOc7GN_cxWtqkYppWc_R-NUDioPxipEeDhO4sm7JlqebuOiiuUtpmP8a5cYHwj86IhtfW-d/pubchart?oid=2057753382&amp;format=interactive"
            title="Percent Change in Black Homeownership Rate From 2016 to 2023">
        </iframe>
        {/snippet}

        {#snippet scrolly()}
            <ArticleText>
              <h3>And ownership tells another part of the story. In 63120, just 44.6% of residents own their homes. In 63139,
                 it's 60%. Homeownership is more than just a financial asset — it's a source of stability, generational wealth, 
                 and community investment. Families who own their homes are more likely to stay, to build equity, to influence 
                 local policy, and to weather financial storms. 
                 <break></break>But the gap doesn't just exist — it's growing.</h3>                
            </ArticleText>
            <ArticleText>
            <h3>Between 2016 and 2023, the Black homeownership rate in 63120 fell by 6.7%. In 63139, it increased by 13.8%. These 
                aren't just statistics — they show how one community continues to face structural barriers to ownership while 
                another gains ground. Because when fewer people can buy homes, fewer people can build wealth. And when that's 
                repeated over decades, the distance between two ZIP codes becomes more than geography — it becomes generational.</h3>
            </ArticleText>            
        {/snippet}
    </Scroller>
</div>

