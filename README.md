# HW3
What code draws the blades of grass?
var x = 0;
var h = 10;

function draw() {
  stroke(random(60, 70), 100, 90);
}

What code makes the "lawnmower" come by? How often does it come by?
1. if (random() > 0.999) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
  }

  fill(40, 100, 60);
  rect(0, height-10, width, 10);
}
2. 0.999

What's the point of the h variable?
Each new row of grass is taller than the previous one

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
In the second arguments of the line function，the -10 means cutting 10 from the original ordinate.
In the fourth arguments of the line function, the -10 means staying at the same ordinate as the second time.
Fo rheight-10-random(h)，cutting the grass to a height of 10 per cut and build a random height to make it look more realistic

What's the point of an object?
An object has data inside it to describe it. An object has behavior

What's an example of a range you might use for the map function?
map(mouseX, Min, Max, Min, Max)

What line of code would give me a random year in the last century?
var x = Random(1900, 1999)
