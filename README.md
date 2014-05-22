GCP-PRISS
=========

An attempt to print through PRISS at UiO with [Google Cloud Print](http://developer.google.com/cloud-print)

**Note: This project will not be started until the middle of June**

Concept
-------

Google Cloud Print is a web-based printing-service. PRISS is a printing-system at the glorious University of Oslo. They should be friends (because sometimes SSH + SCP becomes a bit complex).

TODO
----

1. Implement soft Google Cloud Print-printer in Python
2. Interface with PRISS through excessive use of sys.call()
3. ????
4. Print 

Architecture
------------

- GCP-server in python running at non-privileged user account / UiO Linux
- configfile and magical way of updating server
- data-directory for integration with PRISS (ppr) 
