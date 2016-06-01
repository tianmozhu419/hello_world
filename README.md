# This is about my python project -- turtle package
My first repository

#early version
import turtle
def draw_square():
    window = turtle.Screen()
    window.bgcolor("red")
    
    brad = turtle.Turtle()
    brad.reset()
    brad.shape("classic")
    brad.shapesize(2,2)
    brad.settiltangle(45)
    brad.color("blue", "yellow")
    brad.speed(3)
    
    i = 0
    while i < 4:
        brad.forward(100)
        brad.right(90)
        i = i + 1
 

    angie = turtle.Turtle()
    angie.shape("turtle")
    angie.color("white")
    angie.circle(80)

    third = turtle.Turtle()
    third.shape("turtle")
    third.color("green")

    j = 0
    while j < 360:
        third.forward(100)
        third.left(120)
        j = j + 120
        
    window.exitonclick()


draw_square()
