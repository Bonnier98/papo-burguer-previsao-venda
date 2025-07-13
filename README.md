# Previsão de Vendas - Papo Burguer 🍔

Este projeto usa IA (Facebook Prophet) para prever as vendas diárias da hamburgueria **Papo Burguer**, considerando:

✅ Tendência histórica de vendas  
✅ Sazonalidade semanal  
✅ Sazonalidade especial em julho (férias e festas)  
✅ Regressores como fim de semana, promoções e eventos  

## 📁 Dados
Os dados foram extraídos de relatórios mensais em PDF e limpos com `pdfplumber`.

## 🧠 Modelo
Usamos o Prophet com variáveis externas para melhorar a precisão. Os valores negativos foram corrigidos com limiares mínimos.

## 📊 Resultado
A previsão é usada para criar metas de vendas, ajustar escala da equipe e planejar marketing.

## 📦 Requisitos
- pandas
- matplotlib
- prophet
- pdfplumber
