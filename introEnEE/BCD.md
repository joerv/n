Encodes 0-9 using 4 bits

most commonly weighted as 8421

## gray code
shaft encoders

only one bit changes > less errors
### convert from gray to binary 
* MSB stays the same
* Add each generated bit of the binary code to the next adjacent bit of the gray
code
* disregard carries

###example
Convert 10110 to gray code

binary 10110  
gray   11101

11101<sub>gray</sub>


###example
convery 11101<sub>gray</sub> to binary

gray   11101  
binary 10110<sub>2</sub>
