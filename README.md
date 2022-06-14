import turtle as t

t.speed(100)

tu = t.Turtle()

t.bgcolor("black")

for i in range(360):
    tu.color("indigo")
    tu.circle(i)
    tu.left(5)

t.done()

