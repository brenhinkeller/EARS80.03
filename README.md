# EARS 80.03

Class project assignments and lecture slides for EARS 80.03. 

Projects are written in Julia Markdown and compiled with [Weave.jl](https://github.com/JunoLab/Weave.jl) using a custom template [md2pdfc.tpl](Project%201/md2pdfc.tpl). The monospaced font for the code blocks is [JuliaMono](https://github.com/cormullion/juliamono)

```julia
julia> weave("Project1.jmd", doctype="md2pdf", template="md2pdfc.tpl", keep_unicode=true)
```
