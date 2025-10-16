# Simulação Pisca-Pisca - TinkerCAD

## Código Implementado

### Arquivo: `codigo_arduino.ino`

```cpp
// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```

### Explicação do Código

1. **`void setup()`**: Função executada uma única vez na inicialização
   - `pinMode(LED_BUILTIN, OUTPUT)`: Configura o pino do LED como saída
2. **`void loop()`**: Função executada continuamente
   - `digitalWrite(LED_BUILTIN, HIGH)`: Liga o LED
   - `delay(1000)`: Aguarda 1000ms (1 segundo)
   - `digitalWrite(LED_BUILTIN, LOW)`: Desliga o LED
   - `delay(1000)`: Aguarda mais 1 segundo

## Componentes Utilizados

- Arduino Uno
- Protoboard
- LED (OFF_BOARD)
- Resistor
- Ligações elétricas

## Evidências da Implementação

### Vídeo Demonstrativo

Aqui está um vídeo demonstrando o funcionamento do pisca-pisca no TinkerCAD:

[![Vídeo do Pisca-Pisca](tinkercad_blink_video.mp4)](tinkercad_blink_video.mp4)

### Screenshot do Projeto

![Projeto TinkerCAD](Neat%20Amur-Bojo.png)




