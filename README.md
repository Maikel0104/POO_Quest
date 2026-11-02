<div align="center">

# 🎮 POO Quest

**Aprendendo Orientação a Objetos jogando**

Jogo educativo para o ensino introdutório de Programação Orientada a Objetos<br>
Trabalho de Conclusão de Curso · Bacharelado em Sistemas de Informação · IFRS Campus Vacaria

[![Versão](https://img.shields.io/github/v/release/Maikel0104/POO_Quest?label=vers%C3%A3o&color=53C2F0)](https://github.com/Maikel0104/POO_Quest/releases/latest)
![Plataformas](https://img.shields.io/badge/Windows%20%C2%B7%20macOS%20%C2%B7%20Linux-64%20bits-0078D6)
![Desafios](https://img.shields.io/badge/desafios%20em-Java%20ou%20Python-F2A33A)
![Idioma](https://img.shields.io/badge/idioma-portugu%C3%AAs-4AE3A8)

[⬇️ **Baixar o jogo**](#baixar-e-jogar) ·
[🕹️ **Como jogar**](#como-jogar) ·
[⭐ **Estrelas**](#estrelas) ·
[🎬 **Modo apresentação**](#modo-apresentação)

</div>

---

## Sobre o jogo

O POO Quest é um jogo para quem está começando em Programação Orientada a
Objetos. Em cada fase, o aluno escreve a sua própria classe, em Java ou em
Python, num terminal dentro do jogo, e vê na mesma tela o objeto que ela produz:
o carro ganha a cor que o aluno escolheu, o cofre dispara o alarme quando alguém
tenta mexer no saldo por fora e cada animal do zoológico faz o seu som.

O jogo é completo por si só: não precisa instalar Java, Python nem nenhum outro
programa, e ele funciona sem internet.

### As três fases

| Fase | Conceito | O que acontece na tela |
|:---:|---|---|
| 1 | **Instanciação**: classe e objeto, na oficina do carro | O aluno descreve como é um carro e depois cria um carro de verdade. A cor escolhida vira a pintura, ligar o motor acende os faróis e a velocidade faz as rodas girarem. |
| 2 | **Encapsulamento**: o Cofre do Banco | O dinheiro fica trancado no cofre. Se alguém de fora tenta mexer no saldo direto, o alarme dispara; cada depósito ou saque passa pelo caixa e aparece na fita, aceito ou recusado. |
| 3 | **Herança e polimorfismo**: o Zoológico | O aluno monta a família de animais a partir de uma classe mãe. Uma árvore de classes acende a parte que rodou, e o mesmo pedido faz o cachorro latir, o gato miar e o pássaro piar. |

As fases são liberadas em sequência: concluir uma libera a próxima, e qualquer
fase concluída pode ser jogada de novo.

### O que tem no jogo

- 🧠 **Um conceito por fase**, com explicação, prática e recompensa.
- 🐞 **Erros explicados em português**, apontando a linha e a coluna, com uma
  dica de como corrigir.
- 🔬 **O jogo confere se funciona de verdade**: não basta escrever, é preciso
  que acelerar realmente aumente a velocidade do carro.
- 🐍 **Java ou Python**, à escolha, nas três fases. Cada linguagem tem o seu
  jeito e os seus próprios erros.
- 💡 **Ajuda em camadas**: cada fase começa com um modelo que numera os passos,
  o livro de sintaxe traz só o que a fase pede e as dicas vão do conceito até a
  resposta.
- ⭐ **De uma a três estrelas por fase**, conforme as execuções e as dicas.
- 🎬 **Modo apresentação**, com um aluno simulado que resolve as fases na tela.
- 📦 **Sem instalação**: basta extrair o zip e abrir.

---

## Baixar e jogar

As versões ficam na página de
[Releases](https://github.com/Maikel0104/POO_Quest/releases/latest). Baixe o
zip do seu sistema em **Assets**, extraia e abra.

| Sistema | Arquivo da v1.2.0 | Requisitos |
| --- | --- | --- |
| 🪟 Windows | [POOQuest-v1.2.0-windows.zip](https://github.com/Maikel0104/POO_Quest/releases/download/v1.2.0/POOQuest-v1.2.0-windows.zip) | Windows 10 ou 11, 64 bits |
| 🍎 macOS | [POOQuest-v1.2.0-macos.zip](https://github.com/Maikel0104/POO_Quest/releases/download/v1.2.0/POOQuest-v1.2.0-macos.zip) | macOS 12 ou mais novo, Intel ou Apple Silicon (M1 em diante) |
| 🐧 Linux | [POOQuest-v1.2.0-linux.zip](https://github.com/Maikel0104/POO_Quest/releases/download/v1.2.0/POOQuest-v1.2.0-linux.zip) | Distribuição 64 bits (x86_64) com interface gráfica |

### Windows

1. Clique com o botão direito no zip e escolha **Extrair tudo...**. Não abra o
   jogo de dentro do zip.
2. Na pasta **POO Quest** extraída, abra **POO Quest.exe**.

> [!WARNING]
> Se o Windows mostrar *"O Windows protegeu o computador"*, clique em
> **Mais informações → Executar assim mesmo**. O aviso aparece porque o jogo
> não tem assinatura digital.

### macOS

1. Dê dois cliques no zip para extrair (o Safari costuma extrair sozinho, em
   **Downloads**).
2. Arraste **POO Quest.app**, que está dentro da pasta **POO Quest**, para
   **Aplicativos**.
3. Abra o app. Como ele não é assinado por um desenvolvedor Apple, o macOS
   bloqueia a primeira abertura. Para liberar:
   - **macOS 15 (Sequoia) ou mais novo:** tente abrir, feche o aviso, vá em
     **Ajustes do Sistema ▸ Privacidade e Segurança**, role até o fim e clique
     em **Abrir Mesmo Assim** (pede a senha do Mac).
   - **macOS 14 ou anterior:** clique no app com o botão direito (ou
     Control + clique) ▸ **Abrir** ▸ **Abrir**.

   Isso só é preciso na primeira vez.

> [!WARNING]
> Se aparecer *"POO Quest está danificado e não pode ser aberto"*, o macOS
> marcou o download como de origem desconhecida. Abra o **Terminal**, cole a
> linha abaixo, aperte Enter e abra o jogo de novo:
>
> ```bash
> xattr -cr "/Applications/POO Quest.app"
> ```

### Linux

1. Extraia o zip.
2. Dentro da pasta **POO Quest**, dê dois cliques em **POO Quest.x86_64**.

Se o arquivo abrir como texto ou não fizer nada, marque-o como executável:
botão direito ▸ **Propriedades** ▸ **Permissões** ▸ **Permitir executar como
programa**. Pelo terminal, também dá para extrair e abrir de uma vez:

```bash
unzip POOQuest-v1.2.0-linux.zip
"./POO Quest/POO Quest.x86_64"
```

> [!TIP]
> O jogo precisa de todos os arquivos da pasta **POO Quest**. Se mudar o jogo de
> lugar, leve a pasta inteira.

---

## Como jogar

1. No menu principal, abra **OPÇÕES** e escolha a linguagem do desafio, Java
   ou Python, e as cores do terminal. Tudo é gravado na hora, e o que você
   escreveu em cada linguagem fica guardado separado.
2. Em **JOGAR**, escolha a fase e clique em **COMEÇAR**.
3. Leia a explicação do conceito, avançando com <kbd>E</kbd> ou
   <kbd>Enter</kbd>.
4. Escreva no terminal e clique em **EXECUTAR**. O console mostra o resultado ou
   o erro, em português, e a cena mostra o objeto que você criou. A lista de
   objetivos vai marcando o que já está certo.
5. Travou? **PEDIR DICA** mostra uma dica para o próximo objetivo,
   **LIVRO DE SINTAXE** traz exemplos do que a fase pede, **REVER EXPLICAÇÃO**
   volta ao conceito e **RECOMEÇAR** devolve o modelo inicial.
6. Com todos os objetivos cumpridos, a tela de parabéns mostra as estrelas, os
   seus números e o que você montou, e a próxima fase é liberada.

Dá para executar quantas vezes quiser: não há vidas, tempo limite nem pontos
perdidos. O que você escreveu fica salvo quando sai da fase.

### Estrelas

Cada fase concluída vale de uma a três estrelas:

| Estrela | Como ganhar | Fase 1 | Fases 2 e 3 |
|:---:|---|:---:|:---:|
| 1ª | Concluir a fase | sempre | sempre |
| 2ª | Usar poucas execuções: no máximo uma por objetivo | até 6 | até 7 |
| 3ª | Pedir poucas dicas | até 2 | até 2 |

As estrelas só premiam: quem erra muito ainda conclui a fase, com uma estrela. A
tela de parabéns explica a nota, a seleção de fases mostra a melhor nota de cada
fase e o menu principal soma as três, em "Estrelas: x/9".

### Controles

| Ação | Tecla |
|---|---|
| Avançar a explicação da fase | <kbd>E</kbd> ou <kbd>Enter</kbd> |
| Executar | <kbd>F5</kbd> ou <kbd>Ctrl</kbd> + <kbd>Enter</kbd> |
| Indentar a linha no terminal | <kbd>Tab</kbd> (insere 4 espaços) |
| Voltar / sair da tela | <kbd>Esc</kbd> |
| Ligar e desligar o modo apresentação | <kbd>F9</kbd>, em qualquer tela |

### Progresso

O progresso fica salvo no próprio computador, na conta de quem está usando: as
fases concluídas, as estrelas, o que foi escrito em cada fase e as preferências.
As execuções e as dicas somam todas as vezes em que a fase foi jogada. Para
recomeçar do zero, use o botão com o ícone de inseto 🐞 no menu principal e
confirme em **Zerar tudo**.

---

## Para professores

- **Um aluno por vez no mesmo computador:** zere os dados com o botão de inseto
  🐞 antes de passar o jogo para o próximo aluno, principalmente em laboratórios
  em que todos usam o mesmo login.
- **Feche pelo botão SAIR** do menu, para que o tempo e as dicas da última
  sessão fiquem gravados.
- **Deixe o modo apresentação desligado** quando os alunos forem jogar. Ele não
  fica gravado: ao fechar o jogo, volta desligado.

### Modo apresentação

Para mostrar o jogo numa aula ou numa banca, aperte <kbd>F9</kbd> em qualquer
tela. O selo "MODO APRESENTAÇÃO · F9" aparece no canto superior direito, e as
fases ganham dois botões que ficam escondidos para quem joga:

- **VER RESPOSTA** preenche o terminal com a solução completa da fase, na
  linguagem escolhida (pede confirmação antes). Depois basta clicar em
  **EXECUTAR** para ver o carro montado, o cofre aberto ou o show do zoológico e
  chegar à tela de parabéns.
- **SIMULAR ALUNO** entrega a fase a um aluno simulado. Ele digita tecla por
  tecla, executa, lê a resposta do jogo, pede dica e corrige até concluir,
  enquanto uma faixa no topo narra o que ele pensa e uma seta mostra onde ele
  clica. **VELOCIDADE** acelera; **PARAR** ou <kbd>Esc</kbd> interrompe.

O aluno simulado comete os erros de quem está começando: na Fase 1, esquece a
pontuação do fim da linha e escolhe uma cor que a oficina não aceita; na Fase 2,
deixa o saldo aberto, dispara o alarme e tenta um saque negativo; na Fase 3,
erra o nome de um comportamento, tenta mexer no que é só da classe mãe e faz o
pássaro voar sem andar. Há roteiro para as três fases, em Java e em Python.

A simulação usa o progresso de verdade: ao começar, zera as execuções, as dicas
e o tempo da fase e, no fim, grava a conclusão e as estrelas.

---

## Créditos

**Autor:** Maikel Isaac Tubin Alves<br>
**Orientador:** Prof. Me. Lucas M. Hallmann · **Coorientadora:** Prof.ª Dra. Vanessa Faria Souza<br>
Bacharelado em Sistemas de Informação · Instituto Federal do Rio Grande do Sul, Campus Vacaria · 2026

Fontes: LiberationSans e Cascadia Mono, ambas sob licença SIL OFL.
