<script>
  import Scroller from "../lib/Scroller.svelte";
  import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
    <Scroller layout="right">
        {#snippet sticky()}
            <img class="redlining"src="redlining.png">
            <a href="https://reports.mysidewalk.com/59cc324517#c-485819">
            St. Louis Redlining District Designation in 1937 Overlapped with Non-White Population Percentages</a>
        {/snippet}

        {#snippet scrolly()}
            <ArticleText>
              <h3>In the 1930s, federal agencies created color-coded maps to guide mortgage lending based 
                on perceived 'risk'. But these maps didn't just reflect economic risk — they reinforced 
                racial boundaries. Economically successful white neighborhoods were shaded green and 
                blue, earning them easier access to mortgages and government-backed investment.</h3>                
            </ArticleText>
            <ArticleText>
            <h3>Black communities were shaded yellow or red, often not because of property conditions, 
                but simply because of who lived there. These designations made it much more difficult 
                for residents to secure fair loans, and many lenders charged much higher interest rates 
                or avoided these areas entirely. This wasn't an accident though, it was federal policy.</h3>
                </ArticleText>
            <ArticleText>
            <h3>Over time, the impact multiplied. Without equal access to homeownership — one of the 
                main ways to build generational wealth in the United States — families in red- and yellowlined 
                neighborhoods had fewer chances to invest in their futures. Public and private dollars followed 
                the maps. Neighborhoods labeled 'high risk', like those north of Delmar Boulevard, were often 
                left behind.</h3>                   
                </ArticleText> 
            <ArticleText>
            <h3>Meanwhile, just south of Delmar, the story was different. Loans were more accessible. Homes 
                gained value. Wealth grew — and in many cases, was passed down. Decades later, the legacy 
                of those policies is still visible in the data.</h3>                
                </ArticleText>
                <!-- <a href="https://www.thesaintlouisstory.org/history-1/1935-redlining">
                    More Information about Redlining in St. Louis</a>     -->                
        {/snippet}
    </Scroller>
</div>

<style>
.redlining {
    width: 90%;
    margin: 0px auto;
}

a {
    font-family:'Trebuchet MS';
    text-align: center;
    padding: 3%;
}
</style>

