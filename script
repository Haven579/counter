from tkinter import *

root = Tk()
root.title("Counter")
root.geometry("400x600")
global c

def one():
    global c
    c += 1
    entry.delete(0, "end")
    entry.insert(0, c)

def sto():
	global c
	c += 100
	entry.delete(0, "end")
	entry.insert(0, c)

def dvesti():
	global c
	c += 200
	entry.delete(0, "end")
	entry.insert(0, c)

def tisica():
	global c
	c += 1000
	entry.delete(0, "end")
	entry.insert(0, c)	

c=0
button = Button(text = "+1",command = one)
button1 = Button(text = "+100",command = sto)
button2 = Button(text = "+200",command = dvesti)
button3 = Button(text = "+1000",command = tisica)
label = Label(text = "Count")
entry = Entry(root)
label.pack(side = TOP , pady = 5)
entry.pack(side = TOP , pady = 5)
button.pack(side = TOP , pady = 5)
button1.pack(side = TOP , pady = 5)
button2.pack(side = TOP , pady = 5)
button3.pack(side = TOP , pady = 5)

mainloop()
