Q1: print 3, because we declare i with var, so i will be +1 for every each for loop. so prices.length is 3, I will be +1 for 3 times from 0. like 1, 2, 3. Thus print i = 3.

Q2: 150. because we assign discountedPrice per every for loop. so first discountedPrice is 50 by 100 * (0.5), second discountedPrice is 100 by 200 * (0.5), and Third discountedPrice is 150 by 300 * (0.5). We did only repeat 3 times, so final discountedPrice value is 150. 

Q3: 150. I think is same with q3. like finalPrice will be 50, 100, 150 after each for loop. and we assiged finalPrice with var, so we can use in any scope in function. so last finalPrice value will be 150 and printed it out.

Q4: function will return [50, 100, 150]. We pushed the finalPrice to empty list for every for loop. first iteration, push 50 to discounted list, second push 100 to discounted list, and third push 150 to discounted list and return that list.

Q5: makes an error, because we defined i with the let, so we can use i only in the block that declared, but we call console at the out of let declaration block.

Q6: makes an error, because we defined discountedPrice with the let, so we can use discountedPrice only in the block that delcared, but we call console at the out of let declaration block.

Q7: 150, because we declare finalPrice with let into the function block. We used finalPrice in the function blokc not in for block. it means same block, so we can use that variable.

Q8: [50, 100, 150],  because we declare discounted with let into the function block. We used discounted in the function block not in for block. it means same block, so we can use that variable.

Q9:makes an error, because we defined i with the let, so we can use i only in the block that declared, but we call console at the out of let declaration block.

Q10: print 3, because we declare length with const declaration with the prices.length. prices length is 3. so 3 assigned in length it cannot reassigned.

Q11: return [50, 100, 150]. we do assign with const declaration for each for loop, so it is not reassigned, thus discountedPrice will be 50, 100 ,150 for each loop, and we push each value to discounted list. 

Q12: A. student.name
     B. student["Grad year"]
     C. student.greeting()
     D. student["Favorite Teacher"].name
     E. student.courseLoad[0]

Q13: A. '32' since integers map to their exact string representation.
     B. 1  since - will be arithmetic operators.
     C. 3  since null represents the absence of any value.
     D. '3null' since integers map to their exact string representation.
     E. 4 when the plus operator is placed between a number and a boolean, the boolean is converted into a number in js. True coverted to 1.
     F. 0  since same above, false converted to 0, and null is absence of any value thus 0.
     G. '3undefined' since integers map to their exact string representation.
     H. NaN since NaN meaning not a number, '3'- undefined, cannot be parsed

Q14: A. true, since Javascript converts the values to number, 2 > 1 true
     B. false, since compare first character 2 > 1 
     C. true, since == compare only value 
     D. false, since === compare not only value, but also data type
     E. false, true value = 1
     F. true, Boolean(any value) will return true

Q15: == : equal to , === equal value and equal type.

Q17: Result : [ 2, 4, 6] , since we passed a function into another function, so we push to newArr after call doSomething function.

Q19: 1 4 3 2
