# 💰 CoinConverter: Conversor de Moedas Simples e Interativo

Um aplicativo web minimalista para conversão de moedas, demonstrando habilidades de Front-End com HTML, CSS e JavaScript puro, incluindo consumo de API para dados em tempo real.

## 🎯 Problema Resolvido

Usuários precisam de uma ferramenta rápida e fácil para converter valores entre diferentes moedas, com cotações atualizadas, sem a necessidade de cálculos manuais ou de navegar por sites complexos.

## 💡 Solução Desenvolvida

O CoinConverter oferece uma interface limpa onde o usuário pode inserir um valor em reais (BRL) e converter instantaneamente para Dólar Americano (USD), Euro (EUR) ou Libra Esterlina (GBP). A cotação é obtida em tempo real através de uma API externa, garantindo a precisão dos valores.

As principais funcionalidades e conceitos aplicados incluem:
* **Interface Intuitiva:** Design focado na usabilidade para uma experiência de conversão simplificada.
* **Consumo de API Externa:** Requisição HTTP assíncrona para buscar as cotações de moedas atualizadas.
* **Manipulação do DOM Dinâmica:** Atualização dos valores e informações na tela em tempo real com base na interação do usuário e nos dados da API.
* **Event Handling:** Resposta a eventos de usuário (mudança de valor no input, seleção de moedas) para acionar a conversão.
* **Tratamento de Dados:** Formatação dos valores monetários para exibição amigável ao usuário.

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estrutura semântica e acessível para o formulário e exibição de resultados.
* **CSS3:** Estilização responsiva e moderna da interface.
* **JavaScript (ES6+):** Linguagem principal para a lógica de conversão, consumo de API (`fetch` ou `XMLHttpRequest`), manipulação do DOM e tratamento de eventos.
* **API de Cotações de Moedas:** Integração com uma API de terceiros para dados em tempo real.
* **Git & GitHub:** Controle de versão e hospedagem do código.

## 📊 Resultados Alcançados

* ✅ **Conversão em Tempo Real:** Fornece cotações atualizadas, refletindo o valor de mercado.
* ✅ **Experiência Interativa:** Feedback visual instantâneo ao usuário durante a conversão.
* ✅ **Reutilizável e Escalável:** Estrutura de código que permite adicionar facilmente novas moedas ou funcionalidades.


## 💻 Como Rodar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/KevinSilvaRPG/CoinConverter.git](https://github.com/KevinSilvaRPG/CoinConverter.git)
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd CoinConverter
    ```
3.  **Abra o arquivo `index.html`** no seu navegador preferido.

## 💡 Próximas Etapas e Melhorias Futuras

* Adicionar mais opções de moedas para conversão.
* Implementar validação de input para garantir que apenas números sejam inseridos.
* Persistir a última moeda selecionada no armazenamento local do navegador.
* Melhorar a interface para incluir gráficos de tendências ou histórico de cotações.

---
