Java Fundamentals: Dec 3 - 7 2012
=================================

Best Practices
--------------

Maintainability:

  * Consider block depth and method length as useful measures of code complexity.
  * If a method is too deep or too long, refactor it: extract helper methods.

Class Recipe:

  * `private` fields (mostly immutable, `final` fields whenever possible)
  * Constructor to initialize immutable (and possibly other) fields
  * Getter methods and setter methods
  * Structural identity: `hashCode` and `equals` - use only final fields
  * Optionally: other methods

Object Identity
---------------

Reference identity

  * do the references point at the same or different objects on the heap?
  * `a == b`

Structural identity

  * do the objects have the same properties/state?
  * `a.equals(b)`

Videos
------

Day 1:

  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/1.1.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/1.2.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/1.3.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/1.4.mov

Day 2:

  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/2.1.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/2.2.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/2.3.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/2.4.mov

Day 3:

  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/3.1.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/3.2.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/3.3.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/3.4.mov

Day 4:

  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/4.1.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/4.2.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/4.3.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/4.4.mov

Day 5:

  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/5.1.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/5.2.mov
  * https://mrkn.s3.amazonaws.com/recordings/java-fundamentals-cisco-20121203/5.3.mov

Miscellaneous Resources
-----------------------

  * https://marakana.com/static/courseware/java_fundamentals/index.html