# This is a simple command line application that shows public IPs and servers' names from a given URL.

## Usage:
There are two main commands in this: "ips" and "names", and one flag: "host".

The "ips" command shows a list of the public IPs of a given domain. The "names" command shows a list the servers names from a given domain.

If no domain is given than the app will use the default domain that is "google.com.br".

## Example:
./command-line ips --host github.com

./command-line names --host github.com
