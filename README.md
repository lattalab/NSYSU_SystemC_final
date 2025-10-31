# SystemC_final

* Goal: Design LeNet in SystemC programming language
<img width="1239" height="337" alt="image" src="https://github.com/user-attachments/assets/4394b70d-6e98-4df8-b183-36b5da8d3c9f" />

* Hardware Architecture overview
<img width="806" height="370" alt="image" src="https://github.com/user-attachments/assets/306bab73-1eab-4603-acaf-de35b51883d7" />

* two version of number representation
  * floating point: based on `IEEE 754 Floating Point Standard`
  * fixed point   : read out value and view as `16-bits integer`, but getting floating result after propagate the value into LeNet.

如果想切換 fixed_point 跟 floating-point 可以在 define.h 註解  

有些檔案是用來記錄測試後的結果 (.txt file)
