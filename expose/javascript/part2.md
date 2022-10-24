Q1. it will write message to the console, and the message is '3' as i = 3, i is 3 because the for loop runs 3 times as the original input has 3 prices (3 elements) and the loop goes over everyone of it, and i counts it.

Q2. the console will display '150', which is the final value of discountedPrice. As the loop inside the function runs, the last price it assigns to discountedPrice = 300 * (1-0.5) = 150, and since var variable is still holds after the code block, line 13 executes normally.

Q3. the console will display '150', which is the final value of finalPrice. As the loop inside the function runs, the last price it assigns to finalPrice is 150 rounded. Since it is var variable and is declared in the same code block, the line is executed normally.

Q4. the function will return an array of discounted prices based on the discount rate input. In this case, since the discount rate is 0.5, all items will have half of their original price in the new array. If the input is [100, 200, 300] with 0.5 discount, the function returns array of [50, 100, 150].

Q5. it will cause an error since let variable i is declared inside the for loop. Thus, as line 12 is outside of the code block that let variable i is declared, outside the code block i is undefined.

Q6. it will cause an error since let variable discountedPrice is declared inside the for loop. Thus, as line 13 is outside of the code block that let variable discountedPrice is declared, outside the code block discountedPrice is undefined.

Q7. the console will display integer '150', since line 14 is inside the code block that let variable finalPrice is declared, the conde runs normally, and how 150 is calculated is explained in Q3.

Q8. the function will return array discounted = [50, 100, 150] just as previous section. The return value is still correct because the calculation done in the for loop is still working since let variables it uses are declared in the same code block, as for loop is inside the code block of let variables declared.

Q9. it will cause an error. If we only look at line 11, the code causes error because let variable i is declared inside the for loop code block, whereas line 11 is outside the code block where i is undefined.

Q10. it will display integer '3' in the console as the length of the prices array is 3 in the input, and the const variable length is not reassigned anywhere, so the code runs normally.

Q11. the function will return array discounted = [50, 100, 150] just as previous sections. The return value is still correct because the calculation done in the for loop is still working since const variables it uses are not reassigned but rather declared again and again until the loop ends, so there is no reassigning of const variables hence no error, and discountedPrice is pushed normally to discounted. The reason why let variable i is working is explained in the previous section.

Q12. 
a) student.name
b) student['Gard Year']
c) student.greeting()
d) student['Favorite Teacher']).name
e) student.conrseLoad[0]

Q13.
A. 32           integer 2 is converted into string, so the concatenated result is'32'
B. 1            string '3' converted into integer, so it's 3 - 2 = 1
C. 3            null is 0 when converted into integer, so it's 3 + 0 = 3
D. 3null        here null is converted into string 'null', so the result is concatenated
E. 4            true is converted into integer 1, so it's numeric operation 1 + 3
F. 0            false converted to integer is 0, so as null, so it's 0 + 0 = 0
G. 3undefined   string '3' is concatenated with undefined converted into string 'undefined'
H. NaN          in mimus operation, undefined can't convert into integer, and it outputs NaN as result

Q14.
A. true         '2' is converted to integer 2, so 2 > 1 = true
B. false        '2' and '12' are both strings not integer, and as string '2' is larger than the first string of '12', is '2' is bigger
C. true         '2' is converted into integer 2, so it's 2 = 2
D. false        === comparison compare objects without conversion, so string is not equal to integer
E. false        true converted to integer is 1, so 1 != 2
F. true         boolean(2) evaluated to true, which is the same type to primitive boolean value true

Q15. == compare objects while allowing conversion, whereas === compare objects to be true only if the two objects are the same type before conversion.

Q17. the function will return array of [2, 4, 6], which every integer of the original array is doubled. This is done as the function first creates const array 'newArr', then in a for loop it uses doSomething function to double every integer from the input array, and push it to the 'newArr' array.

Q19. the output is as below, where the last integer 2 is printed 1 second later.
1
4
3
2

