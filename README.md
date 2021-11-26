<h1 align="center">Arduino official Library</h1>
    

<table align="center">

  <tr align="center">
    <th>library</th>
    <th>extension</th>
    <th>Meaning</th>
  </tr>
  
  <tr align="center">
    <td><a href="/Arduino.h">arduino</a></td>
    <td>h</td>
    <td>標準ライブラリー</td>
  </tr>
  
  <tr align="center">
    <td rowspan="2"><a href="/Print.h">print</a></td>
    <td>h</td>
    <td rowspan="2">Serial.print(println)</td>
  </tr>
  
  <tr align="center">
    <td>cpp</td>
  </tr>
  
  <tr align="center">
    <td><a href="/Servo.h">Servo</a></td>
    <td>.h</td>
    <td>サーボにPWM送るやつ</td>
  </tr>
  
  <tr align="center">
    <td><a href="/binary.h">binary</a></td>
    <td>.h</td>
    <td>脳筋二進数定義ファイル</td>
  </tr>

</table>


<table align="center">
 <tr align="center">
    <th colspan="3"><a href="/Arduino.h">Arduino.h</a></th>
 </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>HIGH, LOW</td>
    <td>1, 0</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>INPUT, OUTPUT, INPUT_PULLUP</td>
    <td>0, 1, 2</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>min(a, b)</td>
    <td>最小値</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>max(a, b)</td>
    <td>最大値</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>abs(x)</td>
    <td>絶対値</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>constrain(amt, Low, High)</td>
    <td>切り捨て</td>
  </tr>
  
  <tr align="center">
    <td>long</td>
    <td>map (val, fromL, fromH, toL, toH)</td>
    <td>圧縮</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>round(x)</td>
    <td>四捨五入</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>radians(deg)</td>
    <td>度>ラジアン</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>degrees(red)</td>
    <td>ラジアン>度</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>sq(x)</td>
    <td>2乗</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>bitWrite(value, bit, bitvalue)</td>
    <td>bitに書き込み</td>
  </tr>
  
  <tr align="center">
    <td>#define</td>
    <td>bitRead(value, bit)</td>
    <td>bitから読み取り</td>
  </tr>
  
  <tr align="center">
    <td>#typedef</td>
    <td>word</td>
    <td>unsigned int</td>
  </tr>
  
  <tr align="center">
    <td>#typedef</td>
    <td>boolean</td>
    <td>bool</td>
  </tr>
  
  <tr align="center">
    <td>#typedef</td>
    <td>byte</td>
    <td>uint8_t</td>
  </tr>
  
  <tr align="center">
    <td>void</td>
    <td>pinMode(pin, mode)</td>
    <td>io設定</td>
  </tr>
  
  <tr align="center">
    <td>void</td>
    <td>digitalWrite(pin, val)</td>
    <td>デジタル出力</td>
  </tr>
  
  <tr align="center">
    <td>int</td>
    <td>digitalRead(pin)</td>
    <td>デジタル入力</td>
  </tr>
  
  <tr align="center">
    <td>void</td>
    <td>analogWrite(pin, val)</td>
    <td>アナログ(PWM)出力</td>
  </tr>
  
  <tr align="center">
    <td>int</td>
    <td>analogRead(pin)</td>
    <td>アナログ入力(10bitAD変換)</td>
  </tr>
  
  <tr align="center">
    <td>unsigned long</td>
    <td>millis()</td>
    <td>経過時間(ms)</td>
  </tr>
  
  <tr align="center">
    <td>unsigned long</td>
    <td>micros()</td>
    <td>経過時間(μs)</td>
  </tr>
  
  <tr align="center">
    <td>void</td>
    <td>delay(ms)</td>
    <td>待機(ms)</td>
  </tr>
  
  <tr align="center">
    <td>void</td>
    <td>delayMicroseconds(μs)</td>
    <td>待機(μs)</td>
  </tr>
  
  <tr align="center">
    <td>void</td>
    <td>setup</td>
    <td>メインループ前に１度呼ばれる</td>
  </tr>
  
  <tr align="center">
    <td>long</td>
    <td>loop</td>
    <td>メインループ</td>
  </tr>
  
  <tr align="center">
    <td rowspan="2">long</td>
    <td>random(val)</td>
    <td>疑似乱数生成(0~val)</td>
  </tr>
  
  <tr align="center">
    <td>random(min,max)</td>
    <td>疑似乱数生成(min~max)</td>
  </tr>
  
  <tr align="center">
    <td>void</td>
    <td>randomSeed(seed)</td>
    <td>シード値設定</td>
  </tr>
  
  <tr align="center">
    <td>void</td>
    <td>tone(pin, frequency, duration=0)</td>
    <td>圧電ブザー発振</td>
  </tr>
  
</table>
