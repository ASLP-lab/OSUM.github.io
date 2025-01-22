Large Language Models (LLMs) have made significant progress in various downstream
tasks, inspiring the development of Speech Understanding Language Models (SULMs) to
enable comprehensive speech-based interactions. However, most advanced SULMs are developed by the industry, leveraging large-scale datasets and computational resources that
are not readily available to the academic community. Moreover, the lack of transparency
in training details creates additional barriers to further innovation. In this study, we
present OSUM, an Open Speech Understanding Model designed to explore the potential
of training SLUMs under constrained academic resources. The OSUM model combines
a Whisper encoder with a Qwen2 LLM and supports a wide range of speech tasks, including speech recognition (ASR), speech recognition with timestamps (SRWT), vocal
event detection (VED), speech emotion recognition (SER), speaking style recognition
(SSR), speaker gender classification (SGC), speaker age prediction (SAP), and speechto-text chat (STTC). By employing an ASR+X training strategy, OSUM achieves efficient
and stable multi-task training by simultaneously optimizing ASR alongside target tasks.
Beyond delivering strong performance, OSUM emphasizes transparency by providing
openly available data preparation and training methodologies, offering valuable insights
and practical guidance for the academic community. By d
