# Smart Campus: Algoritmo de Gerenciamento de Carga Elétrica no Horário de Pico com Desligamento Paralelo

Um sistema inteligente voltado para a otimização do consumo de energia em instituições de ensino, com foco especial no controle automatizado e estratégico do módulo de **desligamento de aparelhos de ar-condicionado** durante os horários de pico.

---

## 📋 Sobre o Projeto

O **Smart Campus** é uma iniciativa que une eficiência energética, automação e sustentabilidade. Em horários de pico (quando a tarifa de energia é mais cara e a rede elétrica fica sobrecarregada), o sistema atua de forma coordenada para mitigar picos de demanda. 

Este repositório/módulo específico implementa a lógica de **desligamento paralelo** dos sistemas de climatização, garantindo que a redução de carga ocorra de maneira gradual, segura e sem comprometer drasticamente o conforto térmico dos ambientes antes que a inércia térmica comece a dissipar o calor acumulado.

---

## ⚙️ Principais Funcionalidades

- **Controle em Horário de Pico:** Identificação automática dos horários críticos de consumo energético no campus.
- **Estratégia de Desligamento Paralelo:** Em vez de cortes bruscos ou totais que sobrecarregam a rede em instantes específicos, o algoritmo gerencia o desligamento em blocos/frotas de equipamentos de forma distribuída.
- **Monitoramento de Carga:** Acompanhamento em tempo real da redução de potência ativa ($P$) em quilowatts (kW).
- **Mitigação de Impacto Térmico:** Preservação programada do conforto dos usuários através de ciclos otimizados.

---

## 🚀 Tecnologias Utilizadas

*(Personalize esta seção conforme as tecnologias reais do seu projeto)*
- **Linguagem:** Python / Node.js / C++ (ajustar conforme aplicável)
- **Simulação/Modelagem:** Lógica de Algoritmos de Otimização e Automação
- **Protocolos de Comunicação (IoT):** MQTT / HTTP (se aplicável para comunicação com os aparelhos)

---

## 📐 Modelagem do Módulo de Ar-Condicionado

O modelo matemático e lógico por trás deste módulo considera variáveis como:
1. **Potência Nominal ($P_n$):** Consumo médio de cada unidade evaporadora/condensadora.
2. **Janela de Pico ($t_{inicio}$ a $t_{fim}$):** Intervalo temporal de maior tarifa e sobrecarga.
3. **Fator de Carga Distribuída ($N_{paralelo}$):** Número de unidades desligadas simultaneamente por ciclo para evitar transientes na rede elétrica.

---

## 🛠️ Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/smart-campus-ar-condicionado.git
   ```
2. Instale as dependências (exemplo):
   ```bash
   cd smart-campus-ar-condicionado
   pip install -r requirements.txt
   ```
3. Execute a simulação ou o script principal:
   ```bash
   python main.py
   ```

---

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma *issue* para relatar bugs ou sugerir melhorias na lógica do algoritmo de corte paralelo.

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/NovaLogica`)
3. Faça o Commit das suas alterações (`git commit -m 'Adiciona nova regra de prioridade'`)
4. Faça o Push para a Branch (`git push origin feature/NovaLogica`)
5. Abra um Pull Request

---


---
[Clicke aqui para ver a adr-0001] (architeture/adr-0001.md)
[Clicke aqui para ver o diagrama de containers] (architeture/workspace.mmd)
[Clicke aqui para ver o diagrama de atividades] (atividades.mmd)
[Clicke aqui para ver o diagrama de estados] (estados.mmd)
[Clicke aqui para ver o diagrama de sequencia] (sequencia.mmd)

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).
