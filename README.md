<p align="center"><img src="imagens/banner.png" alt="FinderX" width="640"></p>

<p align="center"><b>Português</b> · <a href="README.en.md">English</a> · <a href="README.es.md">Español</a></p>

# FinderX

Gerenciador de arquivos para **macOS** que funciona como o **Explorador de Arquivos do Windows 11**: abas, barra de comandos, árvore de pastas e os atalhos do Windows (com ⌘ no lugar do Ctrl). Por cima disso, ele traz coisas que nem o Finder nem o Explorador têm, como **painel duplo**, **fila de cópias** e **conferência da cópia**.

Para quem veio do Windows, usa os dois sistemas ou mexe com muitos arquivos e discos externos.

## Baixar

Pegue a versão mais nova em **[Releases](https://github.com/dmanske/FinderX-public/releases/latest)**:

| Seu computador | Arquivo |
|---|---|
| Mac com chip Apple (M1, M2, M3, M4…) | `FinderX-<versão>-Mac-chip-Apple.zip` |
| Mac com processador Intel ou Hackintosh | `FinderX-<versão>-Hackintosh-Intel.zip` |

Precisa do **macOS 14 (Sonoma) ou mais novo**.

## Instalar

1. Abra o `.zip` e arraste o **FinderX** para **Aplicativos**.
2. Na primeira vez, o macOS avisa que não pode verificar o app (ele não é notarizado pela Apple). Abra **Ajustes do Sistema ▸ Privacidade e Segurança**, role até o aviso do FinderX e clique em **Abrir mesmo assim**.
3. Para atualizar, substitua o app em Aplicativos pela versão nova.

## Diferenciais

### Painel duplo (visão dupla)
Duas pastas na mesma janela, **lado a lado** ou **empilhadas**, como nos gerenciadores de arquivos clássicos. Cada lado tem as suas abas, o seu modo de visualização e, embaixo, **o seu disco** com o espaço livre. Tab troca de lado; copiar ou mover para o outro lado é um comando só. Dá para **comparar** as duas pastas (o que existe só de um lado, o que é mais novo, o que é diferente, até conferindo o conteúdo) e **sincronizar** com uma prévia do que vai acontecer antes de mexer em qualquer arquivo. Com **Navegar junto**, entrar numa subpasta de um lado entra na mesma do outro. **Workspaces** guardam um conjunto de abas e lados para voltar a ele depois.

### Fila de cópias
Mandou copiar várias pastas, de vários lugares, para o mesmo HD externo? Em vez de todas disputarem o disco ao mesmo tempo (e ficarem todas lentas), elas entram **numa fila**: acaba uma, começa a próxima, sozinha. Cópias entre **discos diferentes** continuam rodando ao mesmo tempo. A janela de cópia mostra quem está **NA FILA** e quantas estão na frente, com **Começar agora** e **Tirar da fila**; o Painel de Atividades deixa mudar a ordem; e a barra de baixo avisa "1 copiando · 2 na fila". Vem ligada e pode ser desligada nos Ajustes.

### Cópia que você pode confiar
- **Conflito lado a lado:** quando o nome já existe, os dois arquivos aparecem lado a lado (tamanho e data) para você escolher manter um, outro ou os dois.
- **Conferir a cópia:** depois de copiar, o FinderX lê de novo o original e a cópia e compara o conteúdo (SHA-256). De fábrica ele pergunta nas cópias grandes para outro disco; nos Ajustes dá para deixar sempre ou nunca. Ao **mover** para outro disco com a conferência ligada, o original só é apagado depois de a cópia conferir; se algo saiu diferente (cabo ruim, pendrive com defeito), o original fica onde estava.
- **Gráfico de velocidade** e tempo restante, como no Windows, e **desfazer** (⌘Z) de copiar, mover, renomear e apagar.

### Prateleira
Uma cesta flutuante para **juntar arquivos de várias pastas e discos** enquanto você navega e, no fim, mover, copiar, compartilhar ou compactar tudo de uma vez. Ela só guarda o lembrete de onde cada arquivo está; nada sai do lugar até você mandar.

### Do jeito do Windows
Enter abre, F2 renomeia, ⌫ volta, **recortar e colar** de verdade, Enviar para, Copiar para… e Mover para… com busca de pastas, barra de endereço com migalhas clicáveis (e onde dá para digitar o caminho), Este Computador com a barra de espaço de cada disco, grupos por data iguais aos do Windows. Os atalhos podem ser trocados nos Ajustes.

### Ver e encontrar
- Detalhes, Ícones (de extra grandes a pequenos), Lista, Blocos, Conteúdo e Galeria; a **setinha ▸** abre a pasta dentro da própria lista; as colunas se ajustam à largura da janela, sem sobrar espaço em branco.
- **Seleção por retângulo** em qualquer direção, inclusive de baixo para cima.
- **Pesquisa** com E, OU, NÃO e filtros como `tipo:pdf`; **texto dentro de fotos e PDFs escaneados**, lido no próprio Mac, sem internet.
- **Histórico no botão Voltar:** segure o ‹ para ver por onde você passou.

### Ferramentas
- **O que ocupa espaço:** mostra o que pesa numa pasta ou disco.
- **Achar arquivos duplicados.**
- **Faxina guiada:** arrume uma pasta cheia (como Downloads) um arquivo por vez, só com o teclado.
- **.zip, .7z e .tar abertos como pasta**, sem extrair tudo.
- **Excluir permanentemente** com uma pergunta reforçada, que mostra o nome e o lugar do que vai sumir.
- **Lixeira e Nuvem** dentro do app: restaurar para o lugar de origem, ver o que está só na nuvem, baixar ou liberar espaço.

### Rede
Computadores e compartilhamentos da rede local na árvore, conectar a um servidor e **Compartilhar Tela**.

### Aparência
**Vidro do Mac** ou **Mica do Windows**, claro, escuro ou automático, com ou sem transparência.

### Feito para não travar
Se um disco para de responder (pendrive com defeito, driver travado, rede que caiu), clicar na janela e trocar de lado não congelam mais o FinderX por causa dele.

## Imagens

<p><img src="imagens/lado-a-lado-claro.png" alt="Painel duplo lado a lado, com o disco de cada lado embaixo"></p>
<p><img src="imagens/lado-a-lado-escuro.png" alt="Painel duplo no modo escuro"></p>
<p><img src="imagens/mica.png" alt="Aparência Mica do Windows"></p>
<p><img src="imagens/fila.png" alt="Fila de cópias: a segunda cópia espera o mesmo disco"></p>
<p><img src="imagens/sobre.png" alt="Janela Sobre o FinderX" width="560"></p>

## Problemas e sugestões

Abra um **[Issue](https://github.com/dmanske/FinderX-public/issues)** contando o que aconteceu, a versão do FinderX (menu FinderX ▸ Sobre o FinderX) e a versão do macOS.

## Licença

[MIT](LICENSE) · © 2026 Daniel Manske.

O FinderX não é afiliado à Microsoft nem à Apple. Windows é marca da Microsoft; Finder e macOS são marcas da Apple. Nenhum código ou ícone da Microsoft foi copiado: o comportamento foi reproduzido a partir do uso.
