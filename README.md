# Pseudo Anonimização de dados de IPTU

Repositório para testar e documentar a Pseudoanonimização de dados sensíveis de IPTU

## Metodologia

Os dados de contribuinte e CPF/CNPJ serão concatenados e gerada uma Hash MD5 e então gerado um novo arquivo de IPTU.

É importante observar que os dados disponibilizados até junho de 2021 já não possuiam o CPF e CNPJ completos, estavam obfuscados por caracteres substituidos.

## Resultados

Os resultados por conta do tamanho não estão disponibilizados, no entanto, o método pode ser reproduzido utilizando o NoteBook em Python