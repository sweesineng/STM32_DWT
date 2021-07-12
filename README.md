<h1>DWT Delay in millis or microsecond</h1>

<p>DWT, Debug Watchpoint and Trace which usually used for system debugging and tracking</p>
<p>The purpose of this utilities is to achived precision millis and micro second timer with DWT</p>
<p>This utilities provide millis and micro second delay and interval measurement</p>
<p>Delay in HAL/LL is not accurate and there is always additional 1ms delay(refer to below)</p>

There is some discussion on this issue in ST community forum : *[Here](https://community.st.com/s/question/0D50X00009XkXQA/llmdelay-taking-an-extra-millisecond)*

<p>Delay using HAL_Delay:</p>

<img src="Images/Delay_HAL.png" width="50%" height="50%">

<p>Delay using LL_mDelay:</p>

<img src="Images/Delay_LL.png" width="50%" height="50%">

<p>Delay using DwtDelay_ms:</p>

<img src="Images/Delay_Dwt.png" width="50%" height="50%">