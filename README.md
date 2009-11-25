FitText
=======

Truncates the text nodes of elements to fit inside a container

### Example:

#### HTML:

    <ul id="container">
    	<li><span>Lorem ipsum dolor</span></li>
    	<li><span>sit amet, consectetur adipisicing</span></li>
    	<li><span>elit, sed do eiusmod tempor incididunt ut labore et</span></li>
    </ul>

#### CSS:

    ul {
    	list-style: none;
    	width: 50%;
    }

    li {
    	white-space: nowrap;
    }
    
#### JavaScript

    var myFitText = new FitText('container','li > span',{
      offset: 20,
      fitClass: 'fitted'
    });
    
View the [MooDoc](http://moodocs.net/rpflo/mootools-rpflo/FitText) for usage and examples.
