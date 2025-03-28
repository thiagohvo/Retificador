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
![image](https://github.com/user-attachments/assets/58c9c714-3179-4090-9788-f5db36153648)



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
![image](https://github.com/user-attachments/assets/2f000352-ee65-48fc-9144-a4afb91cdb96)
![image](https://github.com/user-attachments/assets/d70582a4-2bde-4ae2-b1a2-4daed1114e59)
![image](https://github.com/user-attachments/assets/e1d0558d-c711-4674-beac-ccc297e3c330)


  

📈 **Resultados Obtidos:**  
- A saída foi regulada corretamente para **5V DC**.  
- As medições com o multímetro confirmaram a eficiência do circuito.  
- O LED acendeu corretamente, indicando a presença de tensão.  

---

## 🖥️ Layout da PCB  

Criamos o layout da PCB no **Proteus** para facilitar a montagem do circuito.  

📷 **Imagem do layout:**  
![image](https://github.com/user-attachments/assets/7d6862a7-ce27-4c02-bad7-6c7ff2cfb20a)
A Placa de Circuito Impresso (PCB) foi projetada utilizando o software Proteus para acomodar todos os componentes necessários ao funcionamento do retificador de onda completa. A placa foi projetada para ser compacta e eficiente, garantindo que o layout minimize interferências e otimize a dissipação de calor, principalmente devido à corrente que passará pela placa durante a operação do retificador.




---

## 🏗️ Modelo 3D  

Geramos um **modelo 3D da placa** para visualização da disposição dos componentes.  

📷 **Imagem do modelo 3D:**  
## **parte da frente**
**mostra uma renderização 3D de uma placa de circuito eletrônico com vários componentes montados em uma placa de circuito impresso (PCI) verde.
**A placa apresenta:

**Um componente retangular branco central (rotulado como U1)
**Resistores (R1)
**Capacitores (C1, C2, C3)
**Um diodo (D1)
**Outros componentes como pinos de jumper (JP)
**Escala de medição de 50mm no canto inferior direito
**Componentes nas cores amarela e azul
**Uma visão detalhada em perspectiva 3D mostrando a altura e o posicionamento dos componentes
![image](https://github.com/user-attachments/assets/c003e711-72c3-40d4-80da-a9c1a2358435)

## **parte de trás**
**vista do layout da PCI do mesmo circuito, mostrando:

**A base verde da placa de circuito
**Trilhas de cobre conectando diversos pontos
**Furos de montagem para componentes
**O layout dos caminhos de conexão do circuito
![image](https://github.com/user-attachments/assets/f7a6b1f5-bd5c-4b05-9c88-22b4733fee70)




---

## 📌 Melhorias Futuras  

✔️ Usar um **LM317** para ajuste de tensão.  
✔️ Adicionar um **fusível** para proteção contra sobrecarga.  
✔️ Melhorar a filtragem com **capacitores de maior capacidade**.  
✔️ Implementar um **dissipador no 7805** para evitar superaquecimento.  

---

## 🏆 Conclusão  

Este projeto demonstrou como um **retificador de onda completa** pode ser utilizado para alimentar circuitos eletrônicos de forma estável e eficiente. O uso do **Arduino e multímetro** permitiu validar os resultados, garantindo a funcionalidade da saída de **5V DC**.  

📌 **Autor:** Thiago de Oliveira
📅 **Data:** Março de 2025  

---
