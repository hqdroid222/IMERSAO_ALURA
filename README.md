# IMERSAO_ALURA
Teste da Live ALURA - https://www.youtube.com/watch?v=j_0HRH7gZtA
Código gerado pelo Gemini através do código abaixo:
------------------------------------------------------------------------------------------
import requestsimport random
url = 'https://raw.githubusercontent.com/guilhermeonrails/api-imersao-ia/main/words.json'resposta = requests.get(url)data = resposta.json()print(data)
valor_secreto = random.choice(data)palavra_secreta = valor_secreto['palavra']dica = valor_secreto['dica']
print(f'A palavra secreta tem {len(palavra_secreta)} letras -> {dica}') 
