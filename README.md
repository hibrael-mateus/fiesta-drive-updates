# Fiesta Drive — Canal de atualizações

Este repositório público contém somente os APKs assinados e os metadados usados pelo atualizador
do Fiesta Drive. O código-fonte e a chave de assinatura não são publicados aqui.

O launcher atual consulta `channel.json`; versões antigas podem consultar `latest.json`.
Ambos apontam para o mesmo APK, baixado por HTTPS e validado por SHA-256, nome do pacote
e número da versão antes de abrir o instalador do Android. A versão `1.10.7-rc7` é
candidata para teste na K2401; ela orienta falhas de rede, mas não pode criar internet
quando a central está desconectada. Projeção Android Auto independente não está incluída.
