#!/usr/bin/python3
# -*- coding: UTF-8
# 2021 peru doxing

import os
import time
import sys
import webbrowser

#########
#colores#
#########

BLACK = '\033[30m'
RED = '\033[31m'
GREEN = '\033[32m'
YELLOW = '\033[33m'
BLUE = '\033[34m'
MAGENTA = '\033[35m'
CYAN = '\033[36m'
WHITE = '\033[37m'
RESET = '\033[39m'
# banner facherito 
def portada():
    print("""

    \033[31m██████╗ ███████╗██████╗ ██╗   ██╗              
    \033[31m██╔══██╗██╔════╝██╔══██╗██║   ██║\033[37m       █─▄▀█──█▀▄─█             
    \033[31m██████╔╝█████╗  ██████╔╝██║   ██║\033[37m      ▐▌──────────▐▌          
    \033[31m██╔═══╝ ██╔══╝  ██╔══██╗██║   ██║\033[37m      █▌▀▄──▄▄──▄▀▐█         
    \033[31m██║     ███████╗██║  ██║╚██████╔╝\033[37m     ▐██──▀▀──▀▀──██▌           
    \033[31m╚═╝     ╚══════╝╚═╝  ╚═╝ ╚═════╝ \033[37m    ▄████▄  ▐▌  ▄████▄            
    \033[32m                                               
    ██████╗  ██████╗ ██╗  ██╗██╗███╗   ██╗ ██████╗ 
    ██╔══██╗██╔═══██╗╚██╗██╔╝██║████╗  ██║██╔════╝ 
    ██║  ██║██║   ██║ ╚███╔╝ ██║██╔██╗ ██║██║  ███╗
    ██║  ██║██║   ██║ ██╔██╗ ██║██║╚██╗██║██║   ██║
    ██████╔╝╚██████╔╝██╔╝ ██╗██║██║ ╚████║╚██████╔╝
    ╚═════╝  ╚═════╝ ╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝ ╚═════╝ 
    \033[36m                                               
    Credit Proyect Ale & Dylan\033[39m



    
        FCSH1         [menú principal de busqueda por páginas 
                           web nacionales ]
                
        FCSH2       [Herramientas útiles para recopilación de 
                            información   ]  
                
        FCSH3      [Sacar todos los datos relacionados a un 
                           número de celular : pais, compañia,ciudad, etc]

        FCSH4         [Poderosa herramienta de extracción de foto del 
                          rostro de un dni, foto de la firma y huellas
                          digitales ]
    
        FCSH5      [ Saber de quién es un número de dni ]

    
""")
def dump_opciones():
    opcion = input("Dylan@Ale: ")
    if opcion == "FCSH1":
        os.system("cd modules && python3 menu.py")

    elif opcion == "FCSH2":
        os.system("cd modules && python3 ubicacion.py")

    elif opcion == "FCSH3":
        os.system("cd modules && python3 numero.py")

    elif opcion == "FCSH4":
        os.system("cd modules && bash dni.sh")
        dump_opciones()

    elif opcion == "FCSH5":
        os.system("cd modules && bash dni2.sh")
        dump_opciones()

    elif opcion == "exit":
        print("\033[34m Módulo de doxing cerrando ...\033[39m")
        time.sleep(1)
        os.system("exit")

    elif opcion == "datos":
        print("""\033[37m
        HERRAMIENTA PROGRAMADA EN PYTHON PARA HACER MAS FACIL UN DOXEO EN PERU
        BASADA DE VARIAS PAGINAS WEB NACIONALES
        

        PROYECT BY : Dylan-Ale

        NO ME HAGO RESPONSABLE DEL MAL USO DE ESTA HERRAMIENTA, SALU2 :) \033[39m
     
        """)
        dump_opciones()
    
    elif opcion == "clear":
        os.system("clear")
        portada()
        dump_opciones()

    elif opcion == "help":
        portada()
        dump_opciones()

    else:
        print("""\033[31m
    
        Opción Invalida :(
        Intentalo nuevamente :)
        """)
        time.sleep(1.5)
        os.system("clear")
        portada()
        dump_opciones()

portada()
dump_opciones()
