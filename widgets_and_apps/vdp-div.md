---
layout: page
title : 'The VDP Widget with IFrame'
title_parent: Widgets and apps
header : Vehicle configurator

class_page: pageWidgetSetup
---

{% include themes/twitter/widgets_and_apps/vehicle_configurator_setup.html %}

<div id="widget-placeholder"></div>
<script  type="text/javascript"  src="http://pure-wave-1620.herokuapp.com/loader.js"></script>
<script type="text/javascript">
    (function(){
    var widget = EDM.createWidget({
        "renderTo": "widget-placeholder",
        "width": 901,
        "options": {
            "apiKey": "5wxzdz9uk36tgteztydfc6e9",
            "vin": "2C3CCABG6FH814232",
            "turnOnEmbedding": "true",
            "isConfigurator": "false"
        },
        "components": [{"id":"section-2","section":"aft.creative.carRatingAndReviews"},{"id":"section-3","section":"aft.creative.trueCostToOwn"}]
    });
    }());
</script>


{% include themes/twitter/widgets_and_apps/vehicle_configurator_acordion.html %}
