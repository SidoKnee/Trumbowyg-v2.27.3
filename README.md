# Trumbowyg-v2.27.3
I have made a few changes to this wonderful Text Area editor 😁
I Love this Editor !
The Languages need a bit of work 😕
I hope that Alexandre Demode (Alex-D) does not mind 🤔
Just do this to get the Buttons to work & the Dropdowns, at the Bottom of your page.

<script>
$(document).ready(function(){
    $.trumbowyg.svgPath = '{path}/ui/icons.twc.svg';
    $.trumbowyg.svgAbsoluteUsePath = true;
	$('#simple-editor').trumbowyg({
		btns: ['viewHTML', 'formatting', 'link', 'btnGrp-semantic', 'btnGrp-lists', 'insertImage','emoji','hashtag','smiley','hands']

	});

});

</script>
