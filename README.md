# Procedures-Triangle

import turtle

def triangle_draw(x,y,sz):
    turtle.speed(5)
    turtle.penup()
    turtle.goto(x,y)
    turtle.pendown()
    for i in range(3):
        turtle.forward(sz)
        turtle.left(60)
        turtle.left(60)
        
for y in range (-100,100,20):
    for x in range (-100,100,20):
        triangle_draw(x,y,10)
