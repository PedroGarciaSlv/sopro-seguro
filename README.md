# SoproSeguro

> Sistema de segurança veicular que utiliza um sensor de álcool e Arduino para identificar a presença de álcool no hálito do motorista e bloquear a movimentação do veículo quando necessário.

---

## 📌 Informações Gerais

- **Nome do Projeto:** SoproSeguro
- **Equipe:** Amanda Gabrielle; Arthur Graciano; Emanuel Chaves; João Francisco; Luiz Felipe; Maria Eduarda; Pedro Garcia.
- **Curso:** Técnico em Informática
- **Instituição:** FUNEC – Unidade Riacho
- **Ano/Semestre:** 2026
- **Professor Orientador:** Ronaldo dos Santos Brito
- **Cliente/Setor Solicitante:** Motoristas, proprietários de veículos e empresas que trabalham com frotas de veículos.

---

## 🎯 Objetivo do Projeto

Desenvolver um protótipo de sistema de segurança veicular utilizando Arduino e um sensor de álcool, capaz de identificar a presença de álcool no hálito do motorista e impedir a movimentação do veículo quando a leitura ultrapassar o limite definido. O projeto busca contribuir para a prevenção de acidentes e promover um trânsito mais seguro.

---

## 👥 Público-Alvo

- Motoristas.
- Proprietários de veículos.
- Empresas que trabalham com frotas de veículos.
- Gestores responsáveis pela segurança de motoristas.
- Pessoas interessadas em tecnologias de segurança no trânsito.

---

## 🧩 Problema a Ser Resolvido

A condução de veículos após o consumo de bebidas alcoólicas representa um risco para o motorista, passageiros e demais pessoas no trânsito. Muitas vezes, não existem mecanismos que impeçam o motorista de iniciar a condução nessas condições, aumentando a possibilidade de acidentes, prejuízos materiais e consequências legais.

---

## 💡 Solução Proposta

Desenvolver um sistema integrado ao veículo que utiliza o sensor MQ-3 para identificar a presença de álcool no ar expelido pelo motorista.

O Arduino recebe as informações do sensor e verifica se a leitura ultrapassa o limite estabelecido. Caso isso aconteça, o sistema bloqueia a movimentação dos motores e emite alertas visuais e sonoros.

Para demonstrar o funcionamento, será desenvolvido um protótipo com Arduino, dois motores DC e um carrinho em miniatura, utilizando o driver DRV8833 para controlar sua movimentação.

---

## ⚙️ Funcionalidades do Sistema

### Funcionalidades Principais

- [x] Realizar a leitura do sensor de álcool MQ-3.
- [x] Identificar valores acima do limite configurado.
- [x] Controlar a liberação e o bloqueio dos motores.
- [x] Emitir alertas visuais por meio de LEDs.
- [x] Emitir alertas sonoros por meio de buzzer.
- [ ] Integrar o Arduino ao driver DRV8833.
- [ ] Controlar os dois motores DC do carrinho.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** C/C++ (programação Arduino).
- **Plataforma de desenvolvimento:** Arduino IDE.
- **Hardware:** Arduino Uno, sensor MQ-3, driver DRV8833, dois motores DC de 3–6 V, LEDs e buzzer.
- **Estrutura física:** Carrinho de papelão com rodas de 68 mm.
- **Ferramentas:** Arduino IDE e Cirkit Designer.
- **Versionamento:** Git e GitHub.

---

## 🗂️ Estrutura do Projeto

```text
/SoproSeguro
│
├── codigo
│   └── SoproSeguro.ino
│
├── circuito
│   └── esquema-eletrico
│
├── docs
│   ├── documentacao
│   └── imagens
│
├── prototipo
│   └── estrutura-fisica
│
└── README.md
```

---

## 🧪 Requisitos Funcionais

- **RF01** – O sistema deve realizar a leitura da concentração de álcool por meio do sensor MQ-3.
- **RF02** – O sistema deve analisar os valores recebidos pelo sensor.
- **RF03** – O sistema deve bloquear a movimentação do carrinho quando a leitura ultrapassar o limite estabelecido.
- **RF04** – O sistema deve liberar a movimentação quando a leitura estiver dentro do limite definido.
- **RF05** – O sistema deve emitir alertas visuais para informar a situação identificada.
- **RF06** – O sistema deve emitir alertas sonoros quando o bloqueio for acionado.
- **RF07** – O sistema deve controlar os dois motores DC por meio do driver DRV8833.
- **RF08** – O sistema deve integrar a leitura do sensor ao mecanismo de bloqueio dos motores.

---

## 🚫 Requisitos Não Funcionais

- O sistema deve apresentar funcionamento confiável.
- O circuito deve utilizar componentes compatíveis entre si.
- O protótipo deve possuir uma estrutura física resistente.
- A interface de sinalização deve ser simples e de fácil compreensão.
- O sistema deve apresentar respostas adequadas às leituras do sensor.
- A montagem deve permitir a manutenção e a substituição dos componentes.
- O protótipo deve funcionar com alimentação elétrica adequada aos componentes utilizados.

---

## 📅 Cronograma do Projeto

| Etapa | Descrição | Responsável | Data |
|------|-----------|-------------|------|
| 1 | Levantamento de requisitos e pesquisas | Equipe | 31/03/2026 |
| 2 | Planejamento e modelagem do projeto | Equipe | 01/06/2026 |
| 3 | Desenvolvimento do código e circuito | Pedro Garcia | 21/11/2026 |
| 4 | Montagem da estrutura e carrinhos | Amanda Gabrielle e Emanuel Chaves | 21/11/2026 |
| 5 | Integração dos componentes | Pedro Garcia e Amanda Gabrielle | 21/11/2026 |
| 6 | Testes e ajustes do protótipo | Equipe | 21/11/2026 |
| 7 | Desenvolvimento da documentação | Luiz Felipe | 15/11/2026 |
| 8 | Preparação da apresentação | Arthur Graciano e Maria Eduarda | 20/11/2026 |
| 9 | Entrega e apresentação final | Equipe | 23/11/2026 |

---

## 🧑‍💻 Integrantes da Equipe

| Nome | Função | Responsabilidade |
|------|-------|-----------------|
| Amanda Gabrielle | Líder | Organização da demonstração dos carrinhos. |
| Arthur Graciano | Comunicação | Desenvolvimento do roteiro para os visitantes. |
| Emanuel Chaves | Montagem e comunicação visual | Montagem dos carrinhos e desenvolvimento do banner. |
| João Francisco | Design e apresentação | Desenvolvimento dos slides finais. |
| Luiz Felipe | Documentação | Elaboração do relatório final. |
| Maria Eduarda | Apresentação | Desenvolvimento do roteiro para a banca. |
| Pedro Garcia | Desenvolvedor | Montagem do circuito, programação e lógica do protótipo. |

---

## 🔐 Controle de Acesso

Não se aplica ao protótipo, pois o projeto não possui sistema de login ou cadastro de usuários.

O controle realizado pelo SoproSeguro está relacionado à autorização ou ao bloqueio da movimentação do carrinho, de acordo com a leitura do sensor de álcool.

---

## 📷 Protótipos / Telas

Inserir imagens e registros do desenvolvimento do projeto:

- Imagens da montagem do circuito Arduino.
- Imagens do sensor MQ-3.
- Fotografias do carrinho em miniatura.
- Esquema elétrico desenvolvido no Cirkit Designer.
- Registros dos testes realizados.
- Vídeo demonstrativo do funcionamento do SoproSeguro.

---

## 📦 Como Executar o Projeto

1. Conectar a alimentação do circuito e ligar o sistema.
2. Aguardar a inicialização do Arduino e do sensor MQ-3.
3. Realizar o teste de leitura do ar expelido próximo ao sensor.
4. Aguardar a análise realizada pelo Arduino.
5. Caso a leitura esteja dentro do limite estabelecido, o sistema libera a movimentação do carrinho.
6. Caso a leitura ultrapasse o limite, o sistema bloqueia os motores e aciona os alertas visuais e sonoros.
7. Após uma nova leitura permitir a liberação, o carrinho poderá voltar a se movimentar.

**Observação:** O SoproSeguro é um protótipo educacional e demonstrativo. O sensor MQ-3 não substitui um etilômetro certificado e o projeto não deve ser utilizado como dispositivo de segurança veicular real.
