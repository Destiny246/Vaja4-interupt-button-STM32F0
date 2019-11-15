# Vaja4-interupt-button-STM32F0
<ul>
  <h3>Odgovori na vprašanja:</h3>
    <h4>2.b: </h4>
      <li>Input pin: PA0</li>
      <li>Output pin modra LED: PC8</li>
      <li>Output pin zelena LED: PC9</li>
    <h4>3.d:</h4>
      <li>HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9);</li>
    <h4>3.e:</h4>
      <li>100ms</li>
    <h4>3.f:</h4>
      <li>HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_8);</li>
    <h4>3.g:</h4>
      <li>HAL_Delay(500);</li>
    <h4>4.b:</h4>
      <li>Ob pritisku na modro tipko vklopimo zeleno LED, ki obstane vklopljena do naslednjega pritiska na modro tipko.</li> 
    <h4>4.c:</h4>
      <li>Pritisk natipko in prižig zelene LED ne vplivata na enakomerno urtipanje modre LED.</li> 
</ul>

<ul>
  <h3>Komentar:</h3>
  <p>
    Med programiranjem ni bilo večjih težav. Največja problem se je pojavil pri nastavljanju enačbe za šesti pin.<br>
    Tipke so nastavljene na pull up logiko.
  </p>
</ul>
