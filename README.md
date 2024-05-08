# translit
Line filter that transliterate between the two Serbian scripts.

[Линијски филтер](https://en.wikipedia.org/wiki/Filter_(software)) који врши пресловљавање писама која се користе у српском језику.

Преузима текст са стандардног улаза, пресловљава га и шаље на стандардни излаз.

Доста тога је преузето из одличног алата [Ћирилизатор](https://github.com/turanjanin/cirilizator) Јована Турањанина.

# Како ради
Програм прихвата две заставице. Једнoм се дефинише смер пресловљавања:
* латиница у ћирилицу (-l2c)
* ћирилица у латиницу (-c2l)

а другом се наводи формат улаза:
* прости (чисти) текст (-text)
* (X)HTML (-html)

Обавезно морају да се наведу две заставице, једна за смер и једна за формат улаза. У сваком другом случају, исписује се кратка порука о употреби.

Програм очекује да је улазни текст UTF-8 кодиран. Може да се користи самостално, преусмеравањем улаза и излаза у командној линији, или из текст едитора као што је [Vim](https://en.wikipedia.org/wiki/Vim_(text_editor)) 
# Примери
///
# Изградња
///
# Лиценца
Ово је софтвер отвореног кода, који се слободно може користити у оквиру [MIT лиценце.](https://github.com/eevan78/translit/blob/main/LICENSE)
