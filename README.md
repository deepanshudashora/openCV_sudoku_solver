# opencv_sudoku_solover

In this sudoku solver I am uploading the image of sudoku and trying to solve it with opencv and cnn model

First The image Processing part comes where The image is transformed and enhanced

Input Image :

![](images/1.png)

Transformed Image:

![](images/4.png)

So first The preprocessed the image which is in final_output file.

for that I also needed a model which can detect which image sudoku is having in that particular grid for this model I used mnist dataset.

now I am taking the imput data preprocessing it and fitting into the model after this i am making a sudoku with it and fitting it into the solver function.

now when sudoku is solved i am getting the output image

![](images/scanned_one.png)

![](images/final_output.png)
