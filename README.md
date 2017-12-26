# slider-boxes
Slider boxes have become incredibly popular over recent years. They give website managers the ability to showcase more content on a cool rotating visual element. Not only does it catch a visitor’s attention, it also improves UX by giving users the ability to access that content at their own pace by triggering the next slide. They’re one of the easiest ways to showcase anything about your organization – from a client roster, customer testimonials, reviews, and images.

## Tutorial

For detailed instruction's, view Solodev's [How to Add Slider Boxes to a Website](https://www.solodev.com/blog/tutorial-tuesdays-how-to-add-slider-boxes-to-a-website.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/8w11bs53/).

## HTML

The tutorial contains the following basic HTML markup.

```
<section class="orange-fade p-5 margin-top-xl pos-r">
  <div class="container">
   	<div class="row">
		<div class="col-sm-12">
        <h2 class="text-center font-weight-bold text-white">Our Customers are Seeing Big Results</h2>
        <p></p>
       <div class="mt-5 pos-r">
          <div class="carousel-controls testimonial-carousel-controls">
            <div class="control prev"><i class="fa fa-chevron-left text-white">&nbsp;</i></div>
            <div class="control next"><i class="fa fa-chevron-right text-white">&nbsp;</i></div>
          </div>
          <div class="testimonial-carousel">
            <div class="one-slide white">
              <div class="testimonial w-100 h-100  p-3 text-center">
                <div class="message text-center text-gray">I have been working with Solodev for nearly 4 years and I couldn&#39;t be happier with the results!</div>
                <div class="separator">&nbsp;</div>
                <div class="brand"><img alt="Florida Dairy Farmers" src="https://raw.githubusercontent.com/solodev/slider-boxes/master/images/img-1.png" class="mx-auto"/></div>
              </div>
            </div>
            <div class="one-slide white">
              <div class="testimonial w-100 h-100  p-3 text-center">
                <div class="message text-center text-gray">The interface is easy for a novice user to make updates just as easily as an experienced developer.</div>
                <div class="separator">&nbsp;</div>
                <div class="brand"><img alt="Florida Department of Education" src="https://raw.githubusercontent.com/solodev/slider-boxes/master/images/img-2.png" class="mx-auto"/></div>
              </div>
            </div>
            <div class="one-slide white">
              <div class="testimonial w-100 h-100  p-3 text-center">
                <div class="message text-center text-gray">Solodev is a great company to partner with! We are extremely happy with the software, service, and support.</div>
                <div class="separator">&nbsp;</div>
                <div class="brand"><img alt="Seminole County" src="https://raw.githubusercontent.com/solodev/slider-boxes/master/images/img-3.png" class="mx-auto" /></div>
              </div>
            </div>
            <div class="one-slide white">
              <div class="testimonial w-100 h-100  p-3 text-center">
                <div class="message text-center text-gray">If you are looking for a great CMS company then Solodev is the right choice.</div>
                <div class="separator">&nbsp;</div>
                <div class="brand"><img alt="Lynx" src="https://raw.githubusercontent.com/solodev/slider-boxes/master/images/img-4.png" class="mx-auto" /></div>
              </div>
            </div>
            <div class="one-slide white">
              <div class="testimonial w-100 h-100  p-3 text-center">
                <div class="message text-center text-gray">Everyone on the Solodev team is very knowledgeable and they have been always been very responsive.</div>
                <div class="separator">&nbsp;</div>
                <div class="brand"><img alt="Miami Beach VCA" src="https://raw.githubusercontent.com/solodev/slider-boxes/master/images/img-5.png" class="mx-auto" /></div>
              </div>
            </div>
            <div class="one-slide white">
              <div class="testimonial w-100 h-100  p-3 text-center">
                <div class="message text-center text-gray">Solodev has been able to successfully keep us at the forefront of our industry and continually meet our ever adapting needs.</div>
                <div class="separator">&nbsp;</div>
                <div class="brand"><img alt="Oneblood" src="https://raw.githubusercontent.com/solodev/slider-boxes/master/images/img-6.png" class="mx-auto" /></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```

## CSS

All required CSS is in slider-boxes.scss

## JavaScript

All required JS is in slider-boxes.js

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"></script>
```

