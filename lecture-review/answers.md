Question 1:
Stream abstraction is what is used to read and write data but instead of reading through a whole set of data at once it read chunks of the data.

the stream is what is being observed and the observer is what you can subscirbe the stream to.

streams are useful for detecing button clicks and sedning data and you can use it for that.

Question 2:
You could use rxjs to subscribe a stream to an observer for when abutton is clicked to send data to a newtork.

Benefits are that it can read chuncks of data instead of reading the whole data to speed up to process.

Downsides are they take longer to set up when you could just use an event listener instead of a stream and won't need to import rxjs library.

Question 3:
to stop the problem don't use global variables
the problem is that if they all use the same variable the varibale will have different value for each since it's recieveing it from the function that last used it