import tkinder as tk

def saludar(): 
    nombre = entrada_nombre.get()
    etiqueta_saludo.config(text=f"¡Hola, {nombre}!")

ventana = tk.Tk()
ventana.title ("Diseño con Grid")

ventana.columnconfigure(0, weight=1)
ventana.columnconfigure(1, weight=3)

etiqueta_nombre_inst = tk.Label(ventana, text="Nombre:")
etiqueta-nombre_inst.gird(row=0, column=0, padx=5, pady=5, sticky="w")

entrada_nombre = tk.Entry (ventana)
entrada_nombre.grid(row=0, column=1, padx=5, pady=5, sticky_="ew")

boton_saludar = tk.Button (ventana, text="saludar", comand=saludar) 
boton_saludar.grid(row=1, column=0, columnspan=2, padx=5, pady=10)

etiqueta_saludo=tk.Label(ventana, text="")
etiqueta_saludo.grid (row=2, column=0, columnspan=2, padx=5, pady=5)

ventana.mainloop()