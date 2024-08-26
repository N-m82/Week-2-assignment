Week-2-assignment
To properly encode the refactored code for the Student Management System, you need to ensure that string literals are enclosed in quotes and correctly use formatted strings. Below are step-by-step instructions on how to encode the existing code correctly, along with a corrected version of the code. 

 Step-by-Step Instructions

1. Ensure String Literals Are Quoted: 
   - When adding student names and majors, make sure they are enclosed in quotes (single or double).
   
2. Correct Print Formatting:
   - There is a syntax error in the `display_student` method due to the absence of an `f` before the f-string; it should be `print(f'ID: {self.id}, Name: {self.name}, Age: {self.age}, Major: {self.major}')`.

3. Use Descriptive Class and Method Names:
   - Keep your classes and methods descriptive to improve readability.

4. Test Your Code:
   - After correcting syntax errors, run the code to ensure that everything works as expected.

5. Add Comments(Optional):
   - Providing comments will improve the readability of your code for others (or for yourself in the future).
  

Here's the complete and corrected version of the Student Management System code:

```python
