
## CBRAIN APIs

This repository contains libraries for accessing the [CBRAIN platform](https://github.com/aces/cbrain). One particular instance of this platform is the Montreal Neurological Institute's [CBRAIN Service](https://portal.cbrain.mcgill.ca/).

Two languages are currently supported:

* Ruby; the API can be found in the file ``ruby/cbrain_ruby_api.rb``
* Perl; the API can be found in the file ``perl/CbrainPerlAPI.pm``

The full documention about these APIs can be generated locally
by running a bash script provided at the top of the repository,
``install_doc.sh``. It can also be browsed online at the
CBRAIN service site:

* [CBRAIN API, Perl, plain text](https://portal.cbrain.mcgill.ca/doc/APIs/perl/CbrainPerlAPI.txt)
* [CBRAIN API, Perl, HTML](https://portal.cbrain.mcgill.ca/doc/APIs/perl/CbrainPerlAPI.html)
* [CBRAIN API, Ruby, HTML](https://portal.cbrain.mcgill.ca/doc/APIs/ruby/CbrainRubyAPI.html)

## Obsolescence Warning

These APIs are no longer maintained, and the CBRAIN platform has evolved since then, and as such might only work partially. They can still be used if one is willing to make adjustments.

The new CBRAIN API is being developed and documented here:

* [CBRAIN Swagger API description](https://portal.cbrain.mcgill.ca/swagger)

## Credits

This project's code was originally a part of the CBRAIN platform
(released separately), but the API itself was funded by [CANARIE](http://www.canarie.ca/)
during the summer of 2014.

