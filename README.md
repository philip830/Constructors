# Constructors

Constructors are especially useful in creating and using Objects. Javascript alone uses single objects, but Constructors give the programmer the power to create an object “type” that can be used as a template of sorts for creating many objects of that “type”:

function person(first, last, age, eye) {
    this.firstName = first;
    this.lastName = last;
    this.age = age;
    this.eyeColor = eye;
}
var myFather = new person("John", "Doe", 50, "blue");
var myMother = new person("Sally", "Rally", 48, "green");

In the above example, “person” is the Object constructor, and myFather and myMother are “new” objects of the same Object “type.”

The “this” keyword is the Object that owns the Javascript code. “This” is not a variable – it can only be used as a specific value:

When used in a function, it is the Object that “owns” the function.
When used in an object, it is the Object.

The intention of this homework was to use Constructors to change a previous assignment from vanilla Javascript to Javascript with Constructors, giving the student an understanding of the utility and power of Constructors.
