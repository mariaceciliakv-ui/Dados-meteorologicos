# 📍 Localização por Geolocalização & Google Forms

Aplicação web desenvolvida em arquivo único (**HTML5, CSS3 e JavaScript puro**) com foco em performance, design moderno e integração direta com o **Google Forms**. O sistema captura as coordenadas GPS do dispositivo de forma automática (com opção de preenchimento manual) e envia os dados de forma assíncrona para a sua planilha.

---

## 🚀 Tecnologias Utilizadas

* **HTML5 Semantic**
* **CSS3 Moderno** (Variáveis CSS, Flexbox, Grid, Design Responsivo *Mobile-First*)
* **JavaScript (ES6+)** (Fetch API, Async/Await, Web Geolocation API)
* **Google Forms & Google Sheets** (Backend *serverless* para armazenamento das respostas)

---

## ⚙️ Funcionalidades

1. **Captura de GPS com 1 Clique:** Utiliza a API nativa do navegador (`navigator.geolocation`) para extrair Latitude e Longitude com alta precisão.
2. **Preenchimento Flexível:** Permite que o usuário insira ou edite manualmente o nome do local e as coordenadas.
3. **Submissão Silenciosa (`no-cors`):** Envia os dados direto para o formulário do Google em segundo plano, sem redirecionar o usuário para fora da página de agradecimento padrão.
4. **Feedback Visual:** Estados de carregamento (*spinners*), alertas de sucesso e tratamento de erros de geolocalização integrados na interface.

---

## 📂 Estrutura do Projeto

Como a aplicação foi projetada para ser simples e leve, ela roda perfeitamente a partir de um único arquivo:

```text
📁 seu-repositorio/
├── index.html    # Contém toda a estrutura, estilos e lógica da aplicação
└── README.md     # Documentação do projeto
