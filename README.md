# Armadillo
Armadillo is an *XML based* secure backup script for AWS S3. It gathers any files and folders you specify, archives them, encrypts and/or signs them using *GnuPG* and finally uploads them to your S3 bucket. For more details see the comments in demo-config.xml and armadillo script.

I originally wrote Armadillo to explore [newLISP](http://www.newlisp.org/) as an alternative to python shell scripts and to have a small utility that would encrypt my backups before beaming them to S3.