# pjax.uix
A modified version of extension for jQuery Pjax.

Based on https://github.com/defunkt/jquery-pjax


 Version added:

- Add a option to increase stream delay.
- Add a callback or a collection of callbacks to a callback list. 
- Increase a function of ui show to load an file.
- Fires asynchronously with each click event


### Last Usage: 

``` js

//Trigger
$( document ).pjax( 'a[data-pjax], [data-pjax] a', '#main', {
	showHTMLdelay: 0,
	startEvent: function( button ){
		//alert( button.attr( 'href' ) );

	},
	endEvent: function( button ){
		//

	}
});

//Remove pjax link
$( 'a[data-remove-pjax]' ).attr( 'usepjax', 1 );
```
