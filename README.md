donut.go is a Go implementation of [Andy Sloan's donut.c](http://www.a1k0n.net/2011/07/20/donut-math.html).

It demonstrates:

* 3d rendering in a terminal window with ascii characters
* determining the terminal screen size
* using a channel as a timer

## Usage ##

To run:

	$ go run donut.go


## Notes ##

The code was tested on Mac OSX Mountain Lion. The Go Syscall defines appear portable, but your milage may vary.

## License ##
The code is available at github [GaryBoone/GoDonut](https://github.com/GaryBoone/GoDonut) under [MIT license](http://opensource.org/licenses/mit-license.php).
