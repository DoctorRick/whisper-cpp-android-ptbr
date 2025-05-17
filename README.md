# whisper-cpp-android-ptbr
Transcrição offline de áudio em texto (PT-BR) usando whisper.cpp otimizado, rodando no Android via Termux. Modelos tiny/base. Foco em script automatizado para gravação e transcrição.

## Objetivo
Rodar transcrição de áudio offline, usando whisper.cpp em Termux Android.
- Modelos tiny/base (foco em PT-BR)
- Input: microfone ou arquivo .wav
- Output: transcrição em texto no terminal

## Primeiros desafios para o Codex:
- Automatizar instalação do whisper.cpp e dependências via Termux
- Baixar e colocar modelo tiny ou base
- Exemplo de comando de uso real: `./main -m models/ggml-tiny.bin -f test.wav -l pt`
- (Opcional) script bash para automatizar gravação e transcrição

## Estrutura sugerida
- /models
- /scripts
- /test_audio
