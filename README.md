# Inspect-elemant
ඔය යට තියන කොඩ් එක කොපි පෙස් කරගන්න 


javascript:(function () { 
    var script =  document.createElement('script');
    script.src="//cdn.jsdelivr.net/npm/eruda"; 
    document.body.appendChild(script);
    script.onload = function () { 
        eruda.init() 
    } 
})();
