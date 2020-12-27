# bash-insulter

Mi versión de bash-insulter, con un toque personal de sátira
y malas palabras.

El trabajo original es de https://github.com/hkbakke/bash-insulter 
todo el crédito (sin las consecuencias feas que puedan salir) son para
el.

## DISCLAIMER

:warning: Este fork contiene lenguaje un poco fuerte, pero
eso ya deberías saberlo. Aun así, pongo este warning por si
eres un mazapan que se pueda ofender a sabiendas de lo que
va a instalar.

Por favor ten en cuenta que este programa está hecho con
el objetivo de entretener y no dirigido a una persona en
específico por lo tanto, si te sientes identificado u 
ofendido con los resultados del programa es tu pedo
xdXDXdxDxD pa que no andes instalando cosas que luego
no te van a gustar.

# Compatibilidad
* Bash v4 o superior.
* Zsh

# Instalación

    # Método 1 - Para pros
    
    git clone https://github.com/VentGrey/bash-insulter-ventgrey.git
    sudo cp bash-insulter/src/bash.command-not-found /etc/

    # Método 2 - Solo insúltame porfi
    sudo wget -O /etc/bash.command-not-found https://raw.githubusercontent.com/VentGrey/bash-insulter-ventgrey/master/src/bash.command-not-found

Luego de eso ejecuta `source` en el archivo o añade el siguiente comando al archivo de `/etc/bash.bashrc`o cualquier otra localización que utilicen las shells con las que inicias sesión, puedes también añadirlo al `~/.bashrc` si no deseas que mi versión ande mentando madres a múltiples usuarios:
```sh
if [ -f /etc/bash.command-not-found ]; then
    . /etc/bash.command-not-found
fi
```
Cierra sesión o reinicia tu shell para ver los hermosos efectos.

Nota: Si usas `zsh` deberás añadirlo al archivo `.zshrc`.
