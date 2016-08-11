# masterd-nanosystem
The first fully-automated nano-daemon designed to drive large-scale genomic image data systems at 454 Life Sciences / Roche Diagnostics

masterd ran from /usr/locl/bin and simply kept feeding jobs to the automated document delivery system, including all image and signal processing (very large processing tasks requiring compute clusters), then eventually processed by the "locoweb" web server which provided results data in human-readable format. The daemon ran uninturrupted across distributed systems for over 10 years without modification or failure (and rediculously low down time). The concept is too simple to fail!
