# Swift-MathEagle
Math Eagle is named after the golden eagle, since this is the fastest bird in the world (in horizontal flight).

This project is meant to make math easy in swift. The syntax is designed to be as simple as possible. Contributors are always welcome, the more the merrier!

## Warning!
MathEagle is still in its initial development phase so the syntax still changes frequently.

#Installation
The fastest way to add MathEagle to your project is to download it as a zip file and drag all files in the MathEagle folder (except Info.plist and MathEagle.h) to your project. Make sure to add them to your target.

#Supported Xcode Versions
Math Eagle is fully compatible with:
- Xcode 6.3 (current official version)

#Currently Supported
* Basic extensions, operators like power (** operator) and functions like sign and factorial
* Prime functions
* Complex numbers
* Single variable function root solving
* Single variable function optimization
* Matrix and Vector math

MathEagle is fully generic, so almost all classes and functions work with any type (even types you define). MathEagle vectors for example can also be of type Int, while the Float and Double type vectors use Accelerate in the background for speed.

Take a look at the Wiki for documentation.

#Advantages
The biggest advantage about MathEagle is that it's totally generic. You can create matrices and vectors and use functions like isPrime with all numeric types. You can even create your own type (let's say Quaternion), implement the protocols and everything just works. Off course specific implementations are overloaded to maintain performance. Vector addition for Float vectors for example is overloaded to use the Accelerate framework.

#Benchmarking
First benchmarking tests show that MathEagle is as fast as Python's famous numpy. You can check the "Benchmarking Files" folder in MathEagle's tests.

Here are some plots for Vector addition:
![Vector Addition Float Benchmarking](/MathEagleTests/Benchmarking Files/Plot Images/VectorAdditionFloat.png)
![Vector Addition Double Benchmarking](/MathEagleTests/Benchmarking Files/Plot Images/VectorAdditionDouble.png)

#To Do
- [ ] Documentation
- [ ] Further General Development
- [ ] Incorporate Accelerate for all applications
