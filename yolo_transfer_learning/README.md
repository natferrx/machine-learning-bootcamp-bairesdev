# YOLOv5 Transfer Learning - Detecção de Objetos

Este projeto demonstra como aplicar **Transfer Learning** com o modelo **YOLOv5** para tarefas de detecção de objetos usando o dataset COCO128. O treinamento foi realizado no Google Colab com visualização dos resultados e inferência final com imagens reais.

---

## Etapas do Projeto

1. **Preparação do ambiente**
2. **Configuração do dataset**
3. **Transfer Learning com YOLOv5s pré-treinado**
4. **Avaliação de desempenho (mAP, losses)**
5. **Inferência com imagens reais**
6. **Visualização dos resultados**

---

## Resultados

Durante o treinamento de 10 épocas, observamos uma melhoria consistente nas métricas de validação:

- 📉 `val/box_loss`, `val/obj_loss`, `val/cls_loss` em queda
- 📈 `metrics/mAP_0.5` e `metrics/mAP_0.5:0.95` apresentando bons ganhos

### Gráficos de Desempenho

<img width="2400" height="1200" alt="download" src="https://github.com/user-attachments/assets/ef165679-2c2e-45ec-ac62-fea984f3d4d5" />


---

### Predições do Modelo

Abaixo estão alguns exemplos de detecções realizadas com o modelo treinado:

![download](https://github.com/user-attachments/assets/fa9ee612-1a3c-4882-aa9f-c8851083bb87)
![download](https://github.com/user-attachments/assets/f0543c19-5314-4bdc-8b7b-39d35efc236c)
![download](https://github.com/user-attachments/assets/269c63a9-99f8-4d5b-af42-a3660ce88e87)


---

## Conclusão

Este projeto demonstrou com sucesso como utilizar **Transfer Learning com YOLOv5** para detecção de objetos. A combinação de uma arquitetura poderosa e um dataset reduzido permitiu obter resultados precisos com poucas épocas de treinamento.

### Aprendizados principais

- Ajustar corretamente o arquivo `custom.yaml` evita erros de classe.
- Verificar o caminho do `weights/best.pt` é crucial para a inferência.
- A visualização ajuda a interpretar os acertos e erros do modelo.

---

## Desenvolvido por

**Natália Ferreira**  
Bootcamp BairesDev - DIO · 2025  
🚀 Projeto: Transfer Learning com YOLOv5  

**Acesse o projeto no Google Colab:**  
[![Abrir no Colab](https://img.shields.io/badge/Abrir%20no%20Colab-000000?style=for-the-badge&logo=googlecolab&logoColor=F9AB00)](https://colab.research.google.com/drive/1h0b0wba7qNnhGMKmzVJRT5zKlrYgO11k?usp=sharing)


