# lab-6
Como Funciona a Análise de Sentimentos?
O serviço analisa o texto e retorna:

Classificação geral:

Positivo 😊

Negativo 😠

Neutro 😐

Misto (quando há sentimentos contraditórios).

Mineração de opiniões (opcional):

Detecta termos específicos e avalia seu sentimento.

Exemplo:

"O celular é ótimo, mas a bateria é ruim."

→ "celular" (positivo) | "bateria" (negativo).

📌 Passo a Passo no Language Studio
1️⃣ Acesse o Language Studio
Entre em: https://language.cognitive.azure.com

Faça login com sua conta Azure.

2️⃣ Crie ou Selecione um Projeto
Vá para "Análise de Texto" > "Análise de Sentimentos".

Selecione um recurso existente ou crie um novo.

3️⃣ Teste com Textos
Na seção "Demo", digite ou cole um texto para análise.

Exemplo:
"Adorei o atendimento, mas o produto chegou atrasado."

4️⃣ Resultados
O sistema retornará:

Sentimento geral: Misto

Opiniões específicas:

"atendimento" → Positivo (confiança: 95%)

"produto chegou atrasado" → Negativo (confiança: 85%)
