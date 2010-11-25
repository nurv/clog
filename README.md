# Catalina 

Some web applications generate lots of exceptions and dump exaggerated amounts of stacktraces. clog can remove, or shorten those stacktraces and also prove some syntax highlight.

## Usage

Start clog with:

	$ clog

Check the last 100 lines from the log:

	$ clog 100
	
If you want only to see the first five lines of the stacktrace:

	$ clog -st 5
	
If you want to see the full stacktrace:

	$ clog -e 100


