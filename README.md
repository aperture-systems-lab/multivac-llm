# Seminario HPC en LLMs

Proyecto del **Semillero Aperture** para la competencia de proyectos.

**Objetivo:** construir desde cero, en código, un modelo de lenguaje tipo GPT llamado **Multivac**.

## Punto de partida

Iniciamos con la serie de videos **Neural Networks: Zero to Hero** de Andrej Karpathy.


## Plan de trabajo

| Semana | Tema | Duración | Qué aprendemos |
|:------:|------|:--------:|----------------|
| 1 | [micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=2&t=2s) | 2h25m | Backpropagation y cómo se entrena una red neuronal |
| 2 | makemore (bigramas) | 1h57m | Modelos de lenguaje por caracteres y `torch.Tensor` |
| 3 | makemore parte 2: MLP | 1h15m | Perceptrón multicapa, hiperparámetros y splits de datos |
| 4 | makemore parte 3: activaciones y BatchNorm | 1h55m | Diagnóstico de redes profundas y BatchNorm |
| 5 | makemore parte 4: Backprop Ninja | 1h55m | Backpropagation manual, sin `loss.backward()` |
| 6 | makemore parte 5: WaveNet | 56m | Redes más profundas y funcionamiento de `torch.nn` |
| 7 | Let's build GPT | 1h56m | Arquitectura Transformer y mecanismo de atención |
| 8 | GPT Tokenizer | 2h13m | Tokenización con BPE: `encode()` y `decode()` |
| 9 | Let's reproduce GPT-2 (124M), parte 1 | 4h01m (total) | Implementación de GPT-2 y carga de sus pesos originales |
| 10 | Let's reproduce GPT-2 (124M), parte 2 | | Entrenamiento en GPU, optimización y evaluación del modelo |

## Ejercicios

Un solo notebook por semana, dentro de la carpeta de esa semana y con tu usuario de GitHub como nombre:

```
semana-XX-<tema>/<tu-usuario>.ipynb
```

- `<tu-usuario>`: tu usuario de GitHub (`github.com/JeroHoyos` → `JeroHoyos`).
- Dentro del notebook: el ejercicio de la semana resuelto.

Ejemplo: `semana-01-micrograd/JeroHoyos.ipynb`

## Requisitos

- [Python ≥ 3.13](https://www.python.org)
- [uv](https://docs.astral.sh/uv/) 

## Uso

```bash
# instalar entorno
uv sync                                                       
```

## Material extra

- [Components of a Coding Agent](https://magazine.sebastianraschka.com/p/components-of-a-coding-agent) — Sebastian Raschka explica las piezas que forman un agente de programación (como Claude Code o Codex) construido alrededor de un LLM.
- [Coding the KV Cache in LLMs](https://magazine.sebastianraschka.com/p/coding-the-kv-cache-in-llms) — Sebastian Raschka implementa desde cero el KV cache, la técnica que acelera la generación de texto reutilizando las claves y valores de atención ya calculados.
- [AI inference is obviously profitable](https://www.seangoedecke.com/ai-inference-is-obviously-profitable/) — Sean Goedecke estima con números cuánto cuesta servir un LLM (GPUs, energía, tokens) y argumenta que la inferencia es rentable, aunque entrenar modelos nuevos no lo sea.
- [Classical Foundations of Artificial Neural Networks](https://bnaskrecki.faculty.wmi.amu.edu.pl/nnets/_build/html/intro.html) — Libro interactivo de Bartosz Naskręcki que recorre la historia y la matemática de las redes neuronales, desde la neurona de McCulloch-Pitts hasta los Transformers y GPT, con código en Python.

