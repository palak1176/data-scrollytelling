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
            seamless frameborder="0"
            scrolling="no" 
            src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQAewDF5cOc7GN_cxWtqkYppWc_R-NUDioPxipEeDhO4sm7JlqebuOiiuUtpmP8a5cYHwj86IhtfW-d/pubchart?oid=347184023&amp;format=interactive"
            title="Median Income in 63120 and 63139">
        </iframe>
        {/snippet}

        {#snippet scrolly()}
            <ArticleText>
              <h3>In 63120, the median household income was just $34,097 in 2023. That's barely enough to cover basic 
                expenses, let alone save for emergencies, buy a home, or invest in education. At this level, 
                families often have to make impossible choices: groceries or gas, rent or medicine, a utility 
                bill or a child's school supplies.</h3>                
            </ArticleText>
            <ArticleText>
              <h3>Now, drive just 30 minutes south — across a few highways, past Delmar — and you're in 63139, 
                where the median household income is $74,749. That's more than double. And with that difference 
                comes breathing room. Stability. The chance to plan for the future instead of constantly reacting 
                to the present.</h3>                
            </ArticleText>
            <ArticleText>
            <h3>The gap isn't about how hard people work. It's about what they've been given the chance to work with. 
            It's about access to jobs, banks, schools, and safe neighborhoods. It's about decades of policy decisions 
            that left some communities with fewer tools to build wealth and others with more.</h3>
            </ArticleText>            
        {/snippet}
    </Scroller>
</div>

