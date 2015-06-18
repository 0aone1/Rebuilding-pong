# Rebuilding-pong

import pygame

pygame.init()
scr = pygame.display.set_mode((800,600))
x = 100
y = 100
post = (x,y)
color = (100, 0, 200)
radius = 10
xflip = False

while True:
    if xflip = False
        x+=1
        pygame.draw.circle(scr, color, post , radius)
        pygame.display.flip()
        if x>= 800
            xflip = True
    else:
        x-=1
        pygame.draw.circle(scr, color, post, radius)
        pygame.display.flip ()
        if x<= 0
            xflip = False
            
    for e in pygame.event.get():
                pass
