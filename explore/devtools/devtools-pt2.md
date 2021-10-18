1. The bug was that the numbers were strings, so when they were added, the function concatenated the two numbers, so 1 + 1 = 11 instead of 2.
2. To fix it, I added parseInt functions on num1 and num2 so they would become integers instead of strings, and add properly instead of concatenating. 

![result-dataType](https://user-images.githubusercontent.com/74385059/137659614-75c5625d-60eb-4fd5-8aca-ecd60da4624a.png)

![result-calculateSum](https://user-images.githubusercontent.com/74385059/137659640-f05f8cac-04f0-45fa-8d9b-d2b82dbab130.png)


![fix](https://user-images.githubusercontent.com/74385059/137659849-ae19772a-0829-46bb-b4ba-6ce4664cdac0.png)
