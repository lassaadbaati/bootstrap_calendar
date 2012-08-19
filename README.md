BIC Calendar
============

ca - BIC Calendar es un simple calendari per marcar esdeveniments. Un plugin de jQuery i Twitter Bootstrap.

en - BIC Calendar is a simple calendar to mark events, a jQuery plugin and Twitter Bootstrap.


Dependencias
------------

- ~jQuery 1.7.2
- ~Twitter Bootstrap 2.0

Use
---
<script>
$(document).ready( function(){
	//create a array [data, text, link, color] 
	var events = [
		[ '21/1/2010', 'SENTMENAT', '', '#999' ],
		[ '23/5/2012', 'SANTA COLOMA DE GRAMENET  - Barcelonès Nord', 'http://ca.gettingcontacts.com/events/view/gramanet', '#999' ]
	];
        //create the calendar
        $('#calendari_lateral').bic_calendar({
		events: events
        });
} );
</script>

Example
-------

[http://gettingcontacts.com](http://gettingcontacts.com)
