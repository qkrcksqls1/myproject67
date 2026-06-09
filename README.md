# myproject67
Web VPython 3.2

b=sphere(pos=vec(-48, 10, 0), radius=6, texture = "https://upload.wikimedia.org/wikipedia/commons/thumb/b/be/Deutsches_Fu%C3%9Fballmuseum_2015_2-Fevernova.jpg/1280px-Deutsches_Fu%C3%9Fballmuseum_2015_2-Fevernova.jpg")
c=sphere(pos=vec(-32, 10, 0), radius=6, texture = "https://upload.wikimedia.org/wikipedia/commons/9/9f/Teamgeist-STG-CRO-AUS.jpg")
d=sphere(pos=vec(-16, 10, 0), radius=6, texture = "https://upload.wikimedia.org/wikipedia/commons/thumb/5/57/Adidas_Jabulani_Official_World_Cup_2010_%284158450149%29.jpg/330px-Adidas_Jabulani_Official_World_Cup_2010_%284158450149%29.jpg")
e=sphere(pos=vec(48,  10, 0), radius=6, texture = "https://upload.wikimedia.org/wikipedia/commons/2/25/Al-Rihla_%28cropped%29.jpg")
f=sphere(pos=vec(32, 10, 0),  radius=6, texture = "https://i.ebayimg.com/images/g/Np8AAOSwlLBnjA9w/s-l400.jpg")
g=sphere(pos=vec(16, 10, 0),  radius=6, texture = "https://m.media-amazon.com/images/I/815QFCZwWHL._AC_UF894,1000_QL80_.jpg")

ccc = [color.red, color.white, color.green, color.magenta, color.black, color.yellow, color.cyan, color.purple, color.orange]
while True:
    rate(100)
    k=keysdown()
    if '1' in k:
        b.color=ccc[0]


    if '2' in k:
        b.color=ccc[1]
    if '3' in k:
        b.color=ccc[2]
    if 'q' in k:
        c.color=ccc[3]
    if 'w' in k:
        c.color=ccc[4]
    if 'e' in k:
        c.color=ccc[5]
    if 'a' in k:
        d.color=ccc[6]
    if 's' in k:
        d.color=ccc[7]
    if 'd' in k:
        d.color=ccc[8]
    if 'z' in k:
        e.radius=0.5
    if 'x' in k:
        e.radius=2
    if 'c' in k:
        e.radius=5
    if '4' in k:
        f.opacity=0.2
    if '5' in k:
        f.opacity=0.5
    if '6' in k:
        f.opacity=2
    if 'r' in k:
        g.pos=vec(0,0,10)
    if 't' in k:
        g.pos=vec(10,0,0)
