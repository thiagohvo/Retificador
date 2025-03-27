# Retificador
## 📖 Introdução  

Este projeto apresenta um **retificador de onda completa** com um regulador de tensão **7805**. O circuito é responsável por converter uma tensão alternada (AC) em contínua (DC) e estabilizá-la em **5V**.  

Na prática, utilizamos um **Arduino** para testes e um **multímetro** para medir as correntes e tensões no circuito.  

---

## 🎯 Objetivo  

- Converter uma tensão AC em DC usando um **retificador de onda completa**.  
- Filtrar a tensão retificada para reduzir ruídos.  
- Regular a saída para **5V DC** utilizando o **7805**.  
- Testar a funcionalidade do circuito com um **Arduino e multímetro**.  

---

## 📜 Esquemático  

### 🔧 **Circuito e Componentes Utilizados**  

Aqui está o esquemático do circuito, projetado no Proteus:  

![Esquemático](fotos/esquematico.png)  

### 📋 **Lista de Componentes**  

| Nome               | Código        | Quantidade | Função |
|--------------------|--------------|------------|--------|
| **Transformador**  | TR1          | 1 | Reduz tensão de 220V para 12V |
| **Ponte de Diodos** | BR1         | 1 | Retifica a tensão AC |
| **Capacitor Eletrolítico** | C1  | 1 | Filtra o ripple da tensão DC |
| **Capacitores Cerâmicos** | C2, C3 | 2 | Reduz ruídos no regulador |
| **Regulador de Tensão** | 7805 | 1 | Estabiliza a saída em 5V |
| **LED Indicador** | D1 | 1 | Indica a presença de tensão |
| **Resistor** | R1 | 1 | 220Ω - Protege o LED |
| **Conector** | CONNSIL2 | 1 | Entrada de alimentação |
| **Conector** | SILL100-02 | 1 | Saída para carga |

### ⚡ **Como Funciona**  

1. **O transformador (TR1)** reduz a tensão da rede elétrica de **220V AC para 12V AC**.  
2. **A ponte de diodos (BR1)** converte a corrente alternada em pulsante contínua.  
3. **O capacitor C1** atua como filtro, reduzindo ondulações na tensão.  
4. **O regulador 7805** mantém a saída estabilizada em **5V DC**.  
5. **Os conectores CONNSIL2 e SILL100-02** facilitam a conexão da carga e alimentação externa.  
6. **O LED** indica que a saída está ativa e funcionando corretamente.  

---

## 🔬 Testes na Prática  

Durante os testes, utilizamos:  
- **Arduino** para validar a saída regulada de **5V**.  
- **Multímetro** para medir as tensões e correntes em diferentes pontos do circuito.  

📷 **Fotos da montagem prática:**  
![Foto da Montagem](fotos/montagem_real.jpg)  

📈 **Resultados Obtidos:**  
- A saída foi regulada corretamente para **5V DC**.  
- As medições com o multímetro confirmaram a eficiência do circuito.  
- O LED acendeu corretamente, indicando a presença de tensão.  

---

## 🖥️ Layout da PCB  

Criamos o layout da PCB no **Proteus** para facilitar a montagem do circuito.  

📷 **Imagem do layout:**  
![PCB](pcb/pcb_layout.png)  

💾 **Arquivos disponíveis em:** [`/pcb/`](pcb/)  

---

## 🏗️ Modelo 3D  

Geramos um **modelo 3D da placa** para visualização da disposição dos componentes.  

📷 **Imagem do modelo 3D:**  
![Modelo 3D](3d/modelo_3d.png)  

💾 **Arquivos disponíveis em:** [`/3d/`](3d/)  

---

## 📌 Melhorias Futuras  

✔️ Usar um **LM317** para ajuste de tensão.  
✔️ Adicionar um **fusível** para proteção contra sobrecarga.  
✔️ Melhorar a filtragem com **capacitores de maior capacidade**.  
✔️ Implementar um **dissipador no 7805** para evitar superaquecimento.  

---

## 🏆 Conclusão  

Este projeto demonstrou como um **retificador de onda completa** pode ser utilizado para alimentar circuitos eletrônicos de forma estável e eficiente. O uso do **Arduino e multímetro** permitiu validar os resultados, garantindo a funcionalidade da saída de **5V DC**.  

📌 **Autor:** Seu Nome  
📅 **Data:** Março de 2025  

---
