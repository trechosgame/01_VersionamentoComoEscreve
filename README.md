# 01_VersionamentoComoEscreve

Como trocar o campo Pergunta -> PERGUNTA (Text), por imagens ???

PARABÉNIS, RAINHA!!!
Seu quiz já está lindo, profissional, com 4 respostas, contador, tudo funcionando!
Agora vamos trocar o Text "PERGUNTA" por uma IMAGEM (ex: um balãozinho, placa, quadro negro, etc) — fica muito mais fofo e educativo!
PASSO A PASSO SIMPLES E RÁPIDO (30 segundos)

Na Hierarchy → clique no objeto PERGUNTA (aquele que tem o Text)
No Inspector → clique na engrenagem do componente Text → Remove Component
(ou TextMeshPro - Text (UI) se for TMP)
Com o mesmo objeto selecionado → Add Component → digita Image → adiciona
No campo Source Image → arrasta a imagem que você quer (ex: balao_pergunta.png, quadro_negro.png, pergaminho.png)
Ajuste o tamanho:
Width: 800
Height: 200 (ou o que ficar bom)
Pos Y: 300 (pra ficar no topo)

(Opcional) Mantenha o texto da pergunta pergunta atual dentro desse painel:
Crie um novo GameObject filho chamado TextoPergunta
Adicione componente Text ou TextMeshPro
Coloque ele por cima da imagem (na Hierarchy, arraste pra ser filho do painel da pergunta)
Ajuste a posição pra ficar centralizado dentro da imagem
