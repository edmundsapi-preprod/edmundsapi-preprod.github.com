---
layout: api-documentation
title : 'Get Vehicle Recalls by Car Model Year ID'
title_active_left_menu: 'Service: Recalls'
title_parent: Api documentation

amount_version: 1
title-endpoint: 'Get Vehicle Recalls by Car Model Year ID'
spec: service_recalls
version: v1
api: vehicle
dropdown-link: 'v1/api/maintenance/recallrepository/findbymodelyearid'


level: 3
description_edpoint: 'Get Vehicle Recalls by Car Model Year ID'
title_md : Description
number: 1

---

### Description

Get list of manufacturer recalls for vehicles with model year ID

### URL

	https://api.edmunds.com/v1/api/maintenance/recallrepository/findbymodelyearid?modelyearid={model year ID}&fmt=json&api_key={api key}
	
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
				var options = {
					"modelyearid": "100502677"
				};

				// Callback function to be called when the API response is returned
				function success(res) {
					var body = document.getElementById('results-body');
					body.innerHTML = "The recall is: " + res.recallHolder[0].defectDescription;
				}

				// Oops, Houston we have a problem!
				function fail(data) {
					console.log(data);
				}

				// Fire the API call
				res.api('/v1/api/maintenance/recallrepository/findbymodelyearid', options, success, fail);

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