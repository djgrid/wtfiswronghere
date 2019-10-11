For some reason the output on this script was different from the others. Even
the included screenshot shows things being printed out looking like it was
a tuple, for example (96, 'fizz').

I originally thought this was the problem but I could find absolutely no 
difference in the for: loop in this challenge as opposed to the others.

When I checked the screenshot .jpg it said that 99 was missing and I realized
that the range() function needs a + 1 to get the last integer.