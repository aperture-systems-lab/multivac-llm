# Multivac LLM

Proyecto del **Semillero Aperture** para la competencia de proyectos.

**Objetivo:** construir un modelo de lenguaje tipo GPT desde cero, en código.

## Punto de partida

Iniciamos con la serie de videos **Neural Networks: Zero to Hero** de Andrej Karpathy.


## Plan de trabajo

| Semana | Tema | Duración | Qué aprendemos |
|:------:|------|:--------:|----------------|
| 1 | micrograd | 2h25m | Backpropagation y cómo se entrena una red neuronal |
| 2 | makemore (bigramas) | 1h57m | Modelos de lenguaje por caracteres y `torch.Tensor` |
| 3 | makemore parte 2: MLP | 1h15m | Perceptrón multicapa, hiperparámetros y splits de datos |
| 4 | makemore parte 3: activaciones y BatchNorm | 1h55m | Diagnóstico de redes profundas y BatchNorm |
| 5 | makemore parte 4: Backprop Ninja | 1h55m | Backpropagation manual, sin `loss.backward()` |
| 6 | makemore parte 5: WaveNet | 56m | Redes más profundas y funcionamiento de `torch.nn` |
| 7 | Let's build GPT | 1h56m | Arquitectura Transformer y mecanismo de atención |
| 8 | GPT Tokenizer | 2h13m | Tokenización con BPE: `encode()` y `decode()` |
| 9 | Let's reproduce GPT-2 (124M), parte 1 | 4h01m (total) | Implementación de GPT-2 y carga de sus pesos originales |
| 10 | Let's reproduce GPT-2 (124M), parte 2 | | Entrenamiento en GPU, optimización y evaluación del modelo |

## Requisitos

- [Python ≥ 3.13](https://www.python.org)
- [uv](https://docs.astral.sh/uv/) 

## Uso

```bash
uv sync                                                        # instalar su entorno
```
