# simple-python-program
Creating simple turtle

import turtle
colors=['red','green','yellow',
        'blue','purple','orange']
t=turtle.pen()
t=speed(0)
turtle.bgcolor('black')
for x in range(360):
    t.pencolor(color[x%6])
    t.width(x/100+1)
    t.forward(x)
    t.left(59)
