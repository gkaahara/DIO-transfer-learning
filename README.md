# **Transfer Learning para Classificação de Gatos vs. Cachorros**  

🔍 **Descrição**  
Este projeto aplica **Transfer Learning** usando a arquitetura **MobileNetV2** (pré-treinada na ImageNet) para classificar imagens de gatos e cachorros com alta acurácia (~98%). Desenvolvido no Google Colab, o código é ideal para quem quer aprender técnicas avançadas de Deep Learning com TensorFlow/Keras.  

---

## **Tecnologias Utilizadas**  
- **Linguagem**: Python  
- **Bibliotecas**: TensorFlow, Keras, TensorFlow Datasets, Matplotlib  
- **Modelo Base**: MobileNetV2 (pré-treinada)  
- **Dataset**: [Cats vs. Dogs](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs) (TensorFlow Datasets)  

---

## **Funcionalidades**  
✔️ **Pré-processamento**: Redimensionamento, normalização e data augmentation.  
✔️ **Transfer Learning**: Reutilização da MobileNetV2 com camadas personalizadas.  
✔️ **Treinamento**: Ajuste fino (fine-tuning) e monitoramento de métricas.  
✔️ **Avaliação**: Acurácia de ~98% em validação e teste.  

---

## **Como Usar**  
1. **No Google Colab**:  
   - Abra o notebook [DIO_Transfer_Learning.ipynb](https://github.com/gkaahara/DIO-transfer-learning/blob/main/DIO_Transfer_Learning.ipynb).  
   - Execute as células sequencialmente (certifique-se de ativar a GPU em *Runtime → Change runtime type*).  

2. **Com Seu Próprio Dataset**:  
   - Substitua o dataset por imagens suas (ex.: `./data/train/gatos/` e `./data/train/cachorros/`).  
   - Ajuste o número de classes na camada de saída (ex.: `Dense(2, activation='softmax')` para 2 classes).  

---

## **Resultados**  
📊 **Métricas Finais**:  
- Acurácia no treino: **99.28%**  
- Acurácia na validação: **98.37%**  
- Loss na validação: **0.047**  

📌 **Matriz de Confusão**:  
![download](https://github.com/user-attachments/assets/acddb334-7d59-4675-9d03-cc3d26dc91ad)


---

## **Próximos Passos**  
🚀 **Deploy**:  
- Converta o modelo para TensorFlow Lite e integre a um app mobile.  
- Crie uma API com Flask/FastAPI para classificação em tempo real.  

🔧 **Melhorias**:  
- Experimente outros modelos (ex.: EfficientNet, ResNet).  
- Adicione mais classes (ex.: raças de animais).  

---

## **Contato**  
👨‍💻 **Autor**: [Gabriel Kaahara]   
🔗 **LinkedIn**: (https://www.linkedin.com/in/gabriel-kaahara-54b9b2104/)  

--- 

⭐ **Se este projeto foi útil, deixe uma estrela no repositório!**  
🔗 **Acesse o código**: [github.com/gkaahara/DIO-transfer-learning](https://github.com/gkaahara/DIO-transfer-learning)  

--- 

### **Notas**  
- O dataset original contém 23.262 imagens (80% treino, 10% validação, 10% teste).  
- Para dúvidas, abra uma *issue* no repositório.  

--- 

**🎉 Pronto para ser usado e adaptado!** 🎉
