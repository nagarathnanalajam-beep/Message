
import turtle as t

t.bgcolor("black")
t.pensize(5)
t.speed(1)

t.color("red")
t.begin_fill()
t.fillcolor("red")

t.left(150)
t.forward(180)
t.circle(-90, 180)

t.setheading(60)
t.circle(-90, 180)

t.forward(180)
t.end_fill()

t.hideturtle()

msg = "I LOVE YOU"

t.penup()
t.goto(0, -50)
t.color("white")

t.write(
    msg,
    move=True,
    align="center",
    font=("Arial", 25, "bold")
)

t.done()
