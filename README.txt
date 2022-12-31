# iwebaudit
[Tools] iWebAudit will scan a list of web servers and grab all their titles. By only reading a little bit from each server's response, this makes reporting only the titles much faster.

------------------------------------------------------------------------------
 iWebAudit v1.5 - Web Page Title Analyzer, Alton Johnson (alton@vonahi.io)  
------------------------------------------------------------------------------ 

 Usage: iwebaudit -f <file> -o <output file> -v -h -t 5

   -f <file>   Supports list of IPs and/or http[s]:// formatted IPs.
   -o <file>   Outputs the results to a file of your choice.
   -h          Enables HTTP PUT Method Discovery. (optional)
   -t <secs>   Sets default timeout. Default is 5. (optional)
   -v 	       Displays details as script runs. (optional)

