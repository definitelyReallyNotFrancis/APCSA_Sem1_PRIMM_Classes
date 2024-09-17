# PRIMM: Classes

## PRIMM
PRIMM is a Computer Science instructional strategy that is driven around inquiry-based exploration. You start off by looking at existing code and investigating what it does to modifying the code to extend its functionality to idependently creating something new using what you learned.

At first, I will ask you to hold to the PRIMM process. We won't use the strategy for every new concept, and as we move along, you will be able to move more quickly through it.

Use this document as a place to document your answers to the questions. You won't turn this document in, but
it can help supplement your notes.

## Predict
**Without running the program**, predict what its behavior is.

1. What will the program output when it is run?
    >  For Square I think that it will use a measurements for sides of a square and do mutiple things to it such as getting the perimeter and area of it. For ShapeDriver, it uses the square from the Square program and modifies the values of it in some way. It outputs the new values of the square after completing. 
2. What do you think the words `public` and `private` mean?
    > I think that are a form of global and local, meaning that publiclly assigned things can be used all across the program and private things are only used within a class or something smaller. 
3. How are the files `ShapeDriver.java` and `Square.java` related? 
    > ShapeDriver uses the Square program for its basis for the measurements of the square, so ShapeDriver is a continuation of the Square program.
4. There is no method definition for `Square()`. Do you think the code will compile? 
    > Yes, I do think the code will compile but since it uses its output straight into the ShapeDriver program I don't think it will be affected by the method definition.
5. Why do the methods/functions `getSide()` and `setSide()` exist? 
    > These are input methods that get input from the user for the sides of the sqaure, so that the prorgram can use these measurements for the sides. 

## Run
Run the program. 
1. What is the output?
    > It is outputting Side: 1.00

2. Did your prediction agree with the output? Explain where it may have differed.
    > This did not match my predicition but I believe this is because the code is not working properley. It is only outputting a side of the square, whereas in the code it seems it should also be outputting the area and perimitter of it as well. 

## Investigate
In this section, your instructor will alternate between explaining topics and tackling a `TODO` in the Modify section.
Make sure you take careful notes on the major topics.

## Modify
Starting with the `Square.java` file, resolve each of the `TODO` items. 
Once you have resolved a `TODO`, make sure to remove the text `TODO` so it doesn't 
appear on the list.

When it comes time to creating your own Unfied Markup Language visual for your custom class,
your instructor will provide you with a Google Drawing template.

## Make
Implement a brand new shape of your choice. It should store the major data for that shape and make
setter and getter method available along with a constructor that is appropriate.
Ensure you instantiate the class in the driver's `main()` method and print out the data attributes.
