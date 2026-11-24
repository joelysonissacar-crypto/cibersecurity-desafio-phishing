# Criação de um Phishing com o Kali Linux - Desafio DIO

## Objetivo
Entender na prática como funciona um ataque de phishing, utilizando o Kali Linux e a ferramenta Social-Engineer Toolkit (SET), em um ambiente de laboratório controlado e seguro.

## O que é Phishing?
Phishing é onde o atacante cria uma página ou mensagem parecida com uma verdadeira para enganar a vítima e fazer ela digitar dados, como login e senha.

O atacante usa 3 coisas:
1. Uma página parecida com a original
2. Um link enviado por e-mail, WhatsApp ou rede social
3. A pressa da vítima para ela não perceber o erro

## Ferramentas utilizadas
- Kali Linux
- Social-Engineer Toolkit (SET)
- GitHub

## Como foi feito o laboratório (passo a passo seguro)

1. Abri o terminal no Kali Linux
2. Ajustei o teclado para ABNT2 com o comando:
   3. Abri o SET com:
      4. Escolhi a opção `1) Social-Engineering Attacks`
5. Escolhi a opção `2) Website Attack Vectors`
6. Escolhi a opção `3) Credential Harvester Attack Method`
7. Escolhi a opção `2) Site Cloner`
8. Usei como teste a página pública e sem login:


**Observação importante:** Ao tentar clonar o site `facebook.com`, o próprio SET retornou o erro `Unable to clone this specific site`, pois o Facebook bloqueia esse tipo de clonagem. Isso mostra que serviços grandes possuem proteções contra isso.

## O que aprendi
- Como o atacante monta a estrutura do golpe
- Por que o endereço (URL) da página é o maior sinal de que é falso
- Por que nunca devemos digitar senha em link que chega por mensagem

## Como se proteger de Phishing

1. Sempre olhe o endereço do site. Se for `facebok.com` ou um IP estranho, não é o Facebook.
2. Nunca clique em link de e-mail ou WhatsApp pedindo para trocar senha. Vá direto no app oficial.
3. Ative a verificação em duas etapas.
4. Desconfie de urgência: "Sua conta vai ser bloqueada agora!"
5. Verifique o cadeado e o certificado, mas lembre: cadeado sozinho não garante que é verdadeiro.

## Pasta de imagens
Prints do laboratório estão organizados em `/images`.

## Conclusão
O phishing funciona mais pela engenharia social (enganar a pessoa) do que por hackear o computador. Por isso, a melhor defesa é a atenção e a educação do usuário.
