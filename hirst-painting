# import colorgram
#
# rgb_colors = []
# colors = colorgram.extract('heistdot.jpg',30)
# for color in colors:
#     r = color.rgb.r
#     g = color.rgb.g
#     b = color.rgb.b
#     new_color = (r, g, b)
#     rgb_colors.append(new_color)
#
# print(rgb_colors)
import turtle as turtle_module
import random

turtle_module.colormode(255)
tim = turtle_module.Turtle()
tim.speed("fastest")
tim.penup()
tim.hideturtle()
color_list = [(198, 166, 109), (141, 77, 54), (73, 98, 123), (158, 148, 54), (213, 203, 144), (120, 39, 29), (137, 160, 179), (70, 108, 74), (144, 176, 139), (195, 91, 70), (69, 52, 46), (96, 81, 89), (60, 52, 56), (224, 177, 163), (102, 141, 131), (97, 130, 164), (156, 141, 159), (49, 60, 83), (73, 67, 50), (111, 38, 42), (47, 56, 72), (108, 136, 140), (182, 199, 183), (182, 190, 205), (168, 101, 106), (51, 76, 61)]
tim.setheading(225)
tim.forward(300)
tim.setheading(0)
number_of_dots = 100

for dot_count in range(1, number_of_dots + 1):
    tim.dot(20, random.choice(color_list))
    tim.forward(50)

    if dot_count % 10 == 0:
        tim.setheading(90)
        tim.forward(50)
        tim.setheading(180)
        tim.forward(500)
        tim.setheading(0)

screen = turtle_module.Screen()
screen.exitonclick()
