Important info.


This script should be activaded in the console 
You can exit out the tab and it will still run.
To stop the script refresh the page.
You can change the pps by changing the interval on the numbers that say "100" in the code

/* 1) Open https://popcat.click 2) Open console (F12) 3)Insert code & run */ var event = new KeyboardEvent('keydown', { key: 'g', ctrlKey: true }); setInterval(function(){ for (i = 0; i < 100; i++) { document.dispatchEvent(event); } }, 0);
    
            
For example change it to "900"

/* 1) Open https://popcat.click 2) Open console (F12) 3) Insert code & run */ var event = new KeyboardEvent('keydown', { key: 'g', ctrlKey: true }); setInterval(function(){ for (i = 0; i < 900; i++) { document.dispatchEvent(event); } }, 0);
        
And it will click 900 pps
Have fun!
