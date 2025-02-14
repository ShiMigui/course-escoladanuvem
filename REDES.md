# Redes

## Documentações
- [Network Essentials](https://aws.amazon.com/pt/getting-started/aws-networking-essentials/)

## Protocolo _TCP_/_IP_
### Transmission Control Protocol / Internet Protocol
Conjunto de protocolos usado para comunicação na internet e redes locais. Ele é dividido em **camadas** que correspondem aproximadamente ao modelo OSI:  

### Principais protocolos do _TCP_/_IP_:
- **_IP_ (Internet Protocol):** Responsável pelo endereçamento e roteamento dos pacotes na rede.  
- **_TCP_ (Transmission Control Protocol):** Garante que os dados sejam entregues corretamente e na ordem certa.  
- **UDP (User Datagram Protocol):** Alternativa ao _TCP_, usado para transmissão mais rápida, mas sem garantia de entrega (ex: streaming, VoIP).  

## Protocolo _DHCP_
### Dynamic Host Configuration Protocol
Protocolo que **atribui automaticamente endereços _IP_** para dispositivos em uma rede.  

### Como funciona?  
1. Um dispositivo (cliente) entra na rede e solicita um _IP_.  
2. O servidor _DHCP_ responde com um _IP_ disponível.  
3. O cliente usa esse _IP_ por um período determinado (leasing).  

### Vantagens do _DHCP_:  
1. Evita a configuração manual de _IPs_.  
2. Reduz conflitos de endereço _IP_ na rede.  
3. Permite gerenciamento mais eficiente em redes grandes.  