# mrdp
Docker version of ESnet's Modern Research Data Portal

Chard K, Dart E, Foster I, Shifflett D, Tuecke S, Williams J. 2018. The Modern Research Data Portal: a design pattern for networked, data-intensive science. PeerJ Computer Science 4:e144 https://doi.org/10.7717/peerj-cs.144

https://github.com/globus/globus-sample-data-portal

The above repo is included in this one as a submodule. 

If you clone this repo normally, you must do the following to get MRDP in the right place:

git clone https://github.com/edubergeek/mrdp.git
git submodule init
git submodule update

You can avoid the extra steps if you add the --recurse-submodules option when cloning this repo.

e.g. 

git clone --recurse-submodules https://github.com/edubergeek/mrdp.git

