# I am the Badass

print('{}Hello, world.{}'.format('\033[34m', '\033[m')

x = 0
ok = True
while ok:
    print(f'{x}')
    x += 1
    if x == 10:
        ok = False