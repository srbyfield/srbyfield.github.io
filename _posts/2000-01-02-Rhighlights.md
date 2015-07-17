---
title: "research highlights"
bg: silver
color: black
fa-icon: laptop
runtime: shiny
---

### My Co-Author Network

I generated this graph with some custom code using perl, R and shiny. 


The graph is generated using a bibtex file containing all my publications. Using custom perl scripts I extract the number of papers each unique pair of co-authors share. With this information I use the R package `igraph` to generate a graph object detailing the relationships between authors. Following this, I use the R package `shiny` to generate the reactive graph. It should be fairly easy to see that there are really two "groups" of authors, one european and on from the USA (from my PhD and first post-doc respectively). The code will soon be available on github.

<iframe src="https://xlevolutionist.shinyapps.io/simple_couthor_network" width="1100" height="980">
  <p>Your browser does not support iframes.</p>
</iframe>   

<br/> 
<br/>


### Genetic Drift Simulations

Check out the simple genetic drift simulator. It is written using R and [Shiny](http://shiny.rstudio.com). It is remarkably straight forward to make these reactive plots using R. 

<iframe src="https://xlevolutionist.shinyapps.io/shiny_drift" width="100%" height="720">
  <p>Your browser does not support iframes.</p>
</iframe>   

<br/> 
<br/>       
         
### Copy-number variants (CNVs) in wild maize


I am currently developing a novel CNV calling pipeline, currently in testing. Preliminary data (see figures below) suggest that the pipeline is working well and we have identified a ~10 MB deletion on chromosome 6 segregating in a wild population of maize (otherwise known as teosinte). 
Furthermore we note that estimates of [Tajima's D](https://en.wikipedia.org/wiki/Tajima's_D) over regions where CNV segregate differ from the background "genome-wide" level.
       
<div style="padding-right: 15px;text-align:center">
    <a href="img/fig_2 copy.jpeg"><img src="img/fig_2 copy.jpeg" alt="deletion" title="chr 6 deletion" width="350" border="5" onClick="_gaq.push(['_trackEvent', 'IMGs', 'Image', 'Ironman']);"></a>  
    <a href="img/fig_6 copy.jpeg"><img src="img/fig_6 copy.jpeg" alt="TD" title="TD across the genome" width="250" border="5" onClick="_gaq.push(['_trackEvent', 'IMGs', 'Image', 'Ironman']);"></a>      
</div>   

<br/> 
<br/>       
         
### The ancient sub-genomes of cotton  

Previous work has examined gene loss following ancient whole genome duplication (WGD; sometimes called [polyploidy](https://en.wikipedia.org/wiki/Polyploid)) in the cotton lineage. I showed that gene loss (sometimes called fractionation) following WGD is ongoing and bias between the duplicate sub-genomes. I further suggested that this process is the result of differing recombination rates between sub-genomes. Read the full story [here](http://mbe.oxfordjournals.org/content/32/4/1063).

<div style="float;padding-right: 15px;text-align:center">
    <a href="img/cottonWGD.png"><img src="img/cottonWGD.png" alt="cotton WGDs" title="cotton WGDs" width="600" border="5" onClick="_gaq.push(['_trackEvent', 'IMGs', 'Image', 'Ironman']);"></a>        
</div> 

<div style="float;padding-right: 15px;text-align:center">
    <a href="img/sRNA_TE.tiff"><img src="img/sRNA_TE.tiff" alt="siRNAs" title="siRNA is the ancient sub-genomes of cotton" width="600" border="5" onClick="_gaq.push(['_trackEvent', 'IMGs', 'Image', 'Ironman']);"></a>        
</div> 
    

<br/> 
<br/>       
               
         
### Repetitive DNA loss in tobacco  

My PhD work focused on the evolution of repetitive DNA in tobacco. Mostly the work focused on the use of fluorescent *in situ* hybridisation (FISH) and a custom build of an NGS clustering algorithm called [RepeatExplorer](http://www.repeatexplorer.org) which identifies and quantifies repeatitive sequences in complex genomes.

<div style="text-align:center">
<a class="twitter-timeline" href="https://twitter.com/SimonByfield/favorites" data-widget-id="614239767882960897">Favorite Tweets by @SimonByfield</a> <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>   
</div>

<br/> 
<br/> 

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-64425631-1', 'auto');
  ga('send', 'pageview');

</script>

