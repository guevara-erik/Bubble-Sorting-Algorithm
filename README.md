# Bubble Sorting Algorithm
Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in the wrong order
his sorting algorithm is comparison-based algorithm in which each pair of adjacent elements is compared and the elements are swapped if they are not in order. This algorithm is not suitable for large data sets as its average and worst case complexity are of Ο(n2) where n is the number of items.

How Bubble Sort Works?
We take an unsorted array for our example. Bubble sort takes Ο(n2) time so we're keeping it short and precise.

![image](https://user-images.githubusercontent.com/102191236/182452002-faefd937-167b-41b3-8737-3d4f73922f4a.png)

Bubble Sort
Bubble sort starts with very first two elements, comparing them to check which one is greater.

![image](https://user-images.githubusercontent.com/102191236/182452058-e7bcc129-3699-4bf3-adc4-24a7d18a4ffd.png)


In this case, value 33 is greater than 14, so it is already in sorted locations. Next, we compare 33 with 27.

![image](https://user-images.githubusercontent.com/102191236/182452081-bc77e145-8e19-4123-90fa-17c5e504fc79.png)

We find that 27 is smaller than 33 and these two values must be swapped.

![image](https://user-images.githubusercontent.com/102191236/182452121-e20cd9b8-d970-42a2-ab27-5c1395f788cb.png)

The new array should look like this −

![image](https://user-images.githubusercontent.com/102191236/182452155-1c530342-a444-4e24-9047-4566217df3b9.png)

Next we compare 33 and 35. We find that both are in already sorted positions.

![image](https://user-images.githubusercontent.com/102191236/182452192-75ddbd55-0276-4cbc-92d3-c47afdb79535.png)

Then we move to the next two values, 35 and 10.

![image](https://user-images.githubusercontent.com/102191236/182452227-7b0eadf6-0e24-4acd-bade-db0988c6dd83.png)

We know then that 10 is smaller 35. Hence they are not sorted.

![image](https://user-images.githubusercontent.com/102191236/182452847-a8c9e3c3-9fad-4f4e-a345-93f4f9544f69.png)

We swap these values. We find that we have reached the end of the array. After one iteration, the array should look like this −

![image](https://user-images.githubusercontent.com/102191236/182452651-92cbe8e8-3896-4d96-93a8-4ea964a3e157.png)

To be precise, we are now showing how an array should look like after each iteration. After the second iteration, it should look like this −

![image](https://user-images.githubusercontent.com/102191236/182452618-82b3d627-5a4f-4fd2-b9ce-23ddcaccec15.png)

Notice that after each iteration, at least one value moves at the end.

![image](https://user-images.githubusercontent.com/102191236/182452588-6f2a5f52-0c9c-485a-ae4f-030b5c927021.png)

And when there's no swap required, bubble sorts learns that an array is completely sorted.

![image](https://user-images.githubusercontent.com/102191236/182452547-dc740cdc-e70e-428d-ba99-1b93d943380e.png)
