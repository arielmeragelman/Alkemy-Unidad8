# Alkemy-Unidad8
Comentarios en Python - PEP8 y Flake8 - Práctico


Ejercicio
Utilizando los conceptos aprendidos en el módulo 8 - 8. Comentarios
en Python - PEP8 y Flake8, resolver el siguiente ejercicio.
● Crear un entorno virtual e instalar Flake 8.
● Utilizar Flake8 para validar el código creado en las prácticas
anteriores.


----------------

Ejemplo de uso:

(base) arielmeragelman@debian:~/Entornos$ python -m venv pep8_env
(base) arielmeragelman@debian:~/Entornos$ source pep8_env/bin/activate
(pep8_env) (base) arielmeragelman@debian:~/Entornos$ python -m pip install flake8
Collecting flake8
  Using cached flake8-5.0.4-py2.py3-none-any.whl (61 kB)
Collecting pycodestyle<2.10.0,>=2.9.0
  Using cached pycodestyle-2.9.1-py2.py3-none-any.whl (41 kB)
Collecting pyflakes<2.6.0,>=2.5.0
  Using cached pyflakes-2.5.0-py2.py3-none-any.whl (66 kB)
Collecting mccabe<0.8.0,>=0.7.0
  Using cached mccabe-0.7.0-py2.py3-none-any.whl (7.3 kB)
Installing collected packages: pyflakes, pycodestyle, mccabe, flake8
Successfully installed flake8-5.0.4 mccabe-0.7.0 pycodestyle-2.9.1 pyflakes-2.5.0
WARNING: You are using pip version 22.0.4; however, version 22.3.1 is available.
You should consider upgrading via the '/home/arielmeragelman/Entornos/pep8_env/bin/python -m pip install --upgrade pip' command.


(pep8_env) (base) arielmeragelman@debian:~/Entornos$ flake8 Unidad2/Alkemy-Unidad2/app.py
Unidad2/Alkemy-Unidad2/app.py:11:80: E501 line too long (82 > 79 characters)
Unidad2/Alkemy-Unidad2/app.py:11:83: W292 no newline at end of file
(pep8_env) (base) arielmeragelman@debian:~/Entornos$ 
