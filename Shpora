from tkinter import *
from tkinter import ttk  
from tkinter.messagebox import showinfo

root = Tk()
root.title("Шпаргалка-фигалка")
root.geometry("250x200")  

def keyw():
    m = {"гугл":'BI54f6428e165w53wA','гос':'8y~twUyZ_',
         'опера':'ФeФweФцrцfцf5', 'сайт':'admin89/85123658798E',
         'авито':'8986565656565/WEYU987987', 'харбр':'Ertb@mail.ru/SRTYFV',
         'небо':'t198780987Soo', 'авито2':'865413232158455/atytytyty5',
         'катя':'8989898989898', 'танки':'a97987@mail.ru/Sorfyt9816','слава':'9098798987987'}
    key = entry.get() 
    label["text"] = (m.get(key))
                    
entry = ttk.Entry(width=50,justify=CENTER)
entry.pack(anchor=NW, padx=38, pady=6)


label = ttk.Label(text='Введите ключ')
label.pack(anchor=CENTER, padx=20, pady=4)
 
btn = ttk.Button(text="Нежно нажать тут", command =keyw)
btn.pack(anchor=CENTER, padx=46, pady=6)

label = ttk.Label(text='спонсор разработки \n    сайт Stoptut.ru ♥ ', font=("Times New Roman", 8),foreground='Blue')
label.pack(anchor=CENTER, padx=40, pady=20) 
  
root.mainloop()
