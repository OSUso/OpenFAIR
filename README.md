# OpenFAIR
Simple FAIR simulations using R

I've had some free time and decided to give this a shot and maybe learn a thing or two on the way.

WARNING: 
a. My statistical capabilities are very limited.
b. Last time I wrote any code was maybe 15 years ago.
c. First time I use R.

If the script works as planned, it should be able to run two FAIR simulations and plot some comparison.

Data is fed through a CSV files (FAIR_input.csv). Don't mess with the structure of that file. Add and remove rows but keep the columns as is. I had a quick look at "shiny" to see how to do a GUI, but that looked too complicated and I don't have that much free time.

The simulation includes all FAIR building blocks under Loss Event Frequency but only Primary Loss Magnitude incl. the six loss categories.
I haven't figured out yet how to include secondary loss magnitude. Maybe I spend some time on that, maybe I won't.

Since there isn't a GUI, you have to do a few things manually in the code itself.

There is a section in early the code where you need to set a few variables, it looks like this:

"===== You need to change the following variables as needed ==="


As far as I can tell the confidence shape values for the ranges are: (VL=1,L=4,M=20,H=160,VH=640)
"4" is apprently the default value.

For whatever reason on my computer one of the plots doesn't show and I need to press refresh in Rstudio.

Useful resources I looked at to get this done:

David F. Severski

https://gist.github.com/davidski/8490758

https://github.com/davidski/evaluator

Jay Jacobs:

http://datadrivensecurity.info/blog/posts/2014/Jan/severski/

Open FAIR™ Tool with SIPmath™ Distributions: Guide to the Theory of Operation

https://publications.opengroup.org/g181

