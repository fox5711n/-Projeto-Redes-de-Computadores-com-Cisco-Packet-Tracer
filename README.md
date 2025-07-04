# Projeto de Redes de Computadores – Packet Tracer

Este repositório apresenta um projeto completo de simulação de redes usando o Cisco Packet Tracer, desenvolvido por alunos da disciplina de Redes de Computadores. O projeto é composto por 10 etapas práticas, cada uma representando uma topologia de rede distinta com diferentes configurações, propósitos e testes de conectividade.

## 📚 Etapas do Projeto

### Etapa 01 – Conexão Cliente-Servidor com Endereços IP Fixos
Rede simples com um cliente e um servidor conectados diretamente. Ambos configurados com IPs fixos. Teste de conectividade via ICMP (ping) realizado com sucesso.

### Etapa 02 – Dois Computadores com IP Fixo, Servidor DHCP e Impressora
Configuração de IPs fixos em dois PCs e comunicação verificada via ping. Impressora incluída na rede e conectividade estabelecida.

### Etapa 03 – Rede com Modem, Dois Switches e Seis Computadores
Rede com acesso à internet via modem, dois switches e seis PCs, com distribuição de IPs via DHCP. Comunicação testada entre dispositivos.

### Etapa 04 – Rede Cascateada com Hub e Switch (Análise de ICMP)
Duas redes com topologias idênticas usando hub e switch, comparando desempenho via testes ICMP. O switch demonstrou melhor performance.

### Etapa 05 – Hub com Access Point e Conexão Wi-Fi
Topologia com cinco computadores conectados a um hub e um access point. Conectividade sem fio validada com sucesso.

### Etapa 06 – Switch e Roteador Wireless com DHCP
Rede com switch e roteador wireless fornecendo IPs por DHCP. Comunicação estável entre PCs e acesso à internet garantido.

### Etapa 07 – Switch com Servidor Centralizado
Topologia com vários PCs conectados a um switch com um servidor centralizado. Comunicação eficiente e centralização de serviços.

### Etapa 08 – Rede com Switch, Roteador, Modem e Acesso à Internet
Rede estruturada com hierarquia: modem, roteador, switch e computadores. Acesso à internet e IPs atribuídos corretamente.

### Etapa 09 – Cascata de Switches com Roteador Central
Topologia com dois switches conectados a um roteador central, totalizando seis computadores. Comunicação intersegmentada validada.

### Etapa 10 – Rede com Switch, Roteador e Impressora de Rede
Todos os dispositivos conectados a um switch, com roteador e impressora de rede acessível por todos os PCs.

---

## 📁 Estrutura de Pastas

Cada pasta corresponde a uma etapa, contendo:

- Arquivo `.pkt` do Packet Tracer
- Prints de tela com o teste de ping e a topologia

```
📦 projeto-redes
├── etapa-01/
│   ├── .pkt
│   ├── ping.png
│   └── topologia.png
├── etapa-02/
│   └── ...
...
└── etapa-10/
```

---

## 🛠️ Tecnologias Utilizadas
- Cisco Packet Tracer
- Protocolo ICMP (ping)
- DHCP, Roteadores, Switches, Modem, Impressora de rede
- Topologias LAN com variações

---

## 👥 Autores
Projeto desenvolvido por alunos da Estácio:

- Cleyton Raposo Ribeiro
- Gabrielle Oliveira Batista
- Gabriel Henrique dos Santos
- João Vitor Santos Diniz
- Maykon Oliveira Santos
- Eduarda Oliveira Bispo
- Samilla Vitória Novais Pereira
- *Victor Junior Alves da Silva Matos*
- Vinicius Monteiro

---

## 📝 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
