FiapCap1Fase3

Neste projeto, se desenvolveu um sistema de irrigação inteligente simulando sensores agrícolas em uma plataforma digital. 
Utilizamos o simulador Wokwi com o microcontrolador ESP32 para monitorar dados de umidade,
nutrientes (representados por dois botões para Fósforo e Potássio), e pH (simulado pelo sensor de luz LDR).
A umidade foi medida com um sensor DHT22. Esses dados determinam a ativação de uma bomba d'água, representada por um relé, controlando a irrigação conforme as condições do solo.
Além disso, implementamos um banco de dados Oracle com integração via Python para realizar operações CRUD (criação, leitura, atualização e exclusão) dos dados dos sensores. 
Assim, o sistema armazena e gerencia o histórico de dados dos sensores, criando uma base para futuras análises e otimização da irrigação.
