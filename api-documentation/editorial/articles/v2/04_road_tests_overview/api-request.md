---
layout: api-documentation
title : 'Get road tests overview'
title_active_left_menu: 'Articles'
title_parent: Api documentation

amount_version: 2
title-endpoint: 'Get road tests overview'
spec: articles
version: v2
api: editorial
dropdown-link: 'api/editorial/v2/{make}/{model}/{year}/roadtests'


level: 4
description_edpoint: 'Get road tests overview'
title_md : Sample Request
number: 4

---

###Sample Request

Get Audi A3 2013 overview.

#### URL

    https://api.edmunds.com/editorial/v2/honda/accord/2013/roadtests?view=basic&api_key={API key}&fmt=json

#### Response

    {
      make: {
        name: "Honda",
        niceName: "honda"
      },
      model: {
        name: "Accord",
        niceName: "accord"
      },
      year: {
        id: 100537293,
        year: 2013
      },
      articles: [
        {
          tags: [
            "Full Test",
            "Sedan",
            "2013 Honda Accord EX",
            "Hybrid",
            "Coupe"
          ],
          description: "Edmunds full test of the redesigned 2013 Honda Accord EX. Includes on-road driving impressions, instrumented test data, specs, photos and more.",
          introduction: "<p>Honda needs a winner.</p> <p>Between a drift from its traditional engineering-driven principles and the tsunami that devastated its factories, the last four years haven't been kind to the H brand.</p> <p>Nonetheless, the company has redesigned its Accord midsize sedan for the eighth time in its history. It's hardly an overstatement to say that the Accord is both the bread and butter of Honda's lineup, as Americans snatch these babies up at a rate of more than 1,000 per day.</p> <p>The ninth-generation 2013 Honda Accord sedan arrives September 19 with new looks and new bones underneath. Struts replace its traditional double-wishbone front suspension and a continuously variable transmission (CVT) takes the place of a traditional automatic transmission on models with the all-new 2.4-liter four-cylinder engine. There's also a revised <a href="/honda/accord/2013/road-test1.html">V6 Accord</a> with an all-new six-speed automatic.</p> <p>In other words, in four-cylinder guise, the new Accord is now virtually identical to every other volume-selling midsize sedan peddled in the U.S.</p> <p><strong>Different. Just Like Everybody Else</strong><br /> Nearly every car in the midsize segment offers a similar-size four-cylinder engine, ample interior space and about the same fuel economy as the new Accord. Progress, it seems, is measured less on fundamentals and more on feature content and styling. And few manufacturers venture far from vanilla when it comes to styling their volume models.</p> <p>Even so, the ever-increasing pressure to deliver miserly fuel consumption is the driving force behind Honda's first-ever direct-injected four-cylinder engine. Rated at 185 horsepower and 181 pound-feet of torque, the new engine comes paired to the six-speed manual transmission as standard, but our EX model has the optional $800 CVT, which replaces the old car's five-speed automatic.</p> <p>The switch to a CVT helps deliver the 2013 Honda Accord's EPA estimated 27 city/36 highway/30 combined mpg ratings, placing it second in the fuel economy race behind the <a href="/nissan/altima/2013/road-test.html" >Nissan Altima</a>. As importantly, the CVT, during around-town driving, performs more intuitively than most we've driven. Its simulated upshifts feel natural and will likely fool all but the most observant drivers into thinking it's a conventional automatic. Wood it getting on the freeway, however, and the unrelenting high-rpm engine howl is present until you lift.</p> <p>Howl as it might, we still recorded 26.3 mpg during 537 miles of combined driving, which handily trumps the 24.1 mpg we recorded over 841 miles in our last test of a 2012 four-cylinder Accord just <a href="/hyundai/sonata/2012/comparison-test.html" >this April</a>.</p> <p><strong>It's Worth It</strong><br /> Honda illustrates the promise of improved acceleration through graphs showing the new Accord to be above and to the right of the old Accord. This, in engineer and PR speak, is universal language for "better."</p> <p>Still, we insist on judging acceleration the old-fashioned way: We measure it. And in this regard there's no argument. It is better. Considerably so.</p> <p>Our 2013 Honda Accord test car whirred its way to 60 mph in 7.8 seconds (7.5 seconds <a href="/car-reviews/features/how-we-test-cars-and-trucks.html">with 1 foot of rollout</a> as on a drag strip). That's a full second better than the old Accord four-cylinder. The quarter-mile, too, is quicker in the new car. The traps whistle past in 15.8 seconds at 91.2 mph, a milestone that required 16.4 seconds in last year's model.</p> <p>During 60-to-0 brake testing, the pedal lacked the confidence we'd prefer, as it softened after multiple stops. The final distance, at 128 feet, was a bit long for the class, as it almost always is with Honda products.</p> <p><strong>Underpinnings</strong><br /> Honda's choice to torpedo the Accord's double-wishbone front suspension in favor of struts seems at first like a poor one for a car proffered as engaging to drive. Double wishbones provide camber control throughout their stroke which generally leads to better handling, although you'd have a hard time selling that line to BMW and Porsche.</p> <p>On the surface, lower cost seems to drive the move, but a full redesign &mdash; especially one as comprehensive as this &mdash; can take years to reap financial benefits. Honda says the decision is driven by weight loss and the need to package a more robust crash structure into the chassis at the upper strut mount.</p> <p>The added strength, say Honda officials, improves performance in the Insurance Institute for Highway Safety's Overlap Barrier Test, where the car is driven into a small fixed object (think pole or tree) just off center at 40 mph. In combination with high-strength steel at critical points, the Accord's unibody is 57 pounds lighter than before and that's without considering the additional savings made by eliminating the old suspension's upper control arm. But at 3,320 pounds, our EX model tipped the scales only 31 pounds lighter than last year's Accord EX tester.</p> <p><strong>It Still Handles</strong><br /> What's more, Honda insists the new suspension hits all its internal handling targets, and after driving it both on the road and through our instrumented tests it's hard to argue otherwise. No midsize sedan is going to engage a dedicated driving enthusiast, but some will certainly repel us. Toyota's Camry LE, for example, is largely successful at this task by demonstrating the dynamic apathy of a sofa bed.</p> <p>The 2013 Honda Accord, however, does not. Its low-effort electrically assisted steering lacks the arbitrary weight of its predecessor but provides ample feel to guide the car prudently between the cones or down a rough back road. Damping, too, is tuned to return genuine body control. As a result we found ourselves hustling the Accord at a respectable pace in places we wouldn't bother with in much of its competition.</p> <p>At 65.5 mph through our slalom, the 2013 Accord was 2.1 mph quicker than the 2012 model, so its ultimate capabilities are clearly improved. It equaled the outgoing car on the skid pad, where both circled at 0.83g, which is at the top of the class.</p> <p><strong>Bucking the Trend</strong><br /> It's a fact common to both the midsize and compact segments that the cars are increasing in size. Bigger and bigger they've grown until, in some cases, they have outsized their larger brethren. This, of course, makes for some uncomfortable positioning. Honda, however, keenly avoided the problem by not offering a car bigger than the Accord (save the <a href="/honda/accord-crosstour/2010/">Accord Crosstour</a>, but who's counting?). And for 2013 it has eliminated the issue altogether by making the new Accord smaller.</p> <p>This Accord sedan is downsized 3.5 inches in overall length and 0.9 inch in wheelbase (to 109.3 inches) yet it gains front and rear headroom. Front legroom remains the same, while rear legroom increases by 1.3 inches. Trunk volume also increases by 0.8 cubic foot.</p> <p>That, friends, is what happens when a company returns to its engineering roots. Inside, this is a big car. Only dimensional deviants will have trouble sitting in the backseat. Even large passengers are comfortable behind a 6-foot driver.</p> <p>What's more, Honda redesigned the Accord's front seats and eliminated the not-quite-low-enough-to-be-lumbar back support that generated complaints during our long-term 2008 Accord test.</p> <p><strong>Interior Attention</strong><br /> Considerable attention was paid to minimizing the button-heavy center stack and simplifying the primary controls. Along with a new one-piece dashboard, the center stack benefits from buttons that divide functions by category. The cleaner interface is both more efficient to use and better-looking.</p> <p>Mercifully, pairing your cellphone via Bluetooth no longer requires voice commands and the necessary manual reading that inevitably accompanies them. An 8-inch screen in the dash accommodates everything from navigation (EX-L models only) to a back-up camera display and is also standard in every Accord. Dual-zone climate control is included on all trims, but you'll still have to tap buttons to set your preferred temperature. Bluetooth and the Pandora music-streaming app are both standard and well integrated for easy use.</p> <p>Another notable standard feature is the Active Noise Control system, which uses the audio system speakers to cancel road noise. We tested it and found that it worked, although it only made our tester as quiet as a Camry. But with interior noise traditionally high in Honda products, this is progress. So is the standard (on EX models and above) keyless start and entry.</p> <p>Another new feature on EX level models and above is the LaneWatch system, which displays the car's blind spot on the in-dash screen. The system is triggered via the right turn signal and its 80-degree view is useful in judging gaps and moving confidently between lanes.</p> <p>Hondalink is Honda's means to support Internet services via your smartphone in a presentation formatted for use in the car. Available only on EX-L level sedans and EX level coupes, the system can do everything from reading your Twitter feed to finding you a new Thai restaurant via Yelp. Again, it's well integrated, so it's actually useful instead of being just another electronic toy that goes unused.</p> <p><strong>A Winner?</strong><br /> Our 2013 Honda Accord EX rang up a $26,195 as-tested price, which is only $200 more than last year's model. It's hard to argue that the additional performance, efficiency and feature content aren't worth the bump in cost.</p> <p>More importantly, this Accord is a Honda again &mdash; a case we've been unable to plead for several models in recent years. Many traditional Honda benefits feature prominently here. Visibility, thanks to a relatively low waistline, is better than in most cars in the segment. Materials and assembly quality appear to be at or above past Honda standards and, to our eyes, it even looks better than the car it replaces.</p> <p>That Honda needs a winner in the new Accord is clear. After our drive, we would say it has one.</p> <p><em>The manufacturer provided Edmunds this vehicle for the purposes of evaluation.</em></p>",
          link: {
            rel: "related",
            href: "http://www.edmunds.com/honda/accord/2013/road-test"
          },
          style: {
            id: 200434856,
            name: "EX 4dr Sedan (2.4L 4cyl CVT)",
            submodel: {
              body: "Sedan",
              modelName: "Accord Sedan",
              niceName: "sedan"
            }
          },
          title: "2013 Honda Accord EX Road Test",
          authors: [
            {
              name: "Josh Jacquot"
            }
          ]
        }
      ],
      articlesCount: 1
    }