---
layout: page
title: Photos
---

<div class="diy-slideshow">
	<figure>
		<img src="{{ site.baseurl }}/_photos/2016-08-04 09.13.28.jpg" width="100%">
		<figcaption>2016-08-04 09.13.28.jpg</figcaption>
	</figure>
	<figure>
		<img src="{{ site.baseurl }}/_photos/2016-08-04 10.15.37.jpg" width="100%">
		<figcaption>2016-08-04 10.15.37.jpg</figcaption>
	</figure>
	<figure>
		<img src="{{ site.baseurl }}/_photos/20160804_112752.jpg" width="100%">
		<figcaption>2016-08-04 11.27.52.jpg</figcaption>
	</figure>
	<figure>
		<img src="{{ site.baseurl }}/_photos/20160804_112910.jpg" width="100%">
		<figcaption>2016-08-04 11.29.10.jpg</figcaption>
	</figure>
	<figure>
		<img src="{{ site.baseurl }}/_photos/20160804_163453.jpg" width="100%">
		<figcaption>2016-08-04 16.34.53.jpg</figcaption>
	</figure>
	<figure>
		<img src="{{ site.baseurl }}/_photos/20160804_175158.jpg" width="100%">
		<figcaption>2016-08-04 17.51.58.jpg</figcaption>
	</figure>
	<span class="prev">&laquo;</span>
  	<span class="next">&raquo;</span>
</div>

<script>
	(function(){
  
		var counter = 0, // to keep track of current slide
		    $items = document.querySelectorAll('.diy-slideshow figure'), // a collection of all of the slides, caching for performance
		    numItems = $items.length; // total number of slides

		// this function is what cycles the slides, showing the next or previous slide and hiding all the others
		var showCurrent = function(){
		  var itemToShow = Math.abs(counter%numItems);// uses remainder (aka modulo) operator to get the actual index of the element to show  
		  
		  // remove .show from whichever element currently has it 
		  // http://stackoverflow.com/a/16053538/2006057
		  [].forEach.call( $items, function(el){
		    el.classList.remove('show');
		  });
		  
		  // add .show to the one item that's supposed to have it
		  $items[itemToShow].classList.add('show');    
		};

		// add click events to prev & next buttons 
		document.querySelector('.next').addEventListener('click', function() {
		     counter++;
		     showCurrent();
		  }, false);

		document.querySelector('.prev').addEventListener('click', function() {
		     counter--;
		     showCurrent();
		  }, false);
		  
	})();  
</script>