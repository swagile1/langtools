## v0.0.3  2020-04-23

* Added `.String()` and `.Clone()` methods to the `Version` struct.

* Used [enumer](https://github.com/alvaroloes/enumer) to generate a
  `.String()` method for the `ParsedAs` type.

* Changed the `version.Compare` func so that versions of different length
  compare as equal when both end in one or more segments of zeroes. In other
  words, `1.0` and `1.0.0` are now treated as equal.


## v0.0.2  2020-03-05

* Add the `pkg/name` package for name normalization.


## v0.0.1  2020-03-05

* Initial release
