`\w` - caracteres de palabras
`\d` - dígitos
`\s` - espacios/invisibles en blanco
`[0-9]` ~ `\d`
`[0-9a-zA-Z_]` ~ `\w`
`*` _greedy_ cero o muchos - todo 
`+` uno o muchos
`?` cero o uno


## Patrones
mails: `[\w._]{5,30}\+?[\w]{0,10}@[\w\.\-]{3,}\.\w{2,5}`
coordenadas 1: 
`^\-?\d{1,3}\.\d{1,6},\s?\-?\d{1,3}\.\d{1,6},.*$`
coordenadas 2:
`^-?\d{1,3}\s\d{1,2}' \d{1,2}\.\d{2,2}"[WE],\s?-?\d{1,3}\s\d{1,2}' \d{1,2}\.\d{2,2}"[SN]$`

nombre propio
`^[A-Z][a-z]{3,}\s?[A-Z]?[a-z]{0,}`

`^\d+::([\w\s:,\(\)'\.\-&!\/]+)\s\((\d\d\d\d)\)::.*$`
Esto es una prueba
