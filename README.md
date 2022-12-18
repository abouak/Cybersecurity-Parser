# Cybersecurity-Parser
The parser will ready from cybersecurity vulnerabilities from a JSON list and execute changes on the Windows register.

The customer has a number of cybersecurit vulnerabilities on several systems, the script shall function as an executable
file and will read from JSON list containing the name, registry location and keys to add or change depende on the vulne-
rability. To add more values to the list an API is provided which will read from a normal text file the vulnerabilit and
include it the in JSON file.

The script also counts with a logger, which on every execution will create a txt file with the name of the 
computer, the current user, the time and date and the changes in the registry in case there is an error the error will
be logged, the logger will contain the previous values of the registry and the new ones. 



