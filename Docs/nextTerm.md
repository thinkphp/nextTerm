Array method: nextTerm{Array: nextTerm}
=======================================

This method finds the next number in the sequence of integers using difference table.


### Syntax:

    //myArray => must be integer sequence.
    var next = myArray.nextTerm();

### Returns:

* (*number* or *boolean*) if cannot be computed difference table then return false(boolean), 
                          otherwise find the next number in the sequence and return it(number).

### Arguments:

* (*void*)

### Example:

    //example ok sequence.
    //array of integers
    var sequence = [9,73,241,561,1081,1849];
        console.log("The number that comes next in this sequence is:" + sequence.nextTerm());
        console.log(sequence.combine([sequence.nextTerm()]));

