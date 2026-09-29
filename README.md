# Multivac LLM

Proyecto del **Semillero Aperture** para la competencia de proyectos.

**Objetivo:** construir un modelo de lenguaje tipo GPT desde cero, en código.

## Punto de partida

Iniciamos con la serie de videos **Neural Networks: Zero to Hero** de Andrej Karpathy.


## Plan de trabajo

Cada video de ~2 horas se trabaja en **2 semanas**; los más cortos, en 1. En total son **18 semanas**.

| Semanas | Tema | Duración | Qué aprendemos |
|:-------:|------|:--------:|----------------|
| 1–2 | [micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=2&t=2s) | 2h25m | Backpropagation y cómo se entrena una red neuronal |
| 3–4 | makemore (bigramas) | 1h57m | Modelos de lenguaje por caracteres y `torch.Tensor` |
| 5 | makemore parte 2: MLP | 1h15m | Perceptrón multicapa, hiperparámetros y splits de datos |
| 6–7 | makemore parte 3: activaciones y BatchNorm | 1h55m | Diagnóstico de redes profundas y BatchNorm |
| 8–9 | makemore parte 4: Backprop Ninja | 1h55m | Backpropagation manual, sin `loss.backward()` |
| 10 | makemore parte 5: WaveNet | 56m | Redes más profundas y funcionamiento de `torch.nn` |
| 11–12 | Let's build GPT | 1h56m | Arquitectura Transformer y mecanismo de atención |
| 13–14 | GPT Tokenizer | 2h13m | Tokenización con BPE: `encode()` y `decode()` |
| 15–16 | Let's reproduce GPT-2 (124M), parte 1 | 4h01m (total) | Implementación de GPT-2 y carga de sus pesos originales |
| 17–18 | Let's reproduce GPT-2 (124M), parte 2 | | Entrenamiento en GPU, optimización y evaluación del modelo |

## Ejercicios

Un solo notebook por video, dentro de la carpeta de ese video y con tu usuario de GitHub como nombre:

```
semana-XX[-YY]-<tema>/<tu-usuario>.ipynb
```

- `XX[-YY]`: la semana o semanas del video (`semana-05-...` o `semana-01-02-...`).
- `<tu-usuario>`: tu usuario de GitHub (`github.com/JeroHoyos` → `JeroHoyos`).
- Dentro del notebook: el ejercicio del video resuelto.

Ejemplo: `semana-01-02-micrograd/JeroHoyos.ipynb`

## Requisitos

- [Python ≥ 3.13](https://www.python.org)
- [uv](https://docs.astral.sh/uv/) 

## Uso

```bash
# instalar entorno
uv sync                                                       
```
