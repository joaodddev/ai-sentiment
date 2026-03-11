# 📈 Sentiment Analysis: Inteligência Artificial na Mídia
> Monitoramento em tempo real de notícias via Google News e Processamento de Linguagem Natural (NLP).

## 📝 Sobre o Projeto
Este projeto foi desenvolvido para analisar o sentimento das manchetes mais recentes sobre **Inteligência Artificial**. Utilizando técnicas de Web Scraping e NLP, o script identifica se o tom das notícias é predominantemente positivo, negativo ou neutro, oferecendo uma visão clara da percepção pública atual.

## 🛠️ Tecnologias Utilizadas
* **Python 3.x**
* **Pandas:** Manipulação e estruturação dos dados.
* **VADER Sentiment:** Biblioteca de NLP otimizada para redes sociais e textos curtos.
* **Feedparser:** Coleta de dados via RSS (Google News).
* **WordCloud & Matplotlib:** Visualização de dados e tendências.

## 📊 Como Funciona
1.  **Coleta:** O script acessa o RSS do Google News buscando o termo "Inteligência Artificial".
2.  **Processamento:** Limpeza simples e estruturação em um DataFrame.
3.  **Análise:** O algoritmo VADER atribui uma pontuação de "compound" para cada manchete.
4.  **Visualização:** Geração de um gráfico de distribuição de sentimentos e uma nuvem de palavras com os termos mais citados.

## 🚀 Como Executar
Basta abrir o arquivo `.ipynb` no **Google Colab** e rodar as células. Não é necessário configurar chaves de API externas.

## 💡 Insights Obtidos
*(Dica: Após rodar o código, observe o seu gráfico e complete aqui com uma frase real)*
* Exemplo: "Notei que, apesar dos avanços, o termo 'risco' e 'ética' aparecem com frequência em manchetes de tom neutro/negativo."
