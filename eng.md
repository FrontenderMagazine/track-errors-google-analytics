I try this, but when last param is added, I didnt see the request to analytics
..  
This works: 

    _gaq.push(['_trackEvent', 'JavaScript Error', 'test tracking', 'file:10' ]);

This doesn’t: 

    _gaq.push(['_trackEvent', 'JavaScript Error', 'test tracking', 'file:10', true ]);