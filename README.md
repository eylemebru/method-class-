 namespace MethodClassExample
{
    // Creating the class with the specified method
    class MathOperation
    {
        // Method that takes two integers and performs a math operation
        public void PerformOperation(int firstNumber, int secondNumber)
        {
            // Perform a sample math operation: adding the two numbers
            int result = firstNumber + secondNumber;

            // Display the result (second integer is displayed)
            Console.WriteLine("The second number is: secondNumber");
            Console.WriteLine("The result of adding the two numbers is: {result}");
        }
    }

    class Program
    {
        static void Main(string[] args)
        {
            // Instantiating the MathOperation class
            MathOperation mathOperation = new MathOperation();

            // Calling the method with two numbers (passing in the values)
            mathOperation.PerformOperation(10, 20); // Here, 10 and 20 are the numbers passed

            // Calling the method using named parameters
            mathOperation.PerformOperation(firstNumber: 15, secondNumber: 25);
 Add comments to explain the code for understanding
            // We first create an instance of the MathOperation class.
            // Then we call the PerformOperation method and pass two numbers to it.
            // We also call the method again using named parameters to specify which value corresponds to which parameter.
        }
    }
}
```

Explanation of the Code:

1. Class Creation:  
   We create a class named MathOperation, which has a method PerformOperation. This method takes two integers, performs a simple math operation (addition in this case), and displays the second integer followed by the result of the math operation.

2. Method Overloading:  
   The method PerformOperation is called twice, once by passing parameters directly and once using named parameters, as required.

3. Comments:  
   Inline comments are provided to explain the functionality of the code, including the creation of the class, the calling of the method, and the usage of both normal and named parameters.
