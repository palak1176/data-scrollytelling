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
            seamless frameborder="0"
            scrolling="no" 
            src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQAewDF5cOc7GN_cxWtqkYppWc_R-NUDioPxipEeDhO4sm7JlqebuOiiuUtpmP8a5cYHwj86IhtfW-d/pubchart?oid=337991730&amp;format=interactive"
            title="Median Home Value of Owner-Occupied Homes with Mortgages">
        </iframe>
        {/snippet}

        {#snippet scrolly()}
            <ArticleText>
              <h3>In 63120, the median home value was just $55,200 for owner-occupied homes with a mortgage in 2023. In 63139, 
                it was nearly four times higher at $206,500. Even when no mortgage is involved, the disparity remains: 
                $50,500 versus $183,000.</h3>                
            </ArticleText>
            <ArticleText>
              <h3>But this isn't just about numbers on Zillow. A higher home value means more generational wealth — the 
                kind that helps families pay for college, fund retirements, or weather financial emergencies. It means 
                stronger public school funding, since property taxes often feed directly into local education budgets. 
                It means more leverage when taking out loans or selling a home. It means a sense of long-term security.</h3>                
            </ArticleText>
            <ArticleText>
            <h3>In contrast, low property values can trap families in a cycle. Their home — often their largest asset — 
                doesn't appreciate the way it does across town. That limits both their financial growth and their ability 
                to pass wealth on to the next generation.</h3>
            </ArticleText>
            <ArticleText>
            <h3>And ownership tells another part of the story. In 63120, just 44.6% of residents own their homes. In 63139,
                it's 60%. Homeownership is more than just a financial asset — it's a source of stability, generational wealth, 
                and community investment. Families who own their homes are more likely to stay, to build equity, to influence 
                local policy, and to weather financial storms.</h3> 
            </ArticleText>     
        {/snippet}
     </Scroller>  
</div>     
     

 