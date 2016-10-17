# visual-features-page
A very effective way to display your product features is a well crafted interactive features page displaying your features through images and text rather than simple lists of benefits. By combining the quality of design, visuals, and copy, you improve your ability to showcase the features of your product and/or services across. In this article, [Solodev](https://www.solodev.com/) will show you how to create a visual features page.

## Tutorial

For detailed instructions, view Solodev's [Crafting an Interactive Features Page](https://www.solodev.com/blog/web-design/crafting-an-interactive-features-page.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/0kywm71u/).

## HTML

The features page contains the following basic HTML markup.

```
<main>
<section class="container">
   <div class="row">
      <div class="col-md-10 col-md-offset-1">
         <h2 class="ct-section-header">
            BIG DATA WITH WEBCORPCO<span class="ct-section-header__separator" role="separator"><img alt="Separator" src="images/separator.png"></span>
         </h2>
         <p class="text-center">
          WebCorpCo is all about making sure your marketing stack is in alignment with your company as well as the customers you serve. There is no 'one size fits all' approach to marketing. Every business is unique, customers are unique, and your marketing should be as well.
      </div>
   </div>
</section>
<div class="container">
   <div class="row ct-choice-box__row">
      <div class="col-md-6">
         <a class="ct-choice-box business" href="/"><span class="inner"><img alt="Big Data" src="images/pic1.jpg"> <span class="ct-choice-box__header">Big Data</span></span></a>
      </div>
      <div class="col-md-6">
         <a class="ct-choice-box residents" href="/"><span class="inner"><img alt="Pattern Analysis" src="images/pic2.jpg"> <span class="ct-choice-box__header">Pattern Analysis</span></span></a>
      </div>
      </div>
         <div class="row ct-choice-box__row">
      <div class="col-md-6">
         <a class="ct-choice-box living" href="/"><span class="inner"><img alt="Data Mining" src="images/pic3.jpg"> <span class="ct-choice-box__header">Data Mining</span></span></a>
      </div>
      <div class="col-md-6">
         <a class="ct-choice-box living" href="/"><span class="inner"><img alt="Realtime Insights" src="images/pic4.jpg"> <span class="ct-choice-box__header">Realtime Insight</span></span></a>
      </div>
   </div>
</div>
</div>
<section class="container ct-isotope-gallery__container">
   <div class="row">
      <div class="col-md-10 col-md-offset-1">
         <h2 class="ct-section-header">
            we can help<span class="ct-section-header__separator" role="separator"><img alt="Separator" src="images/separator.png"></span>
         </h2>
         <p class="text-center">
         Programming not required. WebCorpCo enables marketers to manage their entire stack in one place without needing the ability to program as all code is automatically written by webcorpco.
         </p>
      </div>
   </div>
   <div class="ct-isotope-gallery">
   <div class="row">
      <div class="col-md-6">
         <div class="ct-isotope-item ct-isotope-item--medium">
            <div class="ct-isotope-item__inner accent">
               <div class="ct-isotope-item__media">
                  <img alt="Big Data" src="images/pic1.jpg">
                  <div class="ct-isotope-item__title">
                     <div class="outer">
                        <div class="inner">
                           <span>Big Data</span>
                        </div>
                     </div>
                     <div class="ct-isotope-item__arrow">
                        <img alt="Arrow" src="images/isotope-arrow.png">
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <div class="col-md-6">
         <div class="ct-isotope-item ct-isotope-item--small">
            <div class="ct-isotope-item__inner yellow">
               <div class="ct-isotope-item__media">
                  <img alt="Business Intelligence" src="images/pic2.jpg">
               </div>
               <div class="ct-isotope-item__title">
                  <div class="outer">
                     <div class="inner">
                        <span>Business Intelligence</span>
                     </div>
                  </div>
               </div>
               <div class="ct-isotope-item__arrow">
                  <img alt="Arrow" src="images/isotope-arrow.png">
               </div>
            </div>
         </div>
      </div>
      </div>
      <div class="row">
           <div class="col-md-12">
      <div class="ct-isotope-item ct-isotope-item--big" style="height: 400px;">
         <div class="ct-isotope-item__inner darkblue">
            <div class="ct-isotope-item__media">
               <img alt="Data Mining" src="images/pic3.jpg" style="height: 400px; padding-bottom: 10px;">
            </div>
            </div>
            </div>
           
            <div class="ct-isotope-item__title" style="height: 50%;">
               <div class="outer">
                  <div class="inner">
                     <span>Data Mining</span>
                  </div>
               </div>
            </div>
             <div class="ct-isotope-item__arrow">
               <img alt="Arrow" src="images/isotope-arrow.png" style="margin-right: 20px;">
            </div>
      </div>
</div>
<div class="row">
   <div class="col-md-6">
      <div class="ct-isotope-item ct-isotope-item--medium">
         <div class="ct-isotope-item__inner dark">
            <div class="ct-isotope-item__media">
               <img alt="Data Visualization" src="images/pic6.jpg">
            </div>
            <div class="ct-isotope-item__title">
               <div class="outer">
                  <div class="inner">
                     <span>Data Visualization</span>
                  </div>
               </div>
            </div>
            <div class="ct-isotope-item__arrow">
               <img alt="Arrow" src="images/isotope-arrow.png">
            </div>
         </div>
      </div>
   </div>
   <div class="col-md-6">
      <div class="ct-isotope-item ct-isotope-item--small">
         <div class="ct-isotope-item__inner blue">
            <div class="ct-isotope-item__media">
               <img alt="Global Availability" src="images/pic2.jpg">
            </div>
            <div class="ct-isotope-item__title">
               <div class="outer">
                  <div class="inner">
                     <span>Global Availability</span>
                  </div>
               </div>
            </div>
            <div class="ct-isotope-item__arrow">
               <img alt="Arrow" src="images/isotope-arrow.png">
            </div>
         </div>
      </div>
   </div>
</div>
</section>
```

## CSS

All required CSS is in features.css

## External Includes

This tutorial contains the following third party resources.

```
<link rel="stylesheet" href="features.css">
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```
