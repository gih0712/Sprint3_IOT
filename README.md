# SPRINT 3 - Mottu

Este repositório contém um projeto de visão computacional que utiliza modelos YOLOv8 e EasyOCR para detectar motos, rastrear por cor e ler placas de veículos usando uma webcam no Google Colab. Ideal para entusiastas de IA e desenvolvimento de sistemas de reconhecimento.

## Requisitos

- **Bibliotecas**:
  - `ultralytics` (para YOLOv8)
  - `easyocr` (para OCR)
  - `opencv-python-headless` (processamento de imagens)
  - `matplotlib` (visualização)
  - `huggingface_hub` (download de modelos)
- **Ambiente**:
  - Google Colab com conexão à internet e webcam funcional.
  - Python 3.x.
- **Modelos**:
  - `yolov8n.pt` (detecção de motos, pré-carregado).
  - `keremberke/yolov8m-nas-license-plate` (detecção de placas, baixado automaticamente).

## Como Usar

1. **Execução no Google Colab**:
   - Abra o notebook em [https://colab.research.google.com/drive/1RAoKneI5z0eb4he0A8iFze_BpnxF7MFU#scrollTo=HQyMXAM84DFM]
   - Execute todas as células do código fornecido.
   - Permita o acesso à webcam quando solicitado.
2. **Configuração da Webcam**:
   - Posicione a câmera a 10-20 cm da placa da moto.
   - Garanta iluminação forte e alinhamento perpendicular da placa.
   - Aguarde 3 segundos para estabilizar a captura.
3. **Visualização dos Resultados**:
   - **Detecção de Placa**: Exibe motos (caixas verdes), placas (caixas vermelhas) e texto OCR (ciano se válido, vermelho se inválido).

## Resultado Esperado

<img width="637" height="473" alt="image" src="https://github.com/user-attachments/assets/1eadb93e-4b91-4bc9-b07d-8bb7f2c02e84" />


## Link do Vídeo

[https://youtu.be/Cp7BVsuGlro]

## Integrantes 

- Caroline de Oliveira RM559123
- Giulia Corrêa Camillo RM554473
