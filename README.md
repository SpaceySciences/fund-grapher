# fund-grapher
A simple grapher for looking at the funds raised on the georiga funder

## Installation & Setup

You may need to change the permissions of the <code>grapher</code> file with <code>chmod +x grapher</code>

## Dependencies

* pip, depending on your system. mac: <code>brew install pip</code> or debian linux: <code>apt-get install pip</code> 
* beautifulsoup4, run <code>pip install beautifulsoup4</code>
* html5lib, run <code>pip install html5lib</code>

## USE

to run itially type: <code>./grapher</code>, and you will recieve a usage print

####example:

<code>$ ./grapher -t</code> this will return the total ammount raised

### Args
* | -t | returns the total ammount raised
* | -d | graphs the ammount raised per day
* | -v | verbose print option

