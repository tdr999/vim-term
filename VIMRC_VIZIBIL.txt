set nocompatible
set termguicolors
colo amber
set number
set cindent
set autoindent
set wildmenu
set cursorline
set cursorcolumn
set ruler
set ts=4 sts=4 sw=4 et
set laststatus=2
set statusline=
set statusline+=%#function#\ %l
set statusline+=\ %*
set statusline+=\ ‹‹
set statusline+=\ %f\ %*
set statusline+=\ ››
set statusline+=\ %m
set statusline+=%#keyword#\ %F
set statusline+=%=
"set statusline+=\ %{LinterStatus()}"
set statusline+=\ ‹‹
set statusline+=\ %{strftime('%R',getftime(expand('%')))}
set statusline+=\ ::
set statusline+=\ %n
set statusline+=\ ››\ %*
"https://kadekillary.work/post/statusline-vim/"

set omnifunc=syntaxcomplete#Complete
set complete+=kspell
set completeopt=menuone,longest
