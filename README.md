Gograb uses ssh and a proxy host to "go get" things for you.  Go does not need
to be installed on the proxy.  Gograb expects you to be using a release
version of Go.  The appropriate Go binary distribution is downloaded to the
proxy every time you use gograb, so mind the data usage.  Go is only used to
aquire source code on the proxy; nothing is compiled remotely.  All work is
done in a temporary directory and cleaned up afterward.  Bash 4 is required.
Hopefully you will never need to use this, but if you do, here it is.
