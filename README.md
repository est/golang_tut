A tutorial for GoLang
=====================


Install
-------

because PPA or apt-get is shit, use [this](http://blog.labix.org/2013/06/15/in-flight-deb-packages-of-go) instead


https://godeb.s3.amazonaws.com/godeb-amd64.tar.gz

curl  "https://godeb.s3.amazonaws.com/godeb-386.tar.gz"  | tar -zxvf - 
sudo chmod a+x godeb




Mistakes 
--------


    buf := [512]byte

syntax error: unexpected semicolon or newline, expecting {


corret use:

    buf := make([]byte, 512)
    var buf [512]byte