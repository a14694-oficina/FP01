# Ficha Prática 1: Website da Equipa de Projeto

Este repositório contém o código-fonte para um website estático desenvolvido como parte de uma "Ficha Prática 1". O website tem como objetivo apresentar a **Equipa de Projeto**, os **Projetos** desenvolvidos e os **Contactos** da equipa.

## Estrutura do Projeto

O projeto é composto por um conjunto de ficheiros HTML que representam as diferentes páginas do website, utilizando CSS embutido para o estilo.

| Ficheiro | Descrição | Conteúdo Principal |
| :--- | :--- | :--- |
| `index.html` | Página Inicial | Apresentação da Equipa de Projeto e ligações para os perfis individuais. |
| `projetos.html` | Projetos | Lista de três projetos de desenvolvimento web/plataformas. |
| `contacto.html` | Contactos | Informações de contacto da equipa (morada, email, telemóvel) e um mapa de localização. |
| `ana.html` | Perfil de Ana Costa | Gestora de Projeto. Detalhes sobre experiência, formação e competências. |
| `rui.html` | Perfil de Rui Pereira | Programador Frontend. Detalhes sobre experiência, formação e competências. |
| `sofia.html` | Perfil de Sofia Marques | Designer UI/UX. Detalhes sobre experiência, formação e competências. |
| `images/` (referenciado) | Diretório | Contém as imagens de perfil dos membros da equipa. |

## Funcionalidades Principais

O website oferece as seguintes funcionalidades:

1.  **Apresentação da Equipa:** Uma página inicial (`index.html`) que lista os membros da equipa com as respetivas funções.
2.  **Perfis Detalhados:** Páginas individuais para cada membro (`ana.html`, `rui.html`, `sofia.html`) com informação sobre:
    *   Experiência profissional.
    *   Formação académica.
    *   Competências técnicas (e.g., React, Figma, Scrum).
    *   Contactos individuais.
3.  **Portfólio de Projetos:** Uma secção dedicada (`projetos.html`) que descreve três projetos de desenvolvimento:
    *   Plataforma de Gestão Interna.
    *   Website Responsivo para E-commerce.
    *   Aplicação de Feedback de Clientes.
4.  **Informação de Contacto:** Uma página de contacto (`contacto.html`) com morada, email, telemóvel e um mapa incorporado.
5.  **Design Responsivo:** O código CSS sugere um layout adaptável, utilizando `grid` e `flex` para uma experiência consistente em diferentes dispositivos.

## Como Visualizar

Este é um website estático que pode ser visualizado diretamente no seu navegador.

1.  **Clone o Repositório:**
    ```bash
    git clone [URL do seu repositório]
    cd [nome do repositório]
    ```
2.  **Abrir no Navegador:**
    Abra o ficheiro `index.html` no seu navegador de internet preferido.

    ```bash
    # Exemplo no Linux/macOS
    open index.html 
    # Exemplo no Windows
    start index.html
    ```

## Tecnologias Utilizadas

*   **HTML5:** Estrutura e conteúdo das páginas.
*   **CSS3:** Estilização e layout (incluindo Grid e Flexbox para responsividade).

## Equipa de Desenvolvimento

O projeto foi desenvolvido pela seguinte equipa:

| Nome | Função | Ficheiro de Perfil |
| :--- | :--- | :--- |
| **Ana Costa** | Gestora de Projeto | `ana.html` |
| **Rui Pereira** | Programador Frontend | `rui.html` |
| **Sofia Marques** | Designer UI/UX | `sofia.html` |
