----------------------------------------------------------------------
                  Guia De Instalación De Nvim
----------------------------------------------------------------------

1)- abrir terminal y poner este comando. 

mkdir -p ~/.local/share/fonts
_____________________________________________________________________

2)- abrir terminal y poner este comando.


cd ~/.local/share/fonts && curl -fLo "Droid Sans Mono for Powerline Nerd Font Complete.otf" https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/DroidSansMono/complete/Droid%20Sans%20Mono%20Nerd%20Font%20Complete.otf

_____________________________________________________________________

3)- copiar la carpeta nvim entera a tu .config 
 
ir a .config/nvim y abrir init.vim con nvim para cargar los plugins (Tenes que tener internet sino no cargará nada y dará error)

---------------------------------------------------------------------
							Atajos Nvim
---------------------------------------------------------------------
:y = copiar
:p = pegar
:x = cortar
:w = guardar
:u = cambios atrás
Shift + i = ver ocultos
:q = salir
:wq! = guardar con privilegios sudo
