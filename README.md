# Protótipo de Envio de Dados 🚀

Este projeto consiste em uma interface web moderna e limpa para preenchimento de formulário, desenvolvida com **HTML5** estrutural e estilizada com **CSS3**. O layout adota um design focado na experiência do usuário, dividindo a tela simetricamente em duas seções principais (duas colunas) para coletar dados cadastrais e permitir a inserção de textos personalizados.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do conteúdo.
* **CSS3:** Estilização avançada, utilizando variáveis (`:root`), Flexbox para alinhamento e gradientes radiais no plano de fundo para maior profundidade visual.

---

## 📄 Estrutura do Projeto

O layout é dividido de forma justa entre dois blocos visuais (`lado1` e `lado2`) dentro de um contêiner flexível principal:

### 1. Coluna Esquerda (`lado1`) - Formulário de Cadastro
Uma seção clara focada na captura e validação de informações básicas do usuário na camada do cliente:
* **E-mail:** Validação nativa de formato de endereço eletrônico (`type="email"`).
* **Senha:** Ocultação de caracteres com restrição de tamanho (mínimo de 6 e máximo de 12 caracteres).
* **Nome Completo:** Campo de texto padrão para identificação.
* **Data de Nascimento:** Seletor de calendário nativo do navegador (`type="date"`).
* *Todos os campos possuem o atributo `required`, impedindo envios em branco.*

### 2. Coluna Direita (`lado2`) - Área de Texto Personalizada
Uma seção contrastante (utilizando um tom de roxo/índigo vibrante) que propõe uma interação livre:
* **Área de Texto (`<textarea>`):** Espaço expandido para que o usuário escreva sobre si mesmo.
* **Botão Dedicado:** Processamento independente para o envio do texto inserido.

---

## ⚙️ Ajustes Futuros e Melhorias Técnicas

Para evoluir este protótipo para um ambiente de produção, estão previstas as seguintes melhorias:
1.  **Validação do Lado 2:** Envolver os elementos da segunda coluna em uma tag `<form>` para habilitar o comportamento nativo de envio e validação do atributo `required`.
2.  **Acessibilidade (a11y):** Inclusão de tags `<label>` associadas a cada campo de entrada para suporte a leitores de tela.
3.  **Refatoração de Código:** Correção de pequenos detalhes de fechamento de chaves e declarações duplicadas no CSS/HTML.
4.  **Responsividade Avançada:** Ajustar as porcentagens de largura das colunas para melhor adaptação em dispositivos móveis.