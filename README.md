# Corretor Solution

Painel para o Adobe Premiere Pro (Windows) que lê a planilha de destaques de um curso e:

1. **Junta sequências** marcadas com a mesma cor na planilha (recorta e cola os clipes, com espaço entre as partes);
2. **Marca os GCs**: exporta o áudio de cada aula, transcreve no próprio computador (whisper.cpp) e coloca um marcador onde cada lettering é falado;
3. **Coloca os GCs**: insere o .mogrt na faixa V2, com o texto preenchido, 1 s antes e 1 s depois da fala.

## Instalar

Baixe o `CorretorSolution-<versão>.zip` da última [Release](../../releases/latest), extraia e rode `Instalar.cmd`.
Depois: Premiere > Janela > Extensões > Corretor Solution. Os templates (.mogrt) e a fonte do cliente não ficam neste repositório.

O painel avisa sozinho quando sai uma versão nova (botão **Atualizar**).
