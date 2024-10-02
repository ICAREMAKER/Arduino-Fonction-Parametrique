

# FONCTION PARAMETRIQUE ![arduinoThumb](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/1e80c0a0-27bd-4b96-a6e1-88ef7eca9098) ![C++-Logo wine](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/882aa901-1f05-43d5-9574-60db4e7b6537)

![Qb](https://github.com/ICAREMAKER/Arduino-Pattern-8servos/assets/107696317/3b96b3af-cc64-48fe-a2df-3e50cb406b34)


## Au démarrage
```C
void setup() {
  pinMode(9, OUTPUT); //Je definis la broche 9 comme une sortie
  pinMode(10, OUTPUT);//Je definis la broche 10 comme une sortie
}
```
## J'insere ma fonction parametrique
```C
void loop() {
  blinkLED(9, 500); //inserer les valeurs->(n°broche,durée en millis)
  blinkLED(10, 1000);//inserer les valeurs->(n°broche,durée en millis)
}
```
## Je crée ma fonction presonnalisable
```C
void blinkLED(int pin, int duration) {
  digitalWrite(pin, HIGH);
  delay(duration);
  digitalWrite(pin, LOW);
  delay(duration);
}
```
