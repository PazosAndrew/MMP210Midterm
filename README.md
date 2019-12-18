# MMP210Midterm
<h1>  Processing to Arduino color wheel controlled RGB LED </h1>
 
 <h2> Items required for this project </h2> 
 <ol>
  <li> 1x Arduino Uno  /  Elegoo UNO board </li>
  <li> 4x Jumper Wires </li>
  <li> 3x 220 Ohm Resistors </li>
  <li> 1x RGB LED </li>
  <li> 1x USB cable type A/B. </li>
  <li> any "relatively" Modern computer or laptop </li> </ol>
  
  <h2> Software requirements </h2>
   <li> <a href="https://www.arduino.cc"> Arduino IDE </a> Arduino IDE  </li>
 <li>  <a href="https://processing.org/download/"> Processing </a>   </li>  <ol>
  
  <h3> Project Description </h3> 
  
  <p>  This project utilizes Processing to draw a color / tint wheel on the screen and uses the mouse cursor's position to send data  to Arduino. Arduino interprets that data and uses it to light up the RGB LED to match the color from the tint wheel. Here is a short video I made of it in action. In this video I demonstrate the circuit setup, a brief look at the code and the interaction between Processing and Arduino.  https://www.youtube.com/watch?v=e_odZHztHy8  </p>

  <h2> Challenges faced </h2> 
   <p> As I was putting this project together I faced a handful of challenges along the way. The problem and solution is provided below.
<ul> <li> Processing  - array index out of bounds exception .    Solution: The wrong COM PORT was defined in the code. Looked in device manage to fix. To elaboorate, Arduino was showing COMPORT 4 , however device manager showed COM PORT1 </li>
  <li> Baud rate issue  -  Serial Monitor was showing gibberish and Arduino was throwing me an error. Solution: Set baud rate to 9600 in both Processing and Arduino codes. </li>
 
  <li> RGB light not turning on -  LED not responding to any arduino codes.   Solution - I had the wiring mixed up. There is one leg out of the 4 on the RGB Connecter that is longer than the rest. This is the ground connector to Arduino. </li>
  
   <li> RGB LED not turning on yet again. - After wires were connected and I ran an RGB " Blink" example, not every color was showing.  Solution - Rechecked all of the wires and connections, had a loose resistor not connecting properly on the bread board. </li> </ul>
   
   <h3> Why I chose this project </h3> 
 <p> I chose this project because I always enjoyed how RGB looks. I tend to do quite a bit of PC gaming and have a plethora of RGB peripherals such as an RGB mouse, an RGB Mouse mat, an RGB headset, and even  an RGB Headset Stand!  I also have various LED lights and light strips around my room that give an ambient environment. Curious about how RGB itself may work this seemed like a task that I could come up with and put together using various resources such as codes from examples built into Arduino, looking up some codes online, and putting in my own changes as I worked to plug it all together.  Included in my Repo are the codes for both Processing and arduino, a Circuit diagram and some photos / video that show cases this project in action.  </p>
  
