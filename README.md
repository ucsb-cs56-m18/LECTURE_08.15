# LECTURE_08.15
Lecture for Wednesday 08.15

Today we started by looking by discussing [Ant](https://ucsb-cs56-pconrad.github.io/topics/ant/) vs. [Maven](https://ucsb-cs56-pconrad.github.io/topics/maven), and Test Case Coverage with JacCoCo.

Some of that material is discussed here:

* <https://ucsb-cs56-pconrad.github.io/tutorials/rational_ex12/>

# Test Case Coverage

* 100% test case coverage isn't necessarily a guarantee of goodness
    * We discussed how to construct an "evil" test suite that basically acheives "all tests passing" and 100% test coverage while accomplishing very little of value (almost nothing).
* But, 0% test case coverage isn't good either.  Increasing towards 100%, if you are doing it by genuinely adding good tests, is a good thing to do.
* A key benefit of having good test coverage is the reduction in fear.  
   * You can change things without being afraid that you'll break something (especially if done in combination with version control.)
   
   
# Example of improving test case coverage

* [Version 12 of the Rational Tutorial](https://ucsb-cs56-pconrad.github.io/tutorials/rational_ex12/) has only moderately good test case coverage, as seen in [this report]()

* [Version 12 of the Rational Tutorial](https://ucsb-cs56-pconrad.github.io/tutorials/rational_ex12/) has only moderately good test case coverage, as seen in [this report]()

# We started discussing `==` vs. `.equals()`, and `.hashCode()`

We referenced the Javadoc for:

* the [`.equals()` method of `java.lang.Object`](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html#equals-java.lang.Object-)
* the [`.hashCode()` method of `java.lang.Object`](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html#hashCode--)

More on that next time.
