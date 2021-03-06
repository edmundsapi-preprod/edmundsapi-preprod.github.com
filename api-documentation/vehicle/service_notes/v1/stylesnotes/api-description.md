---
layout: api-documentation
title : 'Get Service Notes by Car Style ID'
title_active_left_menu: 'Service: Notes'
title_parent: Api documentation

amount_version: 1
title-endpoint: 'Get Service Notes by Car Style ID'
spec: service_notes
version: v1
api: vehicle
dropdown-link: 'v1/api/maintenance/stylesnotes/{style ID}'


level: 3
description_edpoint: 'Get Service Notes by Car Style ID'
title_md : Description
number: 1

---

### Description

Get maintenance notes about a specific vehicle by its style ID.

### URL

	https://api.edmunds.com/v1/api/maintenance/stylesnotes/{style ID}?fmt=json&api_key={api key}
	
### Code Example

You need the [Javascript SDK](https://github.com/EdmundsAPI/edmunds-javascript-sdk) to run this example.

	<!DOCTYPE html>

	<html>
	<head>
		<meta charset=utf-8>
		<title>Edmunds API Example</title>
	</head>

	<body>
		<div id="results-body"></div>
		<script>
		  	window.sdkAsyncInit = function() {
		    	// Instantiate the SDK
				var res = new EDMUNDSAPI('YOUR API KEY');

				// Optional parameters
				var options = {};

				// Callback function to be called when the API response is returned
				function success(res) {
					var body = document.getElementById('results-body');
					body.innerHTML = "The note is: " + res.maintenanceStyleNotesHolder[0].note1;
				}

				// Oops, Houston we have a problem!
				function fail(data) {
					console.log(data);
				}

				// Fire the API call
				res.api('/v1/api/maintenance/stylesnotes/101353967', options, success, fail);

			    // Additional initialization code such as adding Event Listeners goes here
		  };

		  // Load the SDK asynchronously
		  (function(d, s, id){
		     	var js, sdkjs = d.getElementsByTagName(s)[0];
		     	if (d.getElementById(id)) {return;}
		     	js = d.createElement(s); js.id = id;
		     	js.src = "path/to/sdk/file";
		     	sdkjs.parentNode.insertBefore(js, sdkjs);
		   }(document, 'script', 'edmunds-jssdk'));
		</script>
	</body>
	</html>