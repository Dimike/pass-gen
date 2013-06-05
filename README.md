pass-gen
========
glas=["a", "e", "i", "o", "u", "y"]

soglas=["b", "d", "g", "v", "m", "n", "w", "l", "r", "j", "d", "z", "g", "p", "t", "k", "f", "s", "c", "h"]






3.times do


x=rand(5)

case x

when 0
print soglas[rand(soglas.size)]
print glas[rand(glas.size)]
print soglas[rand(soglas.size)]
when 1
print soglas[rand(soglas.size)]
print glas[rand(glas.size)].capitalize
print soglas[rand(soglas.size)]
when 2
print soglas[rand(soglas.size)].capitalize
print glas[rand(glas.size)]
print soglas[rand(soglas.size)]
when 3
print soglas[rand(soglas.size)]
print glas[rand(glas.size)]
print soglas[rand(soglas.size)].capitalize
when 4
print soglas[rand(soglas.size)].capitalize
print glas[rand(glas.size)]
print soglas[rand(soglas.size)].capitalize
when 5
print soglas[rand(soglas.size)]
print glas[rand(glas.size)].capitalize
print soglas[rand(soglas.size)].capitalize


end
end
