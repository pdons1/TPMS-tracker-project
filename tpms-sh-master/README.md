# tpms-sh
Shell script for adding the TPMS project from ACI onto your computer
PARTS LIST
Laptop that runs the latest version of Ubuntu (https://ubuntu.com/download/desktop)
(21.95) RTL-SDR USB dongle (https://www.amazon.com/RTL-SDR-Blog-RTL2832U-Software-Defined/dp/B0129EBDS2/ref=asc_df_B0129EBDS2/?tag=hyprod-20&linkCode=df0&hvadid=309707619534&hvpos=1o1&hvnetw=g&hvrand=17863131408284977176&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9004277&hvtargid=pla-760665313632&psc=1)
An antenna of your choice that is compatible with the RTL-SDR


rtl_433 -M newmodel -f315m  -S all -R 59 -R 60 -R 82 -R 88 -R 89 -R 90 -R 95 -R 110 -R 123
After installing the appropriate code from this repository, in terminal enter the line of code above to execute the program.
