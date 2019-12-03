'''This project finds the area of a circle and or a triangle'''
print "The calculator is now on."
name = raw_input("Enter C for Circle or T for Triangle: ")
if name == 'C':
  radius = float(raw_input("Enter radius: "))
  area = 3.14159 * radius*radius
  print str(area)
elif name == 'T':
  base = float(raw_input("Enter the base: "))
  height = float(raw_input("Enter the height: "))
  area = base*height*.5
  print str(area)
else: 
  print "You entered an invalid letter."
print "The program is now finished."
