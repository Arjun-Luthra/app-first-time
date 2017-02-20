   <head> 
      <title>Cold or Allergy</title>  
      <meta name="viewport" content="width=device-width, initial-scale=1">
      <meta name="apple-mobile-web-app-capable" content="yes">
      <link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css" />
      <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
      <script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
   </head> 
   
   <body> 

     <div data-role="page">
	<div data-role="header">
		<h1>Cold or Allergy</h1>
	</div><!-- /header -->
<!-- Changed header from "Hello World" to "Cold or Allergy" -->
	<div data-role="content">	
		<p>This App is design to help you figure out whether you have a cold or allergy.</p>		
	</div><!-- /content -->
<!--Changed content to "This App is design to help you figure out whether you have a cold or allergy"-->
	<div data-role="footer" data-position="fixed">
		<p>This is the footer!</p>
	</div><!-- /footer -->
     </div><!-- /page -->
<!--Kept "This is footer"-->	   
   </body>
</html>
<!--Added button "Go to Page Two"-->
<a	href="#pagetwo"	data-role="button">Go	to	Page	Two</a>

<!--Created mobile page three-->
<div data-role="page"id="pagetwo">
<!--Added header to Page Two-->
	<div data-role="header">
		<h1>Cold or Allergy</h1>
	</div><!-- /header -->
<!--Added content-->
<div	data-role="content">
<!--Added content "Are your eyes watery or itchy?" to Page Two-->
<p>Are	your	eyes	watery	or	itchy?</p>
<!--Added"button" Yes-->
<!--Added "button" No-->
<!--Set "button" Yes and "button" No to page three-->
<a	href="#pagethree"	data-role="button">Yes</a>
<a	href="#pagethree"	data-role="button">No</a>
</div><!-- /content	-->

<!--Created mobile page three-->
<div data-role="page"id="pagethree">
<!--Added header to Page Three-->
	<div data-role="header">
		<h1>Cold or Allergy</h1>
	</div><!-- /header -->

<div	data-role="content">
<!--Added content "Do you have a fever?" to Page Three-->
<p>Do you have a fever?</p>
<!--Added"button" Yes-->
<!--Added "button" No-->
<!--Set "button" Yes and "button" No to shoot page four-->
<a	href="#pagefour"	data-role="button">Yes</a>
<a	href="#pagefour"	data-role="button">No</a>
	
<!--Created mobile page four-->
<div data-role="page"id="pagefour">
<!--Added header to Page Four-->
	<div data-role="header">
		<h1>Cold or Allergy</h1>
	</div><!-- /header -->
<!--Added content "Do you have a sore throat?" to Page Four-->
<!--Added"button" Yes-->
<!--Added "button" No-->
<!--Set "button" Yes and "button" No to shoot page five-->	
<div	data-role="content">
<p>Do you have a sore throat?</p>
<a	href="#pagefive"	data-role="button">Yes</a>
<a	href="#pagefive"	data-role="button">No</a>
	
<!--Created mobile page five-->
<div data-role="page"id="pagefive">
<!--Added header to Page Five-->
	<div data-role="header">
		<h1>Cold or Allergy</h1>
	</div><!-- /header -->
<!--Added content "Are your symptoms seasonal or chronic?" to page five-->
<!--Added"button" Yes-->
<!--Added "button" No-->
<!--Set "button" Yes and "button" No to shoot page six-->
<div	data-role="content">
<p>Are	your	symptoms	seasonal	or	
chronic?</p>
<a	href="#pagesix"	data-role="button">Yes</a>
<a	href="#pagesix"	data-role="button">No</a>

<!--Created mobile page six-->
<div data-role="page"id="pagesix">
	<div data-role="header">
		<h1>Cold or Allergy</h1>
	</div><!-- /header -->
<!--Added content "Do you have any rashes?" to page six-->
<!--Added"button" Yes-->
<!--Added "button" No-->
<!--Set "button" Yes and "button" No to shoot page seven-->
<div	data-role="content">
<p>Do you have any rashes?</p>
<a	href="#pageseven"	data-role="button">Yes</a>
<a	href="#pageseven"	data-role="button">No</a>

<!--Created mobile page seven-->	
<div data-role="page"id="pageseven">
<!--Added header to Page Seven-->
	<div data-role="header">
		<h1>Cold or Allergy</h1>
	</div><!-- /header -->
<!--Added header to Page Seven-->
<!--Added content "Are you experiencing any body aches?" to page seven-->
<!--Added"button" Yes-->
<!--Added "button" No-->
<!--Set "button" Yes and "button" No to shoot page eight-->
<div	data-role="content">
<p>Are you experiencing any body aches?</p>
<a	href="#pageseight"	data-role="button">Yes</a>
<a	href="#pageseight"	data-role="button">No</a>
