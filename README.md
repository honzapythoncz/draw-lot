#losování
from random import randrange
for x in range(1):#randomizér výherních čísel
    a=randrange(1000)#hlavní výhra
    b=randrange(100)#sekundární výhra
    c=randrange(10)#ostatní výhra č.1
    d=randrange(10)#ostatní výhra č.2
    e=randrange(5)#potato výhra
for f in range(251):#hl. výhra
    a_nahoda=randrange(1000)
    if a_nahoda == a:
        if f < 250:
            print('Gratuluji vyhrál jsi hlavní výhru.')
            break
        else:
            print('Počítač si nemůže dovolit víc losů a zkrachoval.')
    else:
        print('Počítač si nemůže dovolit víc losů a zkrachoval u hl. výhry.')
        break
for g in range(251):#sek. výhra
    b_nahoda=randrange(100)
    if b_nahoda == b:
        if g < 250:
            print('Gratuluji vyhrál jsi sekundární výhru výhru.')
            break
        else:
            print('Počítač si nemůže dovolit víc losů a zkrachoval u sek. výhry.')
            break
    else:
        print('Počítač si nemůže dovolit víc losů a zkrachoval u sek. výhry.')
        break
for h in range(251):#ost. výhra č.1
    c_nahoda=randrange(10)
    if c_nahoda==d:
        if h < 250:
            print('Gratuluji vyhrál jsi ostatní výhru č.1 .')
            break
        else:
            print('Počítač si nemůže dovolit víc losů a zkrachoval u ost. výhry č.1.')
    else:
        print('Počítač si nemůže dovolit víc losů a zkrachoval u ost. výhry č.1.')
        break
for ch in range(251):#ost. výhra č.2
    d_nahoda=randrange(10)
    if d_nahoda==d:
        if ch < 250:
            print('Gratuluji vyhrál jsi ostatní výhru č.2 .')
            break
        else:
            print('Počítač si nemůže dovolit víc losů a zkrachoval u č.2.')
    else:
        print('Počítač si nemůže dovolit víc losů a zkrachoval u ost. výhry č.2.')
        break
for i in range(251):#potato výhra
