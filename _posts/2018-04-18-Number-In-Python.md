---
layout: post
title:  "Number in Python"
author: sourabh
categories: [ jumpstart ]
image: 
---

<span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">Integers, floating point and complex come under numbers.</span> <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">We can use the type() function to know which class a variable or a value belongs to and the�isinstance() function to check if an object belongs to a particular class</span> **<span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">Integer�</span>** <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">An Integer type holds an integer value or a whole number that can be a negative or positive value, like -5, -4, 0, 8, 9, 10 and so on. In the Python you can declare an integer value such as in the following:</span> <iframe src="https://repl.it/@Sumn/Integer?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe><span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">But in the preceding example, you cannot determine the type of the variable.�So in Python, we have a function by which we can get the type of a variable. The function is as in the following:</span> **<span style="font-size: 12.0pt; line-height: 107%; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA;">type(variable)</span>** **<span style="font-size: 12.0pt; line-height: 107%; font-family: 'Calibri',sans-serif; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 'Times New Roman'; mso-hansi-theme-font: minor-latin; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; color: #666666; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA;">Example</span>**<iframe src="https://repl.it/@Sumn/type-of-integer?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe>

<div style="box-sizing: border-box; color: #212121; font-family: 'open sans', sans-serif;"><span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">We can represent any integer variable in�Decimal�or�Octal�or�Hexa-Decimal�format. **In Decimal**</span> <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">In decimal you can write directly your Python variable as in the following:</span> <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">a=12 **In Octal**</span> <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">In Octal you can represent such as in the following: a=0O14</span> <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">or</span> <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">a=0o14</span></div>

<iframe src="https://repl.it/@Sumn/Octal?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe>�

<div id="pastingspan1" style="box-sizing: border-box; color: #212121; font-family: 'open sans', sans-serif;">**<span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">In�Hexa-Decimal�</span>** <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">You can represent any integer variable as a Hexa-decimal such as in the following: a=0XC</span> <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">or</span> <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">a=0xC</span><span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">�</span> **<span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">Example</span>**</div>

<div style="box-sizing: border-box; color: #212121; font-family: 'open sans', sans-serif;"><iframe src="https://repl.it/@Sumn/hexa-Decimal?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe></div>

<div style="box-sizing: border-box; color: #212121; font-family: 'open sans', sans-serif;">**<span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">Float</span>** <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">They represent real numbers and are written with a decimal point dividing the integer and fractional parts.</span> **<span style="font-size: 12.0pt; line-height: 107%; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA;">Example�</span>**

<div style="box-sizing: border-box;"><iframe src="https://repl.it/@Sumn/float?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe><span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">We can also represent a floating point number in�E notation.</span> **<span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">Fraction</span>** <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">In Python, you can also create a type that can hold fractional numbers, like 1/2, 3/5 and so on. To create a Fractional type of number you must import�the�"fractions"�module. Then you need to create a fraction object.</span> <span style="font-family: Arial, sans-serif;">�</span></div>

<iframe src="https://repl.it/@Sumn/fraction?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe>

<div style="box-sizing: border-box;"><span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">Not only that, you can also operate fractional numbers.</span> **<span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">Example</span>**</div>

<iframe src="https://repl.it/@Sumn/fraction-22?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe>

<div style="box-sizing: border-box;">**<span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">Complex</span>** <span style="font-size: 12.0pt; font-family: 'Arial',sans-serif; mso-fareast-font-family: 'Times New Roman'; color: #666666;">In Python, you can create a Complex type variable that will have a real part as well as an imaginary part, like 3 + 5i. Here the real part is 3 and the imaginary part is 5\. To create the complex type of variable in Python we have a function called�complex(real_part, imaginary_part)�that takes two arguments, a real part and an imaginary part. **Example**</span><iframe src="https://repl.it/@Sumn/complex-number1?lite=true" width="100%" height="400px" frameborder="no" scrolling="no" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" allowfullscreen="allowfullscreen"></iframe></div>

</div>