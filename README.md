# FitPass Gym Management – Estudo de Caso

Bem-vindo ao repositório oficial do **Estudo de Caso FitPass Gym Management**, utilizado na disciplina de Engenharia de Software.

Este repositório contém o estudo completo que servirá de base para a elaboração:

- Dos **Casos de Uso**
- Da **Documentação Completa dos Casos de Uso**
- Dos **Diagramas de Caso de Uso** (PlantUML ou imagem)

Os alunos deverão seguir cuidadosamente as orientações abaixo.

---

# Visão Geral do Sistema

A FitPass é uma rede de academias que deseja substituir processos manuais por um **sistema moderno de gestão**, contemplando:

- Matrículas  
- Planos  
- Pagamentos  
- Controle de acesso por catraca (RFID)  
- Agendamento de aulas  
- Presença em aulas  
- Avaliações físicas  
- Relatórios gerenciais  

O sistema será utilizado por:

- Alunos  
- Recepcionistas  
- Instrutores  
- Gerentes  
- Sistema de Catraca (API externa)  

Toda a base teórica necessária já está no repositório.

> **Atenção:**  Os arquivos devem ser enviados apenas via **Pull Request** seguindo o padrão descrito abaixo.

# Documentação Fornecida

Os seguintes documentos estão disponíveis na pasta **/docs**:

| Documento | Descrição |
|----------|-----------|
| **rf.md** | Requisitos Funcionais |
| **rnf.md** | Requisitos Não Funcionais |
| **rn.md** | Regras de Negócio |
| **casosdeuso.md** | Template obrigatório para criação do documento final |

Os alunos deverão utilizar exclusivamente essas informações para construir os casos de uso.

# Tarefa dos Alunos

Cada dupla deverá:

### 1. **Fazer um fork deste repositório**

A entrega acontece via **Pull Request** para este repositório original.

### 2. **Produzir um documento contendo 20 Casos de Uso**

- Todos os casos de uso devem estar **no mesmo documento**.
- O documento deve seguir exatamente o template disponível em: /docs/casosdeuso.md

- O documento deve conter **20 casos de uso completos**, com:
  - Nome do caso  
  - Atores  
  - Pré-condições  
  - Pós-condições  
  - Fluxo principal  
  - Fluxos alternativos
  - Requisitos funcionais relacionados
  - Requisitos não funcionais relacionados  
  - Regras de negócio relacionadas  

### 3. **Nomear corretamente o arquivo**

O arquivo deve ser enviado em Markdown e deve seguir o padrão: UC_nomealuno1_nomealuno2.md. Exemplo: UC_MarcosSilva_JulianaPereira.md. 

### 4. **Criar o(s) Diagrama(s) de Caso de Uso**

Os diagramas devem:

- Conter **todos os atores** identificados no documento de casos de uso
- Conter **todos os casos de uso definidos pela dupla**
- Podem ser feitos em PlantUML, Lucidchart, Draw.io, etc.

Os diagramas devem ser exportados em **PNG**.

### Nome do arquivo: 

DUC_XX_nomealuno1_nomealuno2.png onde **XX** é apenas um número sequencial caso existam mais de um diagrama. Exemplos: DUC_01_MarcosSilva_JulianaPereira.png, DUC_02_MarcosSilva_JulianaPereira.png.

### 5. **Enviar tudo via Pull Request**

O PR deve conter:

- O arquivo UC_nomealuno1_nomealuno2.md
- O(s) arquivo(s) do(s) diagrama(s) .png
- As Issues relacionadas:
#1—Documento de Casos de Uso e #2—Diagrama de Casos de Uso

Importante: As Issues devem ser apenas referenciadas no PR, nunca fechadas.
Exemplo de referência correta:
"Relacionado às Issues #1 e #2"
(não usar “closes”, “fixes”, “resolve”, etc.)

