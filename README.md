# Design the Programming Language
Code include a lot of languages: http://rosettacode.org/wiki/Rosetta_Code

Technique in creating for programming language

![](https://www.concettolabs.com/blog/wp-content/uploads/2017/07/Web-Development-Frameworks.png)

## Machine Language
Machine code is a computer program written in machine language instructions that can be executed directly by a computer's central processing unit (CPU). Each instruction causes the CPU to perform a very specific task, **such as a load, a store, a jump, or an ALU operation on one or more units of data in CPU registers or memory.**

![](http://i.imgur.com/9AWZHe2.jpg)

Để tạo ra mã máy trên một mạch để nghiên cứu thì không phải không thể. Bạn có thể chọn [mạch FPGA](https://vi.wikipedia.org/wiki/Field-programmable_gate_array) ở [cửa hàng](https://www.amazon.com/slp/fpga-boards/ef66a6u55eou46p) hay phòng thí nghiệm thực hành của nhà trường. Sử dụng các ngôn ngữ VHDL (VHSIC hardware description language) để viết CPU cho mạch FPGA. Bạn tham khảo [phần 1](http://labs.domipheus.com/blog/designing-a-cpu-in-vhdl-part-1-rationale-tools-method/), [phần 2](http://labs.domipheus.com/blog/designing-a-cpu-in-vhdl-part-2-xilinx-ise-suite-register-file-testing/) ở đây. Sau khi viết chương trình CPU biên dịch trong Xilinx ISE thì bạn tiến hành nạp code xuống FPGA. Bạn cần chuẩn mạch FPGA trắng, mạch nạp và kết nối mạch nạp với cổng usb của FPGA, kết nối cổng nguồn với cổng usb của PC. Để mạch FPGA có thể giao tiếp với PC để truyền dữ liệu thì bạn cài driver cẩn thận (đĩa driver có sẵn khi mua mạch). Bạn có thể tham khảo video [nạp code xuống ROM mạch FPGA](https://youtu.be/DKFhqLffHF4) 

## Assembly language
## Cross Assembler
## High-level programming language
## Build VGA Driver to display image motion in the FPGA PC 
## Artificial Intelligence in the Compiler
