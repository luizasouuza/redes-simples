##  TOPOLOGIA DE REDES SIMPLES 
<img width="1599" height="625" alt="Image" src="https://github.com/user-attachments/assets/594c2b1e-a38b-4462-bbed-b34290589a0b" />


## 🔹 1. Rede Local Simples (com DHCP no roteador)

- Configuração de **DHCP direto no roteador** para distribuir IPs.
- PCs recebem IP automaticamente.
- Todos os hosts conseguem se comunicar.

**Imagem da topologia:**
Redes simples: 

<img width="737" height="278" alt="Image" src="https://github.com/user-attachments/assets/4f426d52-671f-4b7e-b681-2738ca90e4a4" />

**Teste (ping):** 

<img width="630" height="326" alt="Image" src="https://github.com/user-attachments/assets/1c82d163-1114-4a0a-9c6d-1f9ced81f938" />

Mostrando IP atribuido: 

<img width="691" height="541" alt="Image" src="https://github.com/user-attachments/assets/fffe35c2-060d-40c4-9de1-a5c4dd8d6940" />---

## 🔹 2. Rede com Switches em Camada 2

- Três switches interligados.
- Todos os PCs recebem IPs fixos.
- Comunicação confirmada via ping.

**Imagem da topologia:**
Rede com switches: 
<img width="720" height="334" alt="Image" src="https://github.com/user-attachments/assets/bd4a58a4-8903-4607-aed5-a8f115932240" />


**Teste de comunicação:**

Ping switches: 

<img width="696" height="463" alt="Image" src="https://github.com/user-attachments/assets/62f36b00-adc4-4b3f-9615-08ad9df755c0" />

---

## 🔹 3. Rede com VLANs (sem roteamento)

- Switch configurado com **VLANs 30, 40 e 50**.
- Cada grupo de PCs pertence a uma VLAN diferente.
- **Não há comunicação entre VLANs.**

**Imagem da topologia:**
Rede VLAN: <img width="800" height="407" alt="Image" src="https://github.com/user-attachments/assets/14c35abc-82c4-4cfe-ba0a-17d350616d76" />

**Teste de comunicação dentro da VLAN:**
Ping VLAN: <img width="696" height="411" alt="Image" src="https://github.com/user-attachments/assets/9f534498-a3ba-4d2d-88d5-ac4f5f84ee81" />

---
📌 Conclusão

Esses projetos são exemplos bem simples, mas ilustram de forma prática conceitos muito utilizados em redes do dia a dia:

- DHCP distribuindo IPs automaticamente através do roteador, algo comum em redes domésticas.

- Switches Layer 2 permitindo a comunicação entre hosts dentro da mesma rede local.

- VLANs isoladas, mostrando como separar grupos de dispositivos sem que exista comunicação entre eles, reforçando a segurança e a organização da rede.

Mesmo sendo redes pequenas, esses cenários ajudam a entender a base que pode ser aplicada em redes corporativas maiores, servindo como primeiro passo para estudar roteamento, inter-VLAN, segurança e serviços adicionais.
