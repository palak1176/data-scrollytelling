<script>
  import Scroller from "../lib/Scroller.svelte";
  import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
    <Scroller layout="left">
           {#snippet sticky()}
        <iframe 
            width="600" 
            height="371"
            scrolling="no" 
            seamless frameborder="0"
            src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQAewDF5cOc7GN_cxWtqkYppWc_R-NUDioPxipEeDhO4sm7JlqebuOiiuUtpmP8a5cYHwj86IhtfW-d/pubchart?oid=1258591400&amp;format=interactive"
            title="Poverty Line">
        </iframe>
        {/snippet}

        {#snippet scrolly()}
            <ArticleText>
              <h3>And perhaps the clearest indicator of all — poverty. In 63120, 30.2% of residents lived below the poverty 
                line in 2023. That's nearly 1 in 3 people. Just across Delmar, in 63139, the poverty rate was just 7.3%. 
                That's not just a number — that's fewer children going to school hungry, fewer parents juggling multiple jobs, 
                fewer seniors choosing between medicine and rent. It's a daily difference in stress, in stability, in dignity.</h3>                
            </ArticleText>
            <ArticleText>
            <h3>But even here, even in a ZIP code shaped by decades of disinvestment, there are signs of resilience. From 2016 to 
                2023, poverty among Black households in 63120 dropped by 4.8%. That’s a real, meaningful shift. In 63139, the drop 
                was 4.5% — still progress, but it shows that even in the face of structural inequities, communities like 63120 are 
                moving forward.</h3>
            </ArticleText>  
            <ArticleText>
            <h3>The gap remains — but so does the will to close it.</h3>
            </ArticleText> 
        {/snippet}
    </Scroller>
</div>

