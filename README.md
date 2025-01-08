#python turtle circle inside circle
# Setup
t = turtle.Turtle()
scr = turtle.Screen()
scr.bgcolor(90, 100, 67)  # Background color set to RGB (30, 50, 12)

# Draw the first circle (red with pink fill)
t.begin_fill()
t.color("red", "pink")
t.circle(100)
t.end_fill()

# Move the turtle to the new position for the second circle
t.up()
t.goto(5, 50)  # Move turtle to coordinates (5, 50)
t.down()

# Draw the second circle (black with yellow fill)
t.begin_fill()
t.color("black", "yellow")
t.circle(50)
t.end_fill()

t.hideturtle()  # Hide the turtle after drawing is complete

# Finish
turtle.done()

