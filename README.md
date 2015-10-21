# Java 3D Core

This is a Mavenized version of the latest
[Java 3D](https://en.wikipedia.org/wiki/Java_3D) `j3dcore` component,
[built on JOGL 2.3](http://forum.jogamp.org/Java3D-now-works-with-JOGL-2-0-td3732206.html).

## Project status

This is a temporary fork, until the upstream project accepts
[hharrison/java3d-core#19](https://github.com/hharrison/java3d-core/pull/19) and
[follow-up patches](https://github.com/hharrison/java3d-core/compare/master...ctrueden:maven).

## How to use it

To use from your Maven project, add the following dependency to your POM:

```xml
<dependency>
	<groupId>org.scijava</groupId>
  <artifactId>j3dcore</artifactId>
  <version>1.6.0-scijava-1</version>
</dependency>
```

# See also

* https://github.com/scijava/java3d-utils
* https://github.com/scijava/vecmath
