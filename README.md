Mapa de caracteres especiais

Ã¡ = a agudo
Ã  = a grave
Ã¢ = a circunflexo
Ã£ = a til
Âª = a numero
Ã = A agudo
Ã = A grave
Ã = A circunflexo
Ã = A til

Ã© = e agudo
Ã¨ = e grave
Ãª = e circunflexo
& = e comercial
Ã = E agudo
Ã = E grave
Ã = E circunflexo

Ã­ = i agudo
Ã¬ = i grave
Ã® = i circunflexo
Ã¯ = i trema
Ã = I agudo
Ã = I grave
Ã = I circunflexo
Ã = I trema

Ã³ = o agudo
Ã² = o grave
Ã´ = o circunflexo
Ãµ = o til
Âº = o numero
Ã = O agudo
Ã = O grave
Ã = O circunflexo
Ã = O til

Ãº = u agudo
Ã¹ = u grave
Ã» = u circunflexo
Ã = U agudo
Ã = U grave
Ã = U circunflexo

Ã§ = c cedilha
Ã± = n til

========================================================================================

Replace de caracteres especiais gerados pela conversão do banco de latin1 - lantin1-general-ci para uft8 - uft8-general-ci

'á', 'à', 'â', 'ã', 'ª', 'é', 'è', 'ê', 'í', 'ì', 'î', 'ï', 'ó', 'ò', 'ô', 'õ', 'º', 'ú', 'ù', 'û', 'ç', 'ñ'

REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(CAMPO, 'Ã¡', 'á'), 'Ã ', 'à'), 'Ã¢', 'â'), 'Ã£', 'ã'), 'Âª', 'ª'), 'Ã©', 'é'), 'Ã¨', 'è'), 'Ãª', 'ê'), 'Ã­', 'í'), 'Ã¬', 'ì'), 'Ã®', 'î'), 'Ã¯', 'ï'), 'Ã³', 'ó'), 'Ã²', 'ò'), 'Ã´', 'ô'), 'Ãµ', 'õ'), 'Âº', 'º'), 'Ãº', 'ú'), 'Ã¹', 'ù'), 'Ã»', 'û'), 'Ã§', 'ç'), 'Ã±', 'ñ')

'Á', 'À', 'Â', 'Ã', 'É', 'È', 'Ê', 'Í', 'Ì', 'Î', 'Ï', 'Ó', 'Ò', 'Ô', 'Õ', 'Ú', 'Ù',

REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(CAMPO, 'Ã', 'Á'), 'Ã', 'À'), 'Ã', 'Â'), 'Ã', 'Ã'), 'Ã', 'É'), 'Ã', 'È'), 'Ã', 'Ê'), 'Ã', 'Í'), 'Ã', 'Ì'), 'Ã', 'Î'), 'Ã', 'Ï'), 'Ã', 'Ó'), 'Ã', 'Ò'), 'Ã', 'Ô'), 'Ã', 'Õ'), 'Ã', 'Ú'), 'Ã', 'Ù'), 'Ã', 'û')

========================================================================================

Exemplo da aplicação

UPDATE `my_table`
SET
	`my_field` = REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(REPLACE(`my_field`, 'Ã¡', 'á'), 'Ã ', 'à'), 'Ã¢', 'â'), 'Ã£', 'ã'), 'Âª', 'ª'), 'Ã©', 'é'), 'Ã¨', 'è'), 'Ãª', 'ê'), 'Ã­', 'í'), 'Ã¬', 'ì'), 'Ã®', 'î'), 'Ã¯', 'ï'), 'Ã³', 'ó'), 'Ã²', 'ò'), 'Ã´', 'ô'), 'Ãµ', 'õ'), 'Âº', 'º'), 'Ãº', 'ú'), 'Ã¹', 'ù'), 'Ã»', 'û'), 'Ã§', 'ç'), 'Ã±', 'ñ')
;