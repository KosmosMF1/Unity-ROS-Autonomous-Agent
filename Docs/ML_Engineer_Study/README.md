# ML Engineer Study Track

Эта папка — учебный трек по ML/CV/RL, привязанный к реальному проекту **GFS-X Sim-to-Real RL Agent**.

Цель: не просто повторить теорию, а научиться:
- объяснять ML-принципы простым языком;
- принимать технические решения по ML-части проекта;
- анализировать качество модели и причины ошибок;
- проектировать эксперименты;
- учитывать ограничения реального железа;
- уверенно обсуждать CV, RL, sim-to-real и deployment на собеседовании и внутри лаборатории.

## Как работаем

Каждый модуль состоит из 4 частей:

1. **Теория** — что нужно понимать.
2. **Связь с проектом** — где это уже используется в GFS-X.
3. **Практика** — небольшое изменение, анализ или эксперимент прямо в репозитории.
4. **Объяснение вслух** — вопросы, на которые нужно уметь ответить простыми словами.

## План

### 01. ML fundamentals
- supervised / unsupervised / reinforcement learning;
- train / validation / test;
- loss, optimization, overfitting;
- метрики и корректная постановка эксперимента;
- data/domain shift.

### 02. Computer Vision
- classification / detection / segmentation / tracking;
- confidence, IoU, NMS;
- precision, recall, F1, mAP;
- датасет, разметка, аугментации;
- анализ ошибок YOLO.

### 03. Reinforcement Learning
- agent, environment, observation, action, reward;
- policy и value function;
- PPO;
- LSTM и частичная наблюдаемость;
- reward shaping;
- стабильность обучения.

### 04. Sim-to-Real
- domain gap;
- sensor noise;
- latency;
- motor dynamics;
- domain randomization;
- калибровка симуляции.

### 05. ML Deployment / Edge
- inference vs training;
- ONNX;
- CPU/GPU;
- latency, FPS, memory;
- Raspberry Pi;
- ROS pipeline;
- мониторинг и fallback-логика.

### 06. 3D / AR / VR fundamentals
- мировая и локальная системы координат;
- transforms;
- camera model;
- pose estimation;
- основы SLAM;
- где ML используется в XR.

### 07. ML ownership
- перевод бизнес/исследовательской идеи в ML-задачу;
- критерии успеха;
- baseline;
- план эксперимента;
- документация;
- объяснение ограничений нетехническим участникам команды.

## Итог

К концу трека в репозитории должны появиться:
- карта ML-архитектуры проекта;
- описание метрик и критериев успеха;
- журнал экспериментов;
- анализ основных failure modes;
- рекомендации по sim-to-real и edge inference;
- краткая ML-документация, которую можно показать новому участнику проекта.
