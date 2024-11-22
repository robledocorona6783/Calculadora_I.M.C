# Calculadora_I.M.C

Para el proceso de crear este programa inicie de la forma más simple, un formulario que recabara los datos del usuario, un input por dato y listo, posteriormente ui a hacer el calculo del IMC y paramtrizar en que estado estaba el usuario (flaco, normal, sobrepeso, obesidad etc,), y finalmente presentar la información.

Luego releyendo las indicaciones me di cuenta que no debia dejar datos vacios, primero lo hice con ifs, comparando un dato vacio con la funcion (if dato == "":), pero de esa forma el proceso no se repetia infinitamente hasta que llenaran el dato, solo lo repetiria tantas veces como pusiera ifs, ademas de tener que poner el resto del texto en todos los ifs haría mucho codigo, por lo que cambie a usar whiles, esta forma resultó mas efectiva ya que con solo un comando repetiria la instrucción hasta que el usuario llenara la información, sin embargo con los datos que eran valor numerico me encontre con otro problema, no podía comprarlos a vacio igual que las valores de tipo str, intente con varias formas (.isInteger, True or False), y tuve que recurrir a internet para encontrar un manera de ver como validar variables que sean numericas, despues de eso y mucha tabulación finalmente quedó.

Al día siguiente decidi agregarle una rutina para repetir el programa que adapte de un programa en c que vi en Youtube, y asi quedó el primer proyecto.

Las sensaciones que me ha dejado el Ucamp hasta ahora han sido satisfactorias, siento que voy aprendiendo bien y el ritmo es fluido
