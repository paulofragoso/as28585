# as28585

Repositório dos documentos e informações sobre as políticas de roteamento do AS28585:

# Trânsitos:

	52965 - Um Telecom
	14840 - Commcorp (BRDitigal)
	16735 - Algar

# Comunidades (communities) para políticas de roteamento:

Por preferência local:

	28585:90  - Modifica o local pref para 90
	28585:100 - Modifica o local pref para 100
	28585:110 - Modifica o local pref para 110
	28585:666 - Blackhole (somente /32 para IPv4 e /64 para IPv6)

Obs.: O local pref padrão é 100

Por prepend (extendida):

	28585:0:XXXX - Impede anúncios para o AS XXXX
	28585:1:XXXX - Adiciona um prepend para o AS XXXX
	28585:2:XXXX - Adiciona dois prepends para o AS XXXX
	28585:3:XXXX - Adiciona três prepends para o AS XXXX
	28585:4:XXXX - Adiciona quatro prepends para o AS XXXX
	28585:5:XXXX - Adiciona cinco prepends para o AS XXXX

# Comunidades informativas:

	28585:20 - Trânsito
	28585:30 - Clientes
	28583:40 - IXs

