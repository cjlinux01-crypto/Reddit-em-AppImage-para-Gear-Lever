# Reddit em AppImage para Gear Lever

Este repositório disponibiliza a aplicação do Reddit empacotada no formato AppImage, pronta para ser gerida e integrada no seu sistema Linux através do Gear Lever (https://github.com/miamipm/gear-lever).

---

## O que é o Gear Lever?
O Gear Lever é uma ferramenta para Linux que ajuda a gerir ficheiros AppImage, organizando-os na sua lista de aplicações, adicionando ícones e permitindo atualizações de forma simples.

---

## Como descarregar o Reddit AppImage

1. Vá até a secção de Releases (Lançamentos) no menu lateral direito deste repositório.
2. Localize a versão mais recente e descarregue o ficheiro .AppImage do Reddit.

---

## Como usar com o Gear Lever

1. Abra o Gear Lever na sua distribuição Linux.
2. Arraste e solte o ficheiro Reddit.AppImage descarregado para dentro da janela do Gear Lever (ou utilize o botão Adicionar/Importar).
3. O Gear Lever tratará automaticamente de:
   - Dar permissões de execução ao ficheiro.
   - Mover o Reddit AppImage para a pasta organizada.
   - Criar o atalho do Reddit com ícone no menu de aplicações do seu sistema.

---

## Informações Importantes
- Compatibilidade: Testado em distribuições Linux com suporte a AppImage.
- Permissão de execução manual (opcional): Caso pretenda executar sem utilizar o Gear Lever, abra o terminal e execute:
  ```bash
  chmod +x Reddit-1.0.0.AppImage
  ./Reddit-1.0.0.AppImage
