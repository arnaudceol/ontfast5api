Bootstrap: docker
From: ubuntu:bionic

%runscript
    exec echo "Nothing to do!"

%environment
    
%labels
   AUTHOR tommaso.leonardi@iit.it

%post
   apt-get update && apt-get -y install python3 python3-pip
   pip3 install ont-fast5-api
doc
