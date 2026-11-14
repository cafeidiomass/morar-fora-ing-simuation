# Living Abroad · Café Idiomas

Aplicativo de inglês A1–A2, sem cadastro, servidor de dados ou API paga.

## Usar e compartilhar

Abra `dist/index.html` no navegador. Mantenha os arquivos e a subpasta `assets` da pasta `dist` juntos. Para enviar aos alunos, compacte e envie essa pasta inteira; peça para extrair o ZIP antes de abrir `index.html`. O progresso de conclusão é salvo somente no navegador de cada aluno. Recarregar ou sair durante uma conversa reinicia aquele percurso; conclusões anteriores permanecem salvas.

Para compartilhar por um único endereço sem login, publique o conteúdo da pasta `dist` em qualquer hospedagem de arquivos estáticos de sua escolha. O arquivo `index.html` deve ficar na raiz publicada. Não há etapa de instalação ou compilação. Não envie o PDF do e-book junto com o app.

## Em aula

1. Escolha uma das quatro situações.
2. Ouça a fala e as respostas com os botões ♫.
3. Escolha uma resposta. O feedback orienta novas tentativas; o resultado conta acertos na primeira tentativa.
4. Repita a frase em voz alta antes de continuar.
5. Ative a tradução nas preferências quando precisar e depois repita sem ela.
6. Ao terminar, revise o diálogo e pratique novamente com outras escolhas.

As informações pessoais são fictícias. A compra, os pagamentos, a ocorrência AB-2048, os contatos e os bloqueios existem somente na história. A farmácia ensina perguntas de inglês, sem produto real, dose ou recomendação clínica.

## Áudio

O navegador usa SpeechSynthesis, com idioma en-US e preferência por voz americana. As vozes disponíveis dependem do dispositivo. Nas preferências, escolha a voz e velocidade e use “Testar voz”. Se o áudio falhar, tente outra voz, verifique o volume ou leia em voz alta. Algumas vozes exigem internet; o restante do app não depende de conexão quando os arquivos estão no dispositivo. Não é necessário microfone. Não há gravação nem avaliação de pronúncia.

## Conteúdo

Vizinho: 12 interações. Café: 12. Farmácia: 13. Emergência: 15. Base pedagógica: e-book Living Abroad, seções de comunicação básica, cafeterias, saúde, banco, serviços, vida social e emergências; roteiro de aula de 20 slides/40 minutos da conversa de referência. O app amplia esses temas com diálogos educativos próprios.

## Verificação realizada

Os quatro cenários foram percorridos no navegador até o resultado final: 12/12, 12/12, 13/13 e 15/15. Foram conferidos feedback de erro, tradução, velocidade, repetição de cenário e conclusão acumulada (4 de 4). Café alternativo: preto, grande, gelado, descafeinado, aveia, baunilha, para viagem, em dinheiro: $4.75; recebido $10; troco $5.25. Layout conferido em desktop e viewport de celular (390×844), sem transbordamento horizontal na tela inicial. O áudio apresentou eventos de reprodução e de falha, com mensagem de fallback. A qualidade sonora e as vozes de cada dispositivo precisam ser conferidas nele.

## Arquivos

`dist/index.html`: estrutura. `dist/style.css`: visual responsivo. `dist/content.js`: diálogos e preços. `dist/app.js`: navegação, progresso, feedback e áudio.

## Identidade visual atualizada

Inclui a logo e as cinco ilustrações fornecidas: morar fora, vizinho, café, farmácia e emergência. As imagens estão incluídas no pacote, sem depender de links externos.
