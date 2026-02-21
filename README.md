#  Infraestrutura de Redes Corporativa - Empresa ProDesk

Um projeto completo de infraestrutura de conectividade e segurança desenvolvido para suportar a expansão de uma empresa tecnológica com 195 hosts distribuídos em unidades separadas por 600 metros de distância.

##  Engenharia de Infraestrutura
O projeto endereça desafios complexos de interligação e escalabilidade, utilizando uma topologia lógica segmentada para garantir alta performance e isolamento de tráfego.
* **Interligação via Fibra Óptica:** Conexão estável entre as unidades de Produção e Logística através de dutos subterrâneos com transceptores SFP+ para garantir baixa latência.
* **Segurança Lógica (VLANs):** Implementação de redes virtuais (P&D, Qualidade, Compras, Administrativo, Desenvolvimento) com máscaras de sub-rede /26 para mitigar domínios de broadcast.
* **Roteamento Dinâmico OSPF:** Configuração do protocolo *Open Shortest Path First* para garantir convergência rápida e adaptabilidade a falhas na topologia física.

##  Especificações Técnicas
* **Hardware de Borda:** Utilização de roteadores Grandstream (Multi-WAN com VPN) e switches gerenciáveis L3 da TP-Link.
* **Alta Disponibilidade:** Servidores NAS Synology configurados para backup redundante e diretório ativo (AD).
* **Mobilidade:** Implementação de Access Points Wi-Fi 6 para cobertura corporativa de alta densidade.
* **Simulação em Tempo Real:** Validação de toda a topologia lógica e testes de ping/vazão realizados no software **Cisco Packet Tracer**.

##  Orçamento e Planejamento
* **Custo Total Estimado:** R$ 29.825,38, incluindo cabeamento estruturado Cat6/Cat6A e equipamentos ativos.

---
**Autores:** Jefherson Luiz, Maurício Garcia, Marcus Vinicius, Gabriel Grando e Matheus Artismo.
