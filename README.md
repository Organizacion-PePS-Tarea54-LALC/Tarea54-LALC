# Tarea54-LALC
gh auth login
$ mkdir GitHub_cli_PePS
$ cd \GitHub_cli_PePS
$ echo "# Tarea54-LALC" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin https://github.com/Organizacion-PePS-Tarea54-LALC/Tarea54-LALC.git
$ git push -u origin main
$ gh org list
$ gh browse
$ git branch develop
$ git checkout develop
$ gh issue list
$ gh issue create --title "Implementar la interfaz Figura.java" --body "Creamos la interfaz Figura.java que contiene los métodos *calcularArea()* y *calcularPerimetro()* que serán implementados por el resto de clases correspondientes a figuras geométricas"
$ gh issue create --title "Implementar clase Cuadrado.java" --body "Creamos la clase Cuadrado.java que implementa la interfaz Figura.java"
$ gh issue create --title "Implementar clase Triangulo.java" --body "Creamos la clase Triangulo.java (triangulo rectángulo) que implementa la interfaz Figura.java"
$ gh issue create --title "Implementar clase Circunferencia.java" --body "Creamos la clase Circunferencia.java que implementa la interfaz Figura.java"
$ gh issue list