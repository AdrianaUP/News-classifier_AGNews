# News-classifier_AGNews
Este proyecto entrena y compara tres modelos de lenguaje basados en Transformers (RoBERTa, DeBERTa, ModernBERT) para clasificar noticias del dataset AG News en cuatro categorías:

0 — World

1 — Sports

2 — Business

3 — Science/Technology

Estructura del Repositorio
News-classifier_AGNews/
├── notebooks/
│   └── agnews_train_eval.ipynb
├── src/
│   ├── data_preparation.py
│   ├── model_trainer.py
│   ├── evaluation.py
│   └── rpp_classifier.py
├── data/
│   └── rpp_classified.json  # (opcional)
├── README.md

🚀 Cómo ejecutar el proyecto
Este proyecto está diseñado para ejecutarse en Google Colab. Solo necesitas abrir el notebook agnews_train_eval.ipynb y seguir las celdas paso a paso:

Instala las dependencias (transformers, datasets, scikit-learn, etc.)

Carga y divide el dataset AG News

Entrena los modelos RoBERTa, DeBERTa y ModernBERT

Evalúa y compara sus F1-scores

(Bonus) Clasifica noticias reales de RPP usando un LLM y compara contra tus modelos

📊 Resultados
Se entrenaron tres modelos sobre el dataset AG News

Se compararon sus F1-scores en validación

Se clasificaron 50 noticias reales de RPP usando un LLM como referencia

Se compararon las predicciones de los modelos contra el LLM
├── requirements.txt
├── main.py
