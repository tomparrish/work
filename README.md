## Ethics:  
         I don't publish work scripts.  I don't put them in a private repository or otherwise keep a personal version of them.  When I start a new job I show up with the experience and the knowledge, but without code.
         That said, I do feel it's appropriate to assemble a list of previous work.

## Authentication:
         All of these scripts include a call to get an authentication key at the start and to revoke the key at the end.
         These scripts have a mix of using calls to the os to get username/password info or querying the user for those details.

## Programming language:
         These are mostly written in Python.  If I've used something else I've tried to make it obvious.

## Bluecat:
  These all rely on API calls.
  ### BAM:
    1.  Query for the list of subnets using DHCP.  Assign primary DHCP server based off odd/even third octet.
    2.  Create an "A" record.
    3.  Create a "CNAME" record.
    4.  Create an External Host Record (EHR) and a "CNAME"
  ### Gateway:
    1.  Create an External Host Record (EHR)

## Cisco:
  These are a mix of API calls and NetMiko.
  ### ACI:
    1.  Get interface details and present configuration info
      a.  Perhaps 70% done as of October 2024
        1.  Meaning it logs in, does three API calls and presents info to user.
  ### Router:
    1.  Shut down BGP neighbor(s)
    2.  Bring up BGP neighbor(s)
  ### Firewall:
    1.  Query MS for list of o365 IP addresses.  Query Firewall for current Access Control List (ACL).  Create needed configuration changes and notify operations.

## Palo Alto:
  ### NGFW:
    1.  This is just a skeleton for future work.  It logs into the NGFW and runs a show command.  I would love to get a chance to develop this further, but
        Palo's GUI is fairly complete and diving into their SDK is going to give better results for most use cases.
## Bash:
  1.  A script that polls BGP time in current state from a number of devices.
  2.  A script that lists network devices in a meaningful hierarchy and allows ssh to them.
    This is an attempt to not care about naming conventions which are everywhere a waste of time and effort.
  3.  A script that checks current DNS returns vs expected values.
  4.  Honestly, probably 100s of other scripts that were only needed for a brief time and weren't worth the effort of cleaning up

## Perl, Groovy, TCL, Expect:
         I've worked in all of these, but don't feel it's useful to list out individual work because:
  ### Perl
  I loved working in Perl, but Python is better in every way.  I would move Perl work to Python.
  ### Expect
  I still use it for some quick temporary work, but always feel dirty afterwards.
  ### TCL
  I'm figuring it out when I do it.  When I start thinking about TCL my first thought is, "I can make this work, but what's the right way to do this."
  ### Groovy
  I've only used it in relation to Jenkins.  There I've only used it in the cut/paste/change_values sort of way.
