# Trabalho - PWA

PWA para Currículo

## Aplicação dos Tópicos Avaliados

- Responsividade:
  - Uso de @media para redimensionar elementos da página.
  - Flex na seçao de skills para alinhar os itens.
- Github + documentação:
  - Link para Github Pages: https://ericmesquibr.github.io/mobile-class-pwa/
  - README.md com informações sobre o trabalho e estrutura do projeto.
- Implementação:

  - No `manifest.json`:
    - `name`: Nome do aplicativo foi definido como Eric Mesquita
    - `short_name`: Nome curto do aplicativo foi definido como EMC
    - `start_url`: URL inicial do aplicativo (index.html)
    - `display`: Modo de exibição do aplicativo está standalone (sem a barra de navegador.)
    - `scope`: Escopo do aplicativo está definido como . (diretório raiz)
    - `description`: Descrição do aplicativo está definida como "This is a PWA of Eric Mesquita that has a short curriculum"
    - `icons`: Ícones do aplicativo estão definidos como um ícone de 512x512 (imagem PNG)
  - No `serviceworker.js` os seguintes arquivos foram adicionados ao cache:

    - `index.html`;
    - `css/main.css`;
    - `img/descending1.jpg`;
    - `img/descending2.jpg`;
    - `img/icon.jpg`.

- Perfil:
  - O conteúdo contém um resumo do perfil, formação acadêmica, experiência profissional e habilidades técnicas.
- Ao menos um diferencial da página puramente estática, pode usar um ou mais destes recursos: pseudo-classes, keyframes, transitions, parallaxes etc.
  - Foram usado Parallaxes entre as seções da página e um keyframe para uma animação no footer.

### Estrutura do Projeto

```
├── 📁css
│   └── 📄main.css
|
├── 📁img
│   └── 🖼️descending1.jpg
│   └── 🖼️descending2.jpg
│   └── 🖼️icon.png
|
├── 📄.editorconfig              <- EditorConfig, para manter a indentação do código.
├── 📄index.html                 <- Arquivo HTML principal.
├── 📄manifest.json              <- The manifest file.
├── 📄README.md
├── 📄serviceworker.js           <- The service worker file.

```
